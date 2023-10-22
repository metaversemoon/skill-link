#  SkillLink
Skill Link Freelancer App is a groundbreaking platform that revolutionizes the way freelancers connect with project owners. Our innovative approach allows freelancers to not only secure project opportunities but also receive payment for their services before the project owner receives the final solution. This unique system offers freelancers a level of financial security and peace of mind that is unparalleled in the freelancing world. With Skill Link, both freelancers and project owners can collaborate with confidence, knowing that payments are prompt and work is rewarded promptly. Say goodbye to delayed payments and uncertainties – Skill Link is here to reshape the freelancing landscape, making it a win-win for all parties involved. Join us and experience the future of freelancing.

## Technologies
For this project, our technology stack encompasses several key components:

We utilize IPFS-NFTStorage to securely store all user profiles, ratings, portfolios, job information, and reviews as NFTs. This ensures data integrity and reliability.

Our smart contract development relies on Solidity and Hardhat, providing a robust and well-tested foundation for our blockchain operations.

To handle the minting and completion of jobs, we employ the OpenZeppelin ERC721 standard, streamlining our contract functionality. We also utilize the ERC721 template for accelerated smart contract development.

For local blockchain development and testing, we turn to Hardhat, which facilitates efficient and reliable development workflows.

On the frontend, we harness the power of Tailwind, Next.js, and React.js to create an engaging and user-friendly interface. Ethers.js serves as the bridge to connect with the blockchain.

In addition, we incorporate WorldCoin to enhance the functionality of our platform.

To ensure scalability and accessibility across various networks, we leverage The Mantle, Scroll and Polygon Network for our deployment strategies.


##  Bounties:
- Our application is now operational on the Scroll network, offering expedited transactions, heightened security, enhanced throughput, and cost-effective operations. The contract functions as a public database, enabling users to conveniently track their public rating points, portfolios, experience, and activity.
Deployed Contract Address: 0xBEe4fde64e215A96a195FAca6226BE8107D4124c

  contract creation:  https://sepolia-blockscout.scroll.io/tx/0xb94eb12694ff715b3a0565ad8860971ec1bb3e04aa2f86b44ab1b526ad013784


- Our application is now operational on the Mantle network, offering expedited transactions, heightened security, enhanced throughput, and cost-effective operations. The contract functions as a public database, enabling users to conveniently track their public rating points, portfolios, experience, and activity.
Deployed Contract Address: 0x127cbf19A44E9ED1C2D5E9Ed1d90F38bC8e976c8
Cotract creation:
https://explorer.testnet.mantle.xyz/tx/0x4ba5b0f6775c8288003a81ea51bb5aabf15ff18840e3b909a4b46df02dd104cb
https://twitter.com/byBetoNY/status/1716115712287092839

# User Stories:
- allow frelancers to createToken maxSupply 1000
- allow companies to buy tokens
    function buyTokens(amount) {}
- allow companies to sale tokens

## User Story Frelancer:
 - Frelancer Joe comes & creates a maxSupply of 1000 (only for Joe)
 - The contract holds & makes them public for companies to buy/sell them
      JoesContractSupply = 1000 -10
      JoesContractSupply = 990

## User Story Companiies:
 - Company A  comes & buys 100 Joes' tokens
    CompanyA holds 10 joes tokens
- 2 Users
    - Developer user
          - should be able to:
                - able to login
                - create a profile w protfolio, skills,
    - Hiring manager user
        - message(xmtp) requires token x amount to contact user(buy tokens)

### Github: https://github.com/metaversemoon/skill-link








