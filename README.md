##SMART CONTRACT MANAGEMENT

## Description

This project demonstrates how to build a basic web application using React that interacts with a Solidity smart contract deployed on a local Ethereum blockchain. By integrating Metamask, users can set and retrieve values from the smart contract through the React frontend. This setup provides a foundation for building decentralized applications (dApps) with blockchain functionality.

## Getting Started

### Installing

1. **Clone the Repository:**


2. **Set Up the Backend:**



3. **Set Up the Frontend:**



### Executing the Program

1. **Start the Local Ethereum Node:**

    Open a terminal, navigate to the `backend` directory, and run:

    ```bash
    npx hardhat node
    ```

2. **Deploy the Smart Contract:**

    In a new terminal window, still in the `backend` directory, run:

    ```bash
    npx hardhat run --network localhost scripts/deploy.js
    ```

    This will deploy the smart contract to your local Ethereum node.

3. **Start the React Application:**

    In another terminal window, navigate to the `frontend` directory and start the React development server:

    ```bash
    cd frontend
    npm start
    ```

    Your application will be available at `http://localhost:3000`.

### Metamask Integration

1. **Install Metamask:**

    Download and install the Metamask extension for your browser from [Metamask.io](https://metamask.io/).

2. **Connect to Local Network:**

    - Open Metamask and go to the network dropdown.
    - Click on "Add Network" and enter the following details:
      - **Network Name:** Localhost 8545
      - **New RPC URL:** http://localhost:8545
      - **Chain ID:** 31337
      - **Currency Symbol:** ETH

    - Save and switch to this network.

3. **Interact with Your Application:**

    Metamask will prompt you to approve transactions when interacting with the smart contract through the React app.

## Help

**Common Issues:**

- **Problem:** `npm` or `npx` commands not recognized.
  - **Solution:** Ensure Node.js and npm are installed correctly. Restart your terminal or command prompt if necessary.


## Authors

- **Jiya Mittal**
## License

This project is licensed under the MIT License 

