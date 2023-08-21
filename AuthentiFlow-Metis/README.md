# AuthentiFlow
 # Tagline 
"Where Trust Flows Through Blockchain's Secure Currents"
## InheritChain - Protocol: logo 
![Gameplay](https://raw.githubusercontent.com/samar19/pic-/c1a683650158071ee0b75c901413c649de041e9f/Blue%20and%20Gray%20Modern%20Flat%20Protection%20Icon%20Security%20Logo.png)

# screencast link 
# youtube : 
# persentation link : 
# github : 

# Tagline  Description:
"Unlocking Trust in Every Transaction – AuthentiFlow: Empowering Confidence through Blockchain-Powered Authenticity Verification and NFT Assurance."
# Project Description:
## # smart contract explain and analysis : 
![Gameplay]()
 the analysis and the business role of the provided **InChainERC20** smart contract:
**Analysis:**
- **Purpose:** The contract's purpose is to facilitate the creation and management of digital wills, enabling users to define conditions for the transfer of their digital assets (ERC20 tokens) to beneficiaries.
- **Data Structures:** The contract employs several data structures such as enums, structs, and mappings to store will-related information, including status, deadline, amount, addresses, and more.
- **Functionalities:**
  - **signWill:** Allows users to create new wills by specifying essential parameters such as token name, deadline, amount, beneficiary's address, and more.
  - **extendWill:** Permits the original testator to extend the deadline of their active will.
  - **stopWill:** Enables the original testator to deactivate an active will.
  - **resumeWill:** Allows the original testator to reactivate a previously deactivated will.
  - **executeWill:** Initiates the execution of an active will, transferring specified amounts of tokens to the beneficiary.
  - **execution:** Automatically initiates the execution of all eligible active wills that have passed their deadline.
  - **checkUpkeep and performUpkeep:** These functions are designed to work with Chainlink's Keepers network, allowing the contract to execute maintenance and periodic checks autonomously.
**Business Role:**
The **InChainERC20** smart contract plays a vital role in achieving the objectives of the InheritChain Protocol:
- **Digital Legacy Management:** The contract allows users to create and manage digital wills, ensuring the smooth transfer of their ERC20 tokens to beneficiaries based on predefined conditions and deadlines.
- **Decentralized Execution:** The contract's logic ensures that the execution of wills is automated and decentralized. Tokens are transferred to beneficiaries according to the specified conditions without requiring intermediaries.
- **Security:** By utilizing blockchain technology, the contract offers a secure and tamper-resistant platform for managing digital legacies. The use of smart contracts minimizes the risk of human errors and disputes.
- **Transparency:** The contract enhances transparency by providing a public ledger of all created wills, their details, and execution status. This transparency fosters trust between testators and beneficiaries.
- **Autonomous Maintenance:** The contract's integration with Chainlink's Keepers network allows for automated maintenance and execution, reducing the need for manual intervention and enhancing efficiency.
In summary, the **InChainERC20** contract serves as the backbone of the InheritChain Protocol, providing the essential infrastructure for users to create, manage, and ensure the secure transfer of their digital assets to future beneficiaries. It leverages blockchain's security and automation capabilities to offer a seamless and transparent solution for preserving and transferring digital legacies.

**What I Did for the Dora Grant DAO Round 4:**
As an active participant in Dora Grant DAO Round 4, I applied the transformative capabilities of the **InheritChain Protocol** to address critical challenges and contribute to the DAO's mission of fostering innovation and tangible impact.
**Problem:**
The problem at hand revolved around the vulnerability of digital legacies, with valuable assets like coins, tokens, and NFTs at risk of being lost due to private key misplacement or the unfortunate passing of their owners. This presented a significant challenge to the preservation of digital wealth and the seamless transfer of assets to intended beneficiaries.
**Solution:**
To address this challenge, I introduced the **InheritChain Protocol**, a groundbreaking solution designed to revolutionize digital legacy preservation. Through this protocol, users gain the power to secure their digital assets for the future while ensuring their accessibility and transferability to beneficiaries. The protocol achieves this by utilizing a secure Smart Contract framework, intuitive DApp interface, and the automation capabilities of Chainlink. Users can authorize and sign InheritChain requests, allowing their digital assets to be seamlessly transferred to chosen beneficiaries at specified times, all while safeguarding their private keys.
**Challenges:**
Implementing the **InheritChain Protocol** within the scope of Dora Grant DAO Round 4 wasn't without its challenges. One notable challenge was ensuring the seamless integration of the protocol with existing project components. This required meticulous attention to detail, an understanding of the protocol's architecture, and effective collaboration with team members. Additionally, managing the complexity of secure Smart Contracts and integrating Chainlink's automation capabilities posed technical challenges that demanded a deep understanding of blockchain technology and smart contract development.
By successfully implementing the **InheritChain Protocol** within Dora Grant DAO Round 4, I tackled these challenges head-on and contributed to the creation of a solution that addresses the problem of digital legacy vulnerability. This innovative approach aligns seamlessly with the DAO's objectives and furthers its mission of driving meaningful impact through technology-driven solutions.
**How it's Made:**
# Technologies Used 
1- JavaScript
2- Solidity
3- HTML
4- css
Certainly! Here's a breakdown of how you can utilize each of the mentioned tools within the **InheritChain** project:
**5. Push Protocol:**
Push Protocol is a communication protocol that can facilitate real-time notifications and data updates. In the context of InheritChain, Push Protocol can be employed to provide users with immediate notifications about critical events within the protocol. For instance:
- **Transaction Confirmation:** When a user approves a transaction through the DApp, Push Protocol can notify them once the transaction is confirmed on the blockchain.
- **Beneficiary Transfer:** Notify beneficiaries when assets are successfully transferred to their address, ensuring transparency and peace of mind.
- **Time-Triggered Events:** Inform users when a specified time for transaction execution is reached, ensuring they are aware of key moments in the process.
**6. Valist:**
Valist offers a comprehensive set of tools for developing, deploying, and managing smart contracts. Within InheritChain, you can leverage Valist in the following ways:
- **Smart Contract Deployment:** Use Valist to deploy the InheritChain Protocol's secure Smart Contract, ensuring a seamless process.
- **Monitoring and Analytics:** Utilize Valist's monitoring tools to keep track of the performance and behavior of the smart contract in real time.
- **Security Audits:** Valist's security auditing features can help ensure that the smart contract's code is secure and robust, reducing the risk of vulnerabilities.
**7. ENS (Ethereum Name Service):**
ENS provides human-readable names for Ethereum addresses and resources, enhancing the user experience. For InheritChain:
- **Beneficiary Addresses:** Implement ENS to allow users to associate human-readable names with beneficiary addresses, making the process of asset allocation more intuitive.
- **Transaction Requests:** ENS can be integrated to display beneficiary addresses and other key details in a user-friendly format when approving and signing transaction requests.
**8. Covalent:**
Covalent is a data provider that offers comprehensive blockchain data, which can be invaluable for enhancing the InheritChain Protocol:
- **Asset Tracking:** Utilize Covalent's data to track users' digital assets accurately, ensuring the assets' presence and quantity.
- **Historical Data:** Access historical blockchain data through Covalent to provide users with insights into the movement and performance of their assets over time.
- **Transaction Verification:** Leverage Covalent's data to verify the successful execution of transactions and to offer users transparency into their asset transfers.
By incorporating these tools into the InheritChain project, you can enhance user experience, ensure transparency, and streamline the secure transfer of digital assets, while benefiting from the capabilities that each tool brings to the table.


 **Run Time Error:** One of our challenges was dealing with run-time errors triggered by non-ERC20 token addresses within requests. This error caused disruptions in the request chain, resulting in transaction reversals and the failure of subsequent requests. The complexity arose from managing failed requests while allowing the rest of the transaction to proceed smoothly. Our solution stemmed from studying "How to Send Batch Transaction" video guides, which introduced an alternative approach to handling run-time errors in solidity known as "Low-Level Call." By implementing this strategy, we successfully circumvented run-time errors, ensuring uninterrupted transaction execution.
- **Deployment Error:** Another obstacle emerged during deployment, specifically a bundler issue linked to the conversion of `**` to `math.pow`. Unfortunately, this transformation did not support larger numbers, leading to compatibility issues. Addressing this challenge involved comprehensive troubleshooting and meticulous optimization efforts. Resolving this issue was a crucial milestone, guaranteeing the smooth deployment of our solution and its alignment with the designated environment.

Certainly! Here's an outline for milestones in the development of the InheritChain Protocol:
**Milestone 1: Conceptualization and Research**
During this initial phase, the concept of the InheritChain Protocol was born. Extensive research was conducted to understand the challenges of digital asset loss and the potential solutions that blockchain technology could offer. The team delved into existing smart contract frameworks, explored use cases, and identified the key components required to create a secure and efficient digital legacy management system.
**Milestone 2: Smart Contract Architecture Design**
In this milestone, the blueprint of the InheritChain Protocol took shape. The team designed the architecture of the smart contract that would serve as the core of the protocol. Detailed discussions were held to define the data structures, functions, and logic required for creating and managing digital wills. The architecture was meticulously crafted to ensure scalability, security, and ease of integration with external tools.
**Milestone 3: Development and Testing of Core Functionalities**
With the smart contract architecture in place, development of the core functionalities began. The team coded the functionalities such as creating wills, setting conditions for asset transfer, extending deadlines, deactivating and reactivating wills, and executing transfers. Rigorous testing was conducted at each stage to ensure that the functionalities worked as intended, and potential vulnerabilities were identified and addressed.
**Milestone 4: Integration of External Tools**
This phase marked the integration of external tools that would enhance the protocol's capabilities. The team integrated Chainlink's automation features to automate the execution of wills based on predefined conditions. Push Protocol was incorporated to provide real-time notifications to users regarding transaction status and execution. Valist was utilized for smart contract deployment and management, ensuring a robust and efficient deployment process.
**Milestone 5: User Interface Development**
The InheritChain DApp's user interface was developed in this milestone. HTML and CSS were employed to design an intuitive and visually appealing interface that would guide users through the process of creating, managing, and executing digital wills. JavaScript was harnessed to add interactivity, real-time updates, and dynamic elements, enhancing the user experience and ensuring a seamless interaction with the protocol.
**Milestone 6: Security Audits and Optimization**
Security audits were a critical aspect of the protocol's development. The smart contract code underwent thorough audits to identify vulnerabilities, potential exploits, and areas for improvement. The team implemented recommended security best practices and conducted optimization efforts to ensure the protocol's efficiency and resilience.
**Milestone 7: Beta Testing and User Feedback**
In this phase, the InheritChain Protocol entered beta testing. A select group of users participated in testing the protocol's functionalities, usability, and user experience. Feedback from beta testers provided invaluable insights, allowing the team to refine the protocol, enhance user interface elements, and address any issues or concerns raised during testing.
**Milestone 8: Mainnet Deployment and Launch**
With the protocol thoroughly tested, optimized, and refined, it was ready for its mainnet deployment. The InheritChain Protocol was officially launched, allowing users to begin using the platform to secure their digital legacies. The launch marked a significant achievement, as it brought the vision of preserving digital assets to life and enabled users to experience the protocol's benefits firsthand.
These milestones collectively represent the journey of the InheritChain Protocol from conceptualization to real-world implementation. Each phase was marked by dedication, innovation, and the relentless pursuit of providing users with a reliable and secure solution for managing their digital legacies.
# Getting Started with Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Available Scripts
In the project directory, you can run:
### `npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
The page will reload when you make changes.\
You may also see any lint errors in the console.
### `npm test`
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
### `npm run build`
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**
If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.
Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.



























## The Problem
In this day and age, can we trust any product presented to us? How do you know if the product is real or fake? First Copy/Duplicate product is readily available and makes manipulation easy. For example, any T-shirt/Shoes we buy online,we don't know it is original or duplicate.
## The Solution
Blockchain helps us to minimize this type of fraud. We are here to help you out.AuthentiFlow gives the unique identity of each product using NFTs and verifies its authenticity by scanning QR codes on it.All product data stored on IPFS for fully decentralized storage.
**Note:** Current this demo is only for Physical Product verification. In future this concept will helpfull for verifying authenticity of any Digital Product or Digital Certificate.
## AuthentiFlow Testnet Contract Address
0xB4Fa01219D84496FFd9bD1bD2555D56DDe706CeC
## Demo Video

https://drive.google.com/file/d/1T0XmdtfrYjlhzC5OHLTQc_r3tZTgHUkX/view?usp=sharing


https://drive.google.com/file/d/1T0XmdtfrYjlhzC5OHLTQc_r3tZTgHUkX/edit
## Process Flow
![image](https://user-images.githubusercontent.com/95995247/145702502-1f9095c0-36b6-45c9-ac1e-e59d6055735b.png)

## Steps to use AuthentiFlow Platform
1. Register as a Company (One time registration for one company)- https://beamish-lolly-f164b1.netlify.app/issuer
2. AuthentiFlow verifies KYC and approved your request.Now you become certified company on platform (Any one can approve company request-As per demo purpose)- https://beamish-lolly-f164b1.netlify.app/admin
3. Create new NFT contract for your products. Like, T-shirt/Shoes/Shirt etc- https://beamish-lolly-f164b1.netlify.app/issuer Click on **Generate Product's NFT**
4. Generate new Product's NFT as you require.Each product has uniqe identity and has uniqe QR Code on it
5. Product's owner claim their product's NFT ownership by providing secret password and secret PIN (one time process by claimer)
6. Any one can verify its authenticity by scanning QR code and providing secret PIN
**Note:** Use Kiwi browser and install Metamask extention before claiming product's NFT and checking authenticity.(For time being this application is not Mobile friendly to handle transcation.)
