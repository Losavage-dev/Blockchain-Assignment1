# Smart Contract Assignment

## Title

### Blockchain Technologies Assignment 1

## Usage

1. **Write a Smart Contract**:
   - The contract can receive Ether tokens.
   - The owner can withdraw all Ether in the contract.
   - Includes a function to check the balance.

2. **Configure the Environment**:
   - Use `web3.js` library.
   - Integrate with Ganache or a Public Testnet.

3. **Deploy and Test**:
   - Configure Metamask.
   - Deploy the contract and test functionalities.

## Demo Screenshots

- **Deployment Process**:



  Code:![Code](https://github.com/user-attachments/assets/ca80debc-7cd8-44a7-9ace-08aa0088db3f)
  
  ![image](https://github.com/user-attachments/assets/cc96aeda-e49e-4853-8da6-04d951a54063)
  
  ![image](https://github.com/user-attachments/assets/d755a2ff-e2f1-44a8-9b69-2e48b976661c)



- **Function Calls**:
  ![Function Call Screenshot](demo/functions.png)
  ![image](https://github.com/user-attachments/assets/6337f894-2a0f-4517-89ac-e3b846176c49)
  ![image](https://github.com/user-attachments/assets/0cb657f5-a505-46ba-8db1-0e9be15e5cfb)


## Examples

- **Check Balance**:
  ```js
  const balance = await contract.methods.getBalance().call();
  console.log(`Contract Balance: ${balance} Ether`);
  ```

- **Withdraw Funds**:
  ```js
  await contract.methods.withdraw().send({ from: ownerAddress });
  ```

## License

[OpenZeppelin License Example](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/LICENSE)
