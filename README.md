# Greeting.sol
Greeting.sol10
pragma solidity ^0.8.20;

contract Greeting {
    function sayHello() public pure returns (string memory) {
        return "Hello Blockchain!";
    }
}
Add simple storage contract
Add simple test case
Optimize function calls
