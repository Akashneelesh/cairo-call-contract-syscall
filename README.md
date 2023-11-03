# Cairo Call Contract Syscall

This is an example that effectively addresses multiple scenarios. The primary focus is on passing the data to a function and forwarding it to the call_contract_syscall through the calldata. Additionally, the example explores various scenarios in which a receiving contract may need to be structured differently to handle the data, providing a comprehensive view of the topic.

What this particular syscall essentially does is the same low level call as we have in the EVM.

## Getting Started

These instructions will help you set up and deploy the project.

### Prerequisites

- [Node.js](https://nodejs.org/) and either [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [scarb 2.3.0-rc0](https://docs.swmansion.com/scarb/download.html)

### Installation

1. Clone the project repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install project dependencies:
   ```bash
   npm install or yarn
   ```

### Building the Project

To compile the project, run:
`bash
    scarb build
    `
This will generate the sierra and casm files in the target folder.

### Contract Deployment

This project includes deployment scripts for Sender and Receiver contracts.

To deploy the Sender contract, run:
`bash
    npx ts-node scripts/deployment_send.ts
    `

This will provide the contract address for interaction.

For deploying the Receiver contract, execute:
`bash
    npx ts-node scripts/deployment_receive.ts
    `

For more information, check out the contract files within the project directory.

### Additional Information

Explore the project's contracts and find more details and customization options.

### Contact

For questions or issues, please feel free to contact me through discord or telegram (@akashneelesh).

Enjoy using the project!
