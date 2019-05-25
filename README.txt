The Owner Contract is the Parent. The Raffle contract is inheriting from Owner 
to determine the owner of the contract and to make use of the modifier onlyOwner 
so that on the suspendRaffle function under the Raffle contract, this can only be
executed if the one calling the function is the owner of the contract.