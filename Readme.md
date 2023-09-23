# Getting Started with Solidity

This is my 2nd project for metacrafters.

## Description

The 2nd project for metacrafters consists of these 5 steps:
1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. 
The function then increases the total supply by that number and increases the balance 
of the “sender” address by that amount
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
and from the balance of the “sender”.
5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
to the amount that is supposed to be burned.


Below is the skeleton code:
```
// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

/*
       REQUIREMENTS
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
*/

contract MyToken {

    // public variables here

    // mapping variable here

    // mint function

    // burn function

}

```

## Getting Started

### Installing

* You can download the MyToken.sol file by clicking on it, and then clicking the download button found at the top right corner of the text file. The download button is beside the copy raw file button.

### Executing program

* Visit https://remix.ethereum.org
* Upload MyToken.sol using the upload files button above the folder named contracts
* Compile MyToken.sol in the Solidity compiler tab located on the left side of the screen. It is beside the Search in files button
* Click Deploy and run transactions button located below the Solidity compiler button on the left side of the screen.
* Under Deploy and run transactions tab, select MyToken.solcas contract and click Deploy
* Under the section Deployed Contracts, expand MyToken.sol
* Expand the burn and mint functions
* Copy your account found at the top of the Deploy and run transactions tab. There is a copy button beside your account
* Paste your account to the _address fields of the burn and mint functions
* Paste your account on the balances variable

After executing these steps you will now be able to use the program. You can check your total supply by clicking on the total supply variable and expanding its call in the terminal.
You will be looking at the decoded output variable to see the value of the total supply variable.
You can mint and burn functions by placing an unsigned integer value as _value in the function and clicking the transact button.


## Help

Be sure to compile before deploying MyToken.sol </br>
Be sure to select MyToken.sol as the contract before deploying

## Authors

Alan Gabriel Limyu (limyualan@gmail.com)


## License

This project is licensed under the Alan Gabriel Limyu License - see the LICENSE.md file for details
