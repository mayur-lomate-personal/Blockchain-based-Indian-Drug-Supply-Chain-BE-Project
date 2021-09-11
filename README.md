# Blockchain-based hub that helps to identify counterfeit products in the Indian drug supply chain.

1. Counterfeit, or fake, medicines are manufactured using incorrect or harmful ingredients. These medicines are then packaged and labeled to look like the real thing. Counterfeit medicines are unsafe because they may not work and could harm you and are originated from outside our boarders.2. Since the Drug Supply Chain Security Act, obliging wholesalers to verify the authenticity of drugs before reselling, has come into force in the United States in November 2019. We want to bring the same to India.
3. Traditional databases are vulnerable to data tampering and data leakage and there is a possibility of loss due to centered storage, hence blockchain is the best option for such situation, since the goal of blockchain is to allow digital information to be recorded and distributed, but not edited.
4. Supply chain management is the management of the flow of goods and services and includes all processes that transform raw materials into final products. It involves the active streamlining of a business's supply-side activities to maximize customer value and gain a competitive advantage in the marketplace.

The architecture uses the blockchain framework and Node js for development. There are 2 organizations with some number of peers attached to them and also ca authority for each organization. The server is kept as a rest server developed using Node js and Hyperledger fabric Node js SDK. There is also a Web App. The smart contract is written in go language and deployed on peers. Smart Contract includes the functions to write, retrieve and update information.

# Flow

 - The input to the system depends on the person or organization accessing it. If it’s manufacturer than he may be adding info to it or updating the info. Distributer may verify the info and update the current location. Customer may read and verify the info.
 - The Data inserted by manufacturer is returned with qr code. While updating the info it is normally updated and success message is returned.
 - Manufacturer verify’s the information, by seeing that whether the delivery was for him or not and whether it is told to be the same product or not, if everything is right than he updates the information as received.
 - Customer verifies the information and then buys the product. Customer needs to get satisfied of the product he is buying.
