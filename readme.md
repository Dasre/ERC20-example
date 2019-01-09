ERC20 example
===

* Use Mytoken.sol

* ``` Solidity
    uint256 public constant INITIAL_SUPPLY = 10000 * (10 ** uint256(decimals()))
    ``` 
    Determine to mint how many token


* ``` Solidity
    constructor () public payable ERC20Detailed("TEE", "T", 18) {
        _mint(msg.sender, INITIAL_SUPPLY);
    }
    ```
    `Tee` is the token name.
    `T` is the symbol.
    `18` is the decimals.