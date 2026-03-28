# BooleanStorage.sol
How to deploy a contract on Base Chain BooleanStorage.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BooleanStorage {
    bool public status;

    function toggle() public {
        status = !status;
    }
}
