# Ethereum_Evoting
Smart Contract based voting system which let voters elect candidates in an election. This is the upcoming way of casting vote where all votes will be stored in the blockchain, which makes the system tamper proof and fully transparent. Voting tokens are issued to everybody who is eligible to vote and let them vote. Technology Stack - Solidity, Truffle, Ganache, NodeJs, Bootstrap.

# How to use our application 
1. Install MetaMask browser extension.
2. Make sure that the Ethereum account which you've been assigned is imported into MetaMask.
3. Visit cast vote page and caste your vote.

# How to use in your local machine
1. Install truffle 
npm install -g truffle

2. Install Ganache and metamask from web browser after installing set it up.

3. Clone the gitHub repository 
git clone "https://github.com/FABhishek/Ethereum_Evoting"

4. Now open the project in your vs code and open ganache also side by side 

5. Now open terminal in your vs code and run this command 
truffle migrate --reset (this command will upload the smart contract from your local ethereum network to blockchain.

6. Finally run npm run dev command and you're good to go.

# Steps to cast vote:-
### first of all, set up a truffle and link the network with your metamask usging ganache.
![image](https://user-images.githubusercontent.com/52832978/153744531-63b10f2c-6df8-4dd1-81fa-0f9c0d14a009.png)

### List of candidates, you can choose anyone to vote
![image](https://user-images.githubusercontent.com/52832978/153744441-98d4ea23-47bc-46d3-881e-3fd476414881.png)

### click on vote and it will open metamask to vote, then confirm to cast vote successfully.
![image](https://user-images.githubusercontent.com/52832978/153744461-d2b50b9d-9ac5-499d-badc-ea5f58c327bf.png)

### It will show "You've already voted" after successful casting and won't let to caste the vote again using the same ID.
![image](https://user-images.githubusercontent.com/52832978/153744473-6cbe577e-4111-410c-bf5a-87bd2e5be478.png)

### Finally a generated QR code with proper feedback.
![image](https://user-images.githubusercontent.com/52832978/153744507-f0aa230f-3b24-4956-b186-f0c73d222746.png)
 
<img src="https://c.tenor.com/IAUvvrUY7zQAAAAC/done-spongebob.gif" width="290" height="250" />

