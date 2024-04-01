# Week-3-Encode
## Homework Week 3

Gautam Raj @nooberboy 

SeeragU @rag791

Hrithik Edward Sampson @hrithik9619 

## Short summary
A smart contract deployed on Sepolia testnet for users to cast votes on Number: 
- 0 0x0000000000000000000000000000000000000000000000000000000000000001 
- 1 0x0000000000000000000000000000000000000000000000000000000000000002
- 2 0x0000000000000000000000000000000000000000000000000000000000000003
- Block Number: 5608609

## Project purpose
Smart Contract knowledge to Deploy, Delegate and cast votes.

## Transaction details
1. Create Contract

  MyToken.sol:
    
    Contract address: 0x2c14f5e9e0fe99af55c97b5fcbc3d61fdb5f4115
    Transaction hash: 0xc676c2534c52e67dae315b7d34200c063d79ad51875a7f2abeabe357415a7d85 
    Status: success
  
  TokenizedBallot.sol:
  
    Contract address: 0x6b1c724df21165d8107030fee46ae343fd98654d
    Transaction hash: 0x23b75bc39115c47b3985b8bbdff35288b99a5d5a5f4005b1d51f9981ba894bdc  
    Status: success

2. Give right to vote
  ``` 
    Add voter 0xf989CA835FE863907E0CCce67dD4E08ac6Dd7E5f
    Transaction hash: 0x1397516545fe830976b636fd8cae9284816e0bfdaf81f85b536b2b33b9cffe24
    Status: success
    
    Add voter 0xD6e0613A2cAEa9227e6E7eB2Bbe56F6E99EC08bb
    Transaction hash: 0x765ea07ae83ff905f268f06fcdf9e58599fd7317dca3890984158430705d83d4
    Status: success
    
    Add voter 0x445e82fbc39897Db65e80A198742Bb175a6D5E0E
    Transaction hash: 0xad43147dd90b1b064abb5802456cd9926a0bc7eb7ef2724fd13caa5f0b2e9893
    Status: success
  ```

3. Vote
  ```
    Voter 0x6b1c724dF21165d8107030FeE46Ae343Fd98654D
    Transaction hash: 0x727d1eee199c4b562f5ce6b762ba4d1d921d26fe13bd24bdcf606a35e6d542c9
    Status: success
  ```

5. Vote count for proposals
  ```
    Proposal 1 0x0000000000000000000000000000000000000000000000000000000000000002 has 10 votes so far.
  ```

7. Delegate vote
  ```
    Voter 0xDb1d125C9f7faE45d7CeE470d048670a85270f4D delegates to 0x996A5ed069A393F0b25A08f3212F619D801bA110
    Transaction hash: 0xce54c5036aea143e9b50e4eae53598f267a21ff976ed8269256dd1877d8eb2d1
    Status: succeed
  ```

9. Winning proposal
The winner is: 0x0000000000000000000000000000000000000000000000000000000000000002
