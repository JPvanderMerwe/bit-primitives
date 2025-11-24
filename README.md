# bit-primitives
Bit Primitives Collective

<img width="1563" height="1563" alt="bp_1563_full" src="https://github.com/user-attachments/assets/b700c895-fb63-45d5-9eef-5f554bb60e7a" />


To come:  project description, setup instructions, and contribution guidelines
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.2; // safe

// A simple ERC20-like token with a few classic 0.8 features
contract MyToken {
    string public constant name = "MyToken";
    string public constant symbol = "MTK";
    uint8 public constant decimals = 18;
    uint256 public totalSupply;
}
