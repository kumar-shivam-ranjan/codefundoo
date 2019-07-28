# codefundoo++
This repository desccribes the idea and implementation of using blockchain in elecions to make it more secure,transparent and reliable.


# Our main idea of using blockchain for e-voting is as follows:

First of all, the voter registration process would still have to take place off the grid or off the chain. Once a voter registration agency determines that someone is eligible to vote, they would receive a token or key that would allow them to vote exactly once. Any authentic candidate can login in using web-cam and government issued ID. ECC or Eleptical curve cryptography is used to create these votes. ECC is a form of assymetric cryptography that uses two public and private key to ecrypt and decrypt data. 

During Voter registration,the voter creates two ECC key pairs.The voter reveals their identity to verifier who certifies the first key pair. Once that's done, the voter registers their second key pair anonymously as belonging to their first pair. Then the voters cast their virtual ballot and signs up on the vote with the private key.

Once the vote is done,anyone can verify whether the signature is valid or not and make sure that none of the votes have been tampered with. All the votes can be verified by using voter's public key to see if the come from legitimate actor.
During the registration process,after the identity is verified, a smart contract will be executed that will issue a ballot so that he could vote and submit it to the ballot box. Blockchain based voting system will ensure that user doesn't vote multiple times.

In a blockchain based voting system,when a voter votes,the polling station consults a voter blockchain to ensure the voter hasn't already used up his vote.If the voter's vote is valid, the polling station accepts his vote and in case the vote is found to be invalid,the vote gets rejected by the polling station thus tackling the problem of multiple votes by a single person. After voting,the vote becomes a transaction and gets stored in blockchain after encryption. 
Once the vote is casted, it can't be modified because of the innate,immutable characteristics of the blockchain. The voter can even audit each ballot and confirm if the election results are accurate while retaining the privacy of other voters.
The privacy is maintained.

Well, a person’s identity is hidden via complex cryptography and represented only by their public address. So, if you were to look up a person’s transaction history, you will not see “Bob casted his vote to Mr. XYZ of ABC party” instead you will see “1MF1bhsFLkBzzz9vpFYEmvwT2TbyCt7NZJ casted his vote to Mr. XYZ of ABC party”.
The Blockchain is decentralised,dustributed public ledger system. Each block of a blockchain is given with a unique string obtained through hashing. Moreover,each block stores the hash of a previous block and hence it forms a chain.

# Technologies used:
*ECC


*SHA-256



