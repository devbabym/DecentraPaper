# DecentraPaper

DecentraPaper is a decentralized system for managing academic publications using Clarity smart contracts on the Stacks blockchain. It ensures secure storage, immutability, and transparent access control for scientific papers.

## Features

- **Register Publications**: Authors can register academic publications with metadata such as title, summary, and tags.
- **Modify Publications**: Authors can update the details of their registered publications.
- **Remove Publications**: Authors can delete their publications if necessary.
- **Ownership Transfer**: Publications can be transferred to another author.
- **Permission Management**: Authors can control access permissions for specific viewers.

## Smart Contract Overview

The core functionality is implemented using Clarity smart contracts, ensuring security, transparency, and decentralization.

### Error Codes

| Code  | Description |
|-------|------------|
| `u300` | Owner action required |
| `u301` | Publication not found |
| `u302` | Publication already exists |
| `u303` | Invalid publication data |
| `u304` | Publication exceeds allowed size |
| `u305` | Unauthorized action |

### Storage Structures

- **Publication Registry**: Stores metadata such as title, creator, byte count, timestamp, summary, and tags.
- **Viewer Permissions**: Manages access control for specific viewers.

### Public Functions

#### `register-publication`
Registers a new scientific publication.

#### `remove-publication`
Deletes a registered publication.

#### `modify-publication`
Updates the metadata of an existing publication.

#### `transfer-publication`
Transfers ownership of a publication to another user.

## Getting Started

### Prerequisites

- [Clarity CLI](https://docs.stacks.co/docs/clarity-cli)
- [Stacks Blockchain](https://www.stacks.co/)
- A local or testnet environment for deploying smart contracts.

### Deployment

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/decentrapaper.git
   cd decentrapaper
   ```
2. Deploy the contract using Clarity CLI:
   ```sh
   clarity-cli launch --contract decentrapaper.clar
   ```
3. Interact with the contract using Clarity REPL.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
```

Would you like any modifications or additional details? 🚀