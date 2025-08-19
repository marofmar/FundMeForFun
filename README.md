🔗 Web3 Integration:
  - Connects to MetaMask wallet
  - Automatically switches to zkSync Sepolia network
  - Real-time wallet connection status

  💰 Donation Functionality:
  - Enforces $1 USD minimum donation (converted to ETH)
  - Real-time ETH price estimation for USD conversion
  - Transaction processing with user feedback
  - Error handling for insufficient amounts

  📊 Dashboard Features:
  - Total funds raised display
  - User's personal contribution tracking
  - Minimum donation requirement display
  - Contract owner withdrawal functionality (if you're the owner)

  🎨 Modern UI/UX:
  - Responsive gradient design
  - Glass morphism effects
  - Mobile-friendly layout
  - Loading states and user feedback

  🚀 How to Use:

  1. Start the application:
  cd fundme-frontend
  npm start
  2. Connect MetaMask:
    - Make sure you have MetaMask installed
    - The app will guide you to connect and switch to zkSync Sepolia
  3. Make a donation:
    - Enter amount in ETH (minimum ~$1 USD worth)
    - Confirm transaction in MetaMask
    - See your contribution tracked on the dashboard
  4. Owner functions:
    - If you're the contract owner, you'll see a withdraw button

  📁 Project Structure:
  
  FundMe.sol
  fundme-frontend/
  ├── src/
  │   ├── components/FundMe.tsx & .css (Main UI)
  │   ├── hooks/useWeb3.ts (Wallet integration)
  │   ├── contract/config.ts (Contract details)
  │   ├── utils/contractUtils.ts (Helper functions)
  │   └── App.tsx (Main app)
