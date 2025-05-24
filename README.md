# SuiNova

SuiNova is a comprehensive no-code blockchain development ecosystem built on the SUI blockchain by Varmeta. It provides tools and infrastructure for NFT creation, marketplace operations, and blockchain-based applications, allowing users to easily create and deploy blockchain applications without coding experience.

## Overview

SuiNova is a product of Varmeta that provides a no-code platform for users to create blockchain applications such as marketplaces and launchpads. It allows users to build and publish web applications to Walrus, a decentralized storage platform.

SuiNova consists of several integrated components that work together to provide a complete solution for blockchain development and NFT operations:

- **SuiNova Builder**: A visual builder based on Plasmic technology that enables rapid development of web applications and websites with drag-and-drop functionality
- **SuiNova Component Store**: A Next.js application with UI components for blockchain applications
- **SuiNova Indexer**: A NestJS-based indexer for the SUI blockchain that processes and indexes blockchain data
- **SuiNova Smart Contracts**: SUI Move smart contracts that implement NFT marketplace and launchpad functionality
- **SuiNova Walrus Sites Provenance**: Additional tooling for blockchain site provenance

## Components

### SuiNova Builder

The Builder is based on Plasmic, an open-source visual builder for web applications. It enables:

- Rapid design and development of applications and websites with drag-and-drop functionality
- Integration with codebases to use existing React components
- Creation of rich stateful interactions and behaviors
- Connection with arbitrary data sources and backend integrations
- Powerful abstractions like components, variants, and slots

### SuiNova Component Store

A Next.js application that provides:

- UI components for blockchain applications
- Integration with Sui blockchain via @mysten/dapp-kit and @mysten/sui
- Modern UI built with Radix UI and Tailwind CSS

### SuiNova Indexer

A NestJS-based indexer for the SUI blockchain that:

- Processes and indexes blockchain data
- Provides APIs for querying indexed data
- Uses TypeORM for database operations
- Implements job queues with BullMQ
- Supports Kafka for event streaming

### SuiNova Smart Contracts

SUI Move smart contracts that implement:

#### Marketplace Module
- Handles operations related to NFT marketplace
- Supports listing, delisting, editing asks, and buying NFTs
- Manages marketplace fees and transactions

#### Launchpad Module
- Manages launchpad functionalities for NFT projects
- Supports token presales, minting NFTs, buying NFTs
- Handles different sale phases (presale, public sale)
- Provides fund redemption for project owners

## Getting Started

Each component has its own setup and development process. Please refer to the README files in each component directory for specific instructions:

- [SuiNova Builder](/suinova-builder/README.md)
- [SuiNova Component Store](/suinova-component-store)
- [SuiNova Indexer](/suinova-indexer)
- [SuiNova Smart Contracts](/suinova-smartcontract/README.md)

## Walrus Integration

SuiNova seamlessly integrates with Walrus, a decentralized storage platform. This integration allows users to:

- Publish their web applications directly to the decentralized web
- Ensure content permanence and censorship resistance
- Benefit from decentralized hosting without technical complexity
- Maintain ownership and control of their digital assets

The Walrus integration is a key feature that differentiates SuiNova from other no-code platforms, providing true decentralization for blockchain applications.

## Tech Stack

SuiNova leverages a modern tech stack to deliver its no-code blockchain development capabilities:

### Frontend
- **React/Next.js**: For building responsive and performant user interfaces
- **Tailwind CSS**: For streamlined styling and consistent design
- **Radix UI**: For accessible and customizable UI components
- **Plasmic**: For the visual builder functionality

### Blockchain
- **SUI Blockchain**: The underlying blockchain platform
- **SUI Move**: Smart contract language for secure and efficient contracts
- **@mysten/dapp-kit**: For blockchain integration in web applications
- **@mysten/sui**: Core SUI blockchain interaction library

### Backend
- **NestJS**: For robust API development and backend services
- **TypeORM**: For database interactions and data modeling
- **BullMQ**: For job queue management
- **Kafka**: For event streaming and real-time data processing

### Storage
- **Walrus**: Decentralized storage platform for web application hosting

## Future Developments

SuiNova is continuously evolving, with plans to add more templates and features in the future. Stay tuned for updates that will expand the capabilities of this no-code blockchain development platform.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
