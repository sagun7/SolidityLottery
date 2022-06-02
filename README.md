# SolidityLottery
This is a lottery smart contract. It includes number of participants who want to take part in this game. In order to be member of this system, each one of them
has to pay 1 ether to the contract address. When contracts sees the participant/ address has paid 1 ether to the address, his address will be stored in the dynamic 
array of participants/ group of participants. There will be a "manager" who has the right to run getBalance() to find out what is the total ether, which has been collected
in the contract address. He also has right to run selectWinner(), which will randomly select the address from the participants. Finally, that selected participant will receive or 
whole contract balance will be transferred to the winner.
