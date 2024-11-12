<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MediBlock</title>
</head>
<body>

  <h1>MediBlock</h1>
  <p>MediBlock is a decentralized platform designed to securely store and manage healthcare records using blockchain technology. The platform provides a transparent, secure, and immutable record-keeping system for healthcare data, empowering patients and healthcare providers to manage medical records with privacy and control.</p>

  <h2>Features</h2>
  <ul>
    <li><strong>Decentralized Medical Records</strong>: Medical records are stored on the blockchain, ensuring transparency, security, and control for both patients and providers.</li>
    <li><strong>Patient Control</strong>: Patients have full control over their medical data and can choose who has access to their records.</li>
    <li><strong>Secure Data Storage</strong>: Blockchain's immutability ensures that healthcare records cannot be tampered with or altered.</li>
    <li><strong>Healthcare Provider Integration</strong>: Healthcare providers can securely access and update patient records with proper authorization.</li>
    <li><strong>Smart Contract-Based Permissions</strong>: Smart contracts automate permissions and access to medical data based on patient consent.</li>
  </ul>

  <h2>Tech Stack</h2>
  <ul>
    <li><strong>Blockchain</strong>: Ethereum, Binance Smart Chain (or any EVM-compatible network)</li>
    <li><strong>Smart Contracts</strong>: Solidity</li>
    <li><strong>Frontend</strong>: React.js</li>
    <li><strong>Web3 Integration</strong>: Web3.js, Ethers.js</li>
    <li><strong>Backend</strong>: Node.js (optional for certain features)</li>
    <li><strong>Data Encryption</strong>: AES encryption for securing sensitive data before storing it on the blockchain.</li>
    <li><strong>Styling</strong>: Material-UI, CSS</li>
    <li><strong>Testing</strong>: Hardhat, Mocha</li>
  </ul>

  <h2>Installation</h2>
  <h3>Prerequisites</h3>
  <p>Ensure you have the following installed on your local machine:</p>
  <ul>
    <li>Node.js and npm</li>
    <li>Truffle or Hardhat (for smart contract deployment)</li>
    <li>MetaMask (or any Ethereum wallet) for interacting with the platform</li>
  </ul>

  <h3>1. Clone the Repository</h3>
  <pre><code>git clone https://github.com/ketanhustles/MediBlock.git
cd MediBlock</code></pre>

  <h3>2. Install Dependencies</h3>
  <pre><code>npm install</code></pre>

  <h3>3. Compile Smart Contracts</h3>
  <p>Using Hardhat (or Truffle):</p>
  <pre><code>npx hardhat compile</code></pre>

  <h3>4. Deploy Contracts</h3>
  <p>You can deploy the smart contracts to a local or test Ethereum network:</p>
  <pre><code>npx hardhat run scripts/deploy.js --network &lt;network-name&gt;</code></pre>
  <p>Replace &lt;network-name&gt; with the desired network (e.g., ropsten, sepolia, localhost).</p>

  <h3>5. Run the DApp</h3>
  <p>To run the frontend locally:</p>
  <pre><code>npm start</code></pre>
  <p>Access the app at <a href="http://localhost:3000">http://localhost:3000</a>.</p>

  <h2>Usage</h2>
  <ol>
    <li>Connect your Ethereum wallet (MetaMask or any compatible wallet) to the DApp.</li>
    <li>Patients can upload their medical records securely to the blockchain.</li>
    <li>Healthcare providers can view and update records with patient consent.</li>
    <li>Patients can manage access permissions, granting or revoking access to their records.</li>
  </ol>

  <h2>Contributing</h2>
  <ol>
    <li>Fork the repository.</li>
    <li>Create a feature branch 
