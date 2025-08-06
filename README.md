# PayTroix - Web3 Payroll Management System

PayTroix is a modern web3-based payroll management system built on the Morph Holesky network, enabling organizations to manage employee payroll, leave requests, and salary advances in a decentralized manner.

## Features

- **Web3 Wallet Integration**: Secure authentication using blockchain wallets
- **Employee Management**: Add and manage employees with their wallet addresses
- **Payroll Processing**: Process payroll using stable tokens on the Morph Holesky network
- **Leave Management**: Handle employee leave requests and approvals
- **Salary Advance**: Process and track salary advance requests
- **Role-based Access**: Separate interfaces for organizations and recipients
- **Real-time Balance Tracking**: Monitor token balances and transaction history
- **Dashboard Analytics**: View employee statistics and payroll metrics

## Technology Stack

- **Frontend**: Next.js 13+ with App Router
- **Blockchain**: Morph Holesky Network
- **Authentication**: Appkit - Web3 Wallet-based auth
- **Styling**: Tailwind CSS
- **State Management**: React Hooks
- **Web3 Integration**: ethers.js, AppKit

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Network Configuration

PayTroix is configured to work exclusively with the Morph Holesky network:

- **Chain ID**: 2810 (0xafa)
- **RPC URL**: https://rpc-holesky.morphl2.io
- **Block Explorer**: https://explorer-holesky.morphl2.io

## Stable Tokens

The following stable tokens are available on the network for testing:

- USDT Contract Address: `0x562368917B2D3337d4613749cA989dd7A62eb1c8`

### Getting Test Tokens

1. Visit the Morph Holesky Explorer
2. Connect your wallet
3. Navigate to the token contract addresses
4. Use the faucet to claim test tokens

Note: These tokens are for testing purposes only and have no real value.

## Learn More

For more information about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Morph L2 Documentation](https://docs.morphl2.io/)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [ethers.js Documentation](https://docs.ethers.org/v6/)

## Project Structure

```
src/
  ├── app/                 # Next.js pages using App Router
  ├── components/          # React components
  │   ├── dashboard/      # Dashboard-specific components
  │   ├── landingPage/   # Landing page components
  │   └── shared/        # Shared/reusable components
  ├── config/             # Configuration files
  ├── context/            # React context providers
  ├── hooks/              # Custom React hooks
  ├── services/           # API and blockchain services
  ├── types/              # TypeScript type definitions
  └── utils/              # Utility functions
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
