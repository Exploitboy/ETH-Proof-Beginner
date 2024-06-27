# ETH-Proof-Beginner

# Old Coin (OC) Token Smart Contract
<p>This Solidity smart contract implements the Old Coin (OC) token as an ERC-20 standard token on the Ethereum blockchain.</p>

# Token Details
  Token Name: Old Coin<br>
  Token Symbol: OC<br>
  Initial Total Supply: 0<br>


# Getting Started
<strong> Deploy Contract:</strong> Deploy the MyToken contract on an Ethereum-compatible blockchain network.
<strong>Mint Tokens:</strong> Use the mint function to create new tokens and assign them to addresses.
<bold>Burn Tokens:</bold> Use the burn function to destroy tokens from addresses.
'''
pragma solidity 0.8.26;

contract MyToken {
    // Public variables to store token details
    string public tokenName = "Dark Coin";
    string public tokenAbbrv = "DC";
    uint public totalSupply = 0;
  '''
# Contract Functions
  mint(address to_address, uint to_value)
  -This function creates new tokens and assigns them to the specified address.
  <ul>
    <li>Parameters</li>
   <li> to_address: The address to which the new tokens will be assigned.</li>
    <li>to_value: The amount of tokens to be created and assigned.</li>
   </ul>
    
 # burn(address from_address, uint remove_value)
  -This function destroys tokens from the specified address.
  Parameters:
    from_address: The address from which tokens will be burned.
    remove_value: The amount of tokens to be destroyed.
  # Executing program
  To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:



To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "HelloWorld" contract in the left-hand sidebar, and then click on the "sayHello" function. Finally, click on the "transact" button to execute the function and retrieve the "Hello World!" message.

    

