
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

| Server                                                                                                                   | Description                                                                                                                                                                                                                             | Install                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|:-------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Avalara 1099 MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-ava1099-mcp-server/)               | Provides comprehensive access to 1099 tax form management, W9 form processing, issuer management, and compliance data.                                                                                                                  | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-ava1099-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9hdmExMDk5LyJ9" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-ava1099-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Fava1099%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                                                 
| [Avalara AvaTax MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avatax/)                                 | This server provides comprehensive access to tax calculations, transaction management, nexus handling, and compliance data.                                                                                                             | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-avatax-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9hdmF0YXgvIn0=" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-avatax-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Favatax%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                                                     |
| [Avalara Cross Border MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/cross-border/)                     | Enterprise MCP server providing AI-powered cross-border trade tools for product classification, duty calculation, and trade restrictions checking.                                                                                      | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-cross-border-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9jcm9zcy1ib3JkZXIvIn0=" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-cross-border-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Fcross-border%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                           |
| [Avalara E-Invoicing & Live Reporting MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/E-Invoicing/)      | MCP server providing AI agents access to Avalara's global e-invoicing and live reporting APIs for retrieving document statuses, downloading legal/compliant documents, and enabling seamless compliance across jurisdictions worldwide. | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-e-invoicing-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9lLWludm9pY2luZy8ifQ==" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-e-invoicing-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Fe-invoicing%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                             |
| [Avalara Exemption Certificates MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/exemption-certificates/) | MCP server providing AI agents access to Avalara's exemption certificate management APIs for retrieving certificates, customers, and companies.                                                                                         | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-exemption-certificates-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9leGVtcHRpb24tY2VydGlmaWNhdGVzLyJ9" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-exemption-certificates-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Fexemption-certificates%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a> |
| [Avalara Returns MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/managed-returns/)                       | This server provides comprehensive access to tax returns management, filing calendars, and compliance data.                                                                                                                             | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-returns-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9yZXR1cm5zLyJ9" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-returns-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Freturns%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                                                  |
| [Ava Tax Content MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/avalara-tax-content/)                   | Provides Avalara Tax Content                                                                                                                                                                                                            | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-avatax-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9hdmF0YXgvIn0=" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-avatax-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Favatax%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                                                     |
| [Avalara Business Licensing MCP Server](https://devtest.developer.ci.avalara.io/mcp-servers/business_licensing/)         | Enable your AI agents to access business license and permit requirements across multiple jurisdictions through this comprehensive MCP server.                                                                                           | <a href="cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-bl-mcp-server&amp;config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9ibC8ifQ==" class="inline-block mb-4"><img src="https://img.shields.io/badge/Add_to-Cursor-blue?style=for-the-badge" alt="Add to Cursor"></a> <a href="https://insiders.vscode.dev/redirect?url=vscode:mcp/install?%7B%22type%22%3A%22http%22%2C%22name%22%3A%22avalara-bl-mcp-server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.avalara.com%2Fbl%2F%22%7D" class="inline-block mb-4"><img src="https://img.shields.io/badge/Install_on-VS_Code-555555?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=555555&color=FF9900" alt="Install in VS Code"></a>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |


  






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
