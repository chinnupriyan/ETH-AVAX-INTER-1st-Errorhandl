# OddEvenChecker Smart Contract

This Solidity smart contract provides functions to check whether a given number is odd or even. It also demonstrates the usage of `require`, `revert`, and assertion (`assert`) statements for condition validation within smart contracts.

## Functions

### `isEven(uint256 number)`

Checks if the provided number is even.

- **Parameters:**
  - `number`: Unsigned integer to be checked for evenness.

- **Returns:**
  - `bool`: `true` if the number is even, `false` otherwise.

### `isOdd(uint256 number)`

Checks if the provided number is odd.

- **Parameters:**
  - `number`: Unsigned integer to be checked for oddness.

- **Returns:**
  - `bool`: `true` if the number is odd, `false` otherwise.

### `checkEvenWithRevert(uint256 number)`

Demonstrates the use of `revert()` to handle conditions directly within the function.

- **Parameters:**
  - `number`: Unsigned integer to be checked for evenness.

- **Reverts:**
  - If `number` is not even, the function reverts the transaction with an error message.

## Usage

To interact with this contract, deploy it to an Ethereum-compatible environment such as Remix or Truffle. After deployment, call the functions to verify the odd/even status of different numbers.
