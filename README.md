# BlockNumber.sol
BlockNumber.sol
pragma solidity ^0.8.20;
contract BlockNumber {
    function getBlock() public view returns(uint){
        return block.number;
    }
}
