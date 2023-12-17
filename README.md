# erc6551-hardhat-starter
A starter for projects looking to build ERC6551 applications using Hardhat.

### Install Dependencies

`npm i`

### Compile Contracts

`npx hardhat compile`

### Run Tests

```sh
npx hardhat test
npx hardhat test test/filename.test.ts
npx hardhat coverage
npx hardhat coverage --testfiles test/filename.test.ts
```

### Deployment and Executing Scripts

`npx hardhat run scripts/ethereum/deploy.ts --network ethereum`
