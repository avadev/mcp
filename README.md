
## Avalara MCP Servers

[MCP (Model Context Protocol)](https://modelcontextprotocol.io/docs/getting-started/intro) is an open-source standard for connecting AI applications to external systems. 

Avalara provides managed MCP servers that give you instant access to our tax data, compliance tools, and business intelligence through your favorite AI clients. Connect seamlessly using OAuth 2.1 authentication on supported tools like Claude, Cursor, VS Code, or any other MCP-compatible client.

### What you can do:

* Query real-time tax rates and calculations
* Access compliance monitoring and regulatory updates
* Retrieve documentation and guidance


## Before you start

### Prerequisites

Before connecting to Avalara MCP servers, ensure you have:

* **Active Avalara subscription** - Your account must be in good standing
* **AI client installed** - Choose from Claude, Cursor, VS Code, or other MCP-compatible clients
* **Modern web browser** - Required for OAuth 2.1 authorization flow

## Security & Data Protection

**Security is fundamental to Avalara:**

    🔒 End-to-end encryption - All traffic encrypted via HTTPS/TLS 1.3
    �� OAuth 2.1 authentication - Industry-standard secure access control
    ⚡ Dynamic Client Registration - Seamless integration with MCP clients
    👤 Permission-based access - Data access respects your account permissions and roles

## Available Servers

Start with Avalara API MCP Server for general interactions, then add Avalara Knowledge MCP Server for docs and guidance.

| Server                                                                                                             | Description                                                                                                                                                                                                                             | Install                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|:-------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Avalara 1099 MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-ava1099-mcp-server/)         | Provides comprehensive access to 1099 tax form management, W9 form processing, issuer management, and compliance data.                                                                                                                  | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [AvaTax MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avatax/)                                   | This server provides comprehensive access to tax calculations, transaction management, nexus handling, and compliance data.                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara Cross Boarder MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/cross-border/)              | Enterprise MCP server providing AI-powered cross-border trade tools for product classification, duty calculation, and trade restrictions checking.                                                                                      | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [E-Invoicing MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/E-Invoicing/)                         | MCP server providing AI agents access to Avalara's global e-invoicing and live reporting APIs for retrieving document statuses, downloading legal/compliant documents, and enabling seamless compliance across jurisdictions worldwide. | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Exemption Certifications MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/exemption-certificates/) | MCP server providing AI agents access to Avalara's exemption certificate management APIs for retrieving certificates, customers, and companies.                                                                                         | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Managed Returns MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/managed-returns/)                 | This server provides comprehensive access to tax returns management, filing calendars, and compliance data.                                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Ava Tax Content MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-tax-content/)             | Provides Avalra Tax Content                                                                                                                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Business Licensing MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/business_licensing/)           | Enable your AI agents to access business license and permit requirements across multiple jurisdictions through this comprehensive MCP server.                                                                                           | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |


  






-----

## How to Connect

### Step 1: Install the Server

Choose your preferred method:

* One-click installation: Use the installation buttons above for Cursor and VS Code
* Manual installation: See detailed installation instructions for other clients in specific server pages

### Step 2: Authorize Access

* **Your MCP client** will redirect you to Avalara's secure login page
* **Sign in** with your Avalara credentials
* **Review permissions** - the client will request access to specific MCP server capabilities
* **Grant consent** - to complete the OAuth flow

### Step 3: Start Using

* **Cursor/VS Code**: Restart your editor or manually activate the server
* **Claude Desktop**: Connection is available immediately after authorization
* **Other clients**: Follow your client's specific activation instructions

## Troubleshooting
* Connection failed: Verify your Avalara account status and internet connection
* Permission denied: Check that your account has access to the requested services
* HTTP 429 (Too Many Requests): You've exceeded the rate limit for this server
  * Wait a few minutes before retrying
  * Check the server's rate limit details on its individual page
