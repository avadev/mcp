
## Avalara MCP Servers

[MCP (Model Context Protocol)](https://modelcontextprotocol.io/docs/getting-started/intro)  servers provide a standardized way to connect AI applications with Avalara's tax compliance systems. MCP servers let partners and developers integrate AI-driven tax workflows, automate cross-border compliance, and easily plug into Avalara's regularly updated tax content.
Currently, Avalara-supported MCP servers include AvaTax, Managed Returns, and E-Invoicing and Live Reporting. We’ll keep adding more services over time.

### What you can do:

* Query real-time tax rates and calculations
* Access compliance monitoring and regulatory updates
* Retrieve documentation and guidance


## Getting Started with Avalara MCP Servers

Learn how to set up and connect to Avalara Model Context Protocol (MCP) servers for AI-powered tax compliance integration.

### Prerequisites

To connect to Avalara MCP servers, you need to have:
* An active Avalara subscription - Your account must be in good standing
* AI client installed - Select from Claude, Cursor, VS Code, or other MCP-compatible clients
* A modern web browser - Required for OAuth 2.1 authorization flow.



### How to connect:

**Step 1: Install the server**    

Select your preferred method  
* **One-click installation**: Use installation buttons available on individual MCP server pages
* **Manual installation**: Follow the configuration steps for your specific MCP client

**Step 2: Authorize the access**     
* **Your MCP client** will redirect you to Avalara's secure sign in page
* **Sign in** with your Avalara credentials
* **Review permissions** - the client will request access to specific MCP server capabilities
* **Grant consent** to complete the OAuth flow  

**Step 3: Start using**

* **Cursor or VS Code**: Restart your editor or manually activate the server
* **Claude Desktop**: Connection is available immediately after authorization
* **Other clients**: Follow your client's specific activation instructions.

## Available Servers

Start with Avalara API MCP Server for general interactions, then add Avalara Knowledge MCP Server for docs and guidance.

| Server                                                                                                                   | Description                                                                                                                                                                                                                             | Install                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|:-------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Avalara 1099 MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-ava1099-mcp-server/)               | Provides comprehensive access to 1099 tax form management, W9 form processing, issuer management, and compliance data.                                                                                                                  | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara AvaTax MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avatax/)                                 | This server provides comprehensive access to tax calculations, transaction management, nexus handling, and compliance data.                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara Cross Border MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/cross-border/)                     | Enterprise MCP server providing AI-powered cross-border trade tools for product classification, duty calculation, and trade restrictions checking.                                                                                      | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara E-Invoicing & Live Reporting MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/E-Invoicing/)      | MCP server providing AI agents access to Avalara's global e-invoicing and live reporting APIs for retrieving document statuses, downloading legal/compliant documents, and enabling seamless compliance across jurisdictions worldwide. | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara Exemption Certificates MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/exemption-certificates/) | MCP server providing AI agents access to Avalara's exemption certificate management APIs for retrieving certificates, customers, and companies.                                                                                         | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara Returns MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/managed-returns/)                       | This server provides comprehensive access to tax returns management, filing calendars, and compliance data.                                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Ava Tax Content MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-tax-content/)                   | Provides Avalra Tax Content                                                                                                                                                                                                             | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |
| [Avalara Business Licensing MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/business_licensing/)         | Enable your AI agents to access business license and permit requirements across multiple jurisdictions through this comprehensive MCP server.                                                                                           | [![Install in VS Code](https://img.shields.io/badge/VS%20Code-Install%20MCP-007ACC?logo=visualstudiocode&logoColor=white)](vscode:mcp/install?name=avalara.knowledge-mcp&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.example.com%2Fmcp%22%7D)[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20MCP-000000?logo=cursor&logoColor=white)](cursor://mcp/install?name=avalara.knowledge-mcp&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmV4YW1wbGUuY29tL21jcCJ9) |


  






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
