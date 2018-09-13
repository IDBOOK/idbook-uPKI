# idbook-uPKI
IDBOOK uPKI
Before the internet, the majority of identities only existed in the real world, but now they must coexist with the digital world. In order to solve the problem of mapping various identity certificates from the real world to the digital world, the first step is to solve the mapping of authentication institutions in the digital world. Through using a PKI (Public Key Infrastructure) identification system that is used in existing web services, IDBook will develop a system of decentralized credit (uPKI), with qualified and certified nodes extending its authority from the real world to the digital world.

The transaction signature will be checked when the whole network synchronizes the billing unit. If the signature comes from an organization without a CA certificate, the transaction will be rejected.

The election of witness nodes
(1) The communities initiate voting with an airdrop, and wallets with airdrops can vote for witness nodes.
(2) For the elected witness nodes, the foundation will encrypt the public-key of the witness nodes with the private key of the authorized accounts, and preserve the authorized signature. The validation method will be using the public key of the authorized account to decrypt the authorized signature/public key of the witness nodes.
(3) The issuing institution needs to host a certain amount of IDB for the foundation account for unlocking, so as to obtain the candidate qualification, then IDB of the unselected node will be unlocked.
(4) witness nodes are also responsible for ordering the DAG consensus, authenticating the organizations as well as certifying the name and ID numbers of citizens.

The verification of personal identity and institutions will be processed offline, including the verification of company names, institution numbers, bank accounts, names, id numbers, etc. The witness nodes have the obligation to ensure the specification of organization verification. In the case of irregularities, the foundation can use the authorized accounts to cancel the signature for the node. Those cancelled witness nodes will lose the ability to verify institutions. The verification fee can be free of charge at the discretion of the issuing party.
All institutions will be valid for one year after being authenticated and shall be re-authenticated every year. The authenticated institutions will not be affected even if the verification nodes were canceled. The verified institutions can verify "miners", and only after the "miners" are verified can they conduct exchanging mining.
The effective verification methods for "miners" are the verification of institutions, ID card number, and the consistency of the ID card number and institutions registered ID information.


The institutions deploy the nodes and set the nations. The institutional nodes submit application materials through a DApp on the chain and are randomly qualified by the license issuing party. The verification is required to finish within one day. Verification overtime will be considered as a waiver and will be automatically transferred to other license issuing parties. The DApp randomly selects 3 issuing nodes in the issuing node pool to participate in the verification. The license issuing nodes will participate in validation voting, with part of the IDB as guarantee of the vote. The organization of the license issuing nodes independently verify the identity of the institutional nodes and decide whether to confirm the verification independently.
The voting mechanism follows the most effective principle. Once the results of the vote are the same as the opening of the ballot box, the foundation will unlock and reward the IDB. If inconsistent, the guaranteed IDB will be confiscated. The mechanism will ensure the license issuing nodes are loyal to performing its verification responsibilities, because they cannot predict the verification of the other issuing nodes. Only through the authenticity of the results can they safeguard their own rights and interests. If any issuing nodes has any objection to the final result, they may refer it to the foundation for arbitration.
According to the rules, if the institution passes the verification successfully, the verification will be recorded to the blockchain through the transaction, and everyone can query it.


