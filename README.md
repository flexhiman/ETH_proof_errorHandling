# Smart Contract Project

In this program, we write a smart contract that implements the require(), assert(), and revert() statements.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. In this program, we write a smart contract that implements the error-handling methods which are require(), assert(), and revert

### Executing program

```javascript
// SPDX-License-Identifier: MIT
 pragma solidity 0.8.7;

contract ErrorHandling{
    function MultiRequire(uint n,uint m) public pure{
        require( n*m<50, "The multipication of n and m is smaller than 50");
    }
    function MultiAssert (uint i) public pure{
        assert( i>=5 );
    }
    function MultiRevert (uint q,uint u) public pure{
        if( q*u>50){
            revert("The multipication of q and u is smaller than 50");
        }
    }
}
```
In this program, we implement the error-handling methods. We first make a contract named ErrorHandling and after that, a function named MultiRequire and after that take two unsigned integers n&m and pass the arguments.
After that, we make a function named MUltiAssert and take an unsigned integer i. And after that we pass the arguments.
After that, we make a function named MultiRevert and take two unsigned integer q&u and after that pass the arguments.

## Authors
Himanshu Singh
