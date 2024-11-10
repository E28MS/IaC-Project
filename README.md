# IaC-Project
# Project Title

I am building an Infrastructure as Code App to deploy this on-prem infrastructure (add diagram) to the Cloud. 

I will use Bicep.  

## Table of Contents
- [Project Title](#project-title)
- [Table of Contents](#table-of-contents)
- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

My project can be used to transfer existing on premises infrastructure to the Cloud.

## Getting Started

Instructions on setting up your project locally.

### Prerequisites
To deploy infrastructure with Bicep, you need several tools and resources in place to ensure a smooth setup and deployment process. Here’s a list of prerequisites:

### 1. **Bicep CLI**
   - **Install the Bicep CLI**: This is the primary tool needed to compile Bicep files into ARM templates and deploy them to Azure.
     - You can install Bicep via the Azure CLI using:
       ```bash
       az bicep install
       ```
     - Alternatively, you can download and install the Bicep CLI manually from GitHub.
     - **Version compatibility**: Ensure the Bicep CLI version is compatible with the Azure CLI or PowerShell you’re using.

### 2. **Azure CLI**
   - **Install Azure CLI**: The Azure CLI is commonly used to deploy Bicep templates to Azure.
   - **Authenticate with Azure**: You’ll need to log in to Azure using:
     ```bash
     az login
     ```

### 3. **Azure PowerShell (Optional)**
   - If you prefer PowerShell over Azure CLI, install **Azure PowerShell** and authenticate using:
     ```powershell
     Connect-AzAccount
     ```

### 4. **Azure Subscription**
   - **Active Azure Subscription**: You need an Azure subscription to deploy resources, and the account should have Contributor or Owner permissions for the target resource group.

### 5. **VS Code or Another Code Editor (Recommended)**
   - **Install Visual Studio Code**: This is the recommended editor for Bicep as it has an extension for Bicep, which provides syntax highlighting, IntelliSense, and linting support.
   - **Bicep Extension**: Install the [Bicep extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep) to enhance development experience with additional features like autocompletion.

### 6. **Azure Resource Manager (ARM) Knowledge**
   - Although optional, familiarity with ARM templates and basic Azure Resource Manager concepts is beneficial, as Bicep compiles down to ARM templates.

### 7. **Git (Optional but Recommended)**
   - If working on a team or using version control, having Git installed helps you manage and collaborate on Bicep files.

### **Summary Checklist**
| Tool | Purpose |
| --- | --- |
| Bicep CLI | Compile and deploy Bicep files |
| Azure CLI or Azure PowerShell | Deploy Bicep templates to Azure |
| Azure Subscription | Access to deploy resources |
| VS Code + Bicep Extension | Recommended editor for Bicep development |
| Git (Optional) | Version control for Bicep templates |

By setting up these prerequisites, you'll be ready to start developing and deploying infrastructure using Bicep. 

### Installation

Step-by-step guide on how to install your project.

## Usage

Provide examples and instructions for how to use your project.

## Contributing

Explain how other developers can contribute to your project. Include guidelines for pull requests and code style.

## License

Specify the license under which your project is distributed.

## Contact

Include your name and email address for people to reach out to you with questions, feedback, or suggestions.
