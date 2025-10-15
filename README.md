
# <img src="A-Check.png" alt="A-Check" width="60"> Avalara

**This is a non-community repo, created and maintained by Avalara**
___

## Avalara MCP Servers


[MCP (Model Context Protocol)](https://modelcontextprotocol.io/docs/getting-started/intro)   servers connect AI applications with Avalara's tax compliance systems in a standardized way. MCP servers allow partners and developers to integrate AI-driven tax workflows, automate cross-border compliance, and access Avalara's regularly updated tax content.  
Avalara-supported MCP servers include AvaTax, Returns, E-Invoicing and Live Reporting, Tax Registrations and Business Licenses and Exemption Certificate Management. More services will be added over time.



### What you can do:

1. Query real-time tax rates and calculations
2. Access compliance monitoring and regulatory updates
3. Manage exemption certificates, business licenses, and returns
4. Retrieve documentation and guidance


## Getting Started with Avalara MCP Servers

Learn how to set up and connect to Avalara Model Context Protocol (MCP) servers for AI-powered tax compliance integration.

### Prerequisites

To connect to Avalara MCP servers, you need to have:
* **Avalara subscription**: You must have an active Avalara account
* **An AI client**: Programmatic clients built using FastMCP or any other MCP-compatible library.
* **A modern web browser**: Required for the OAuth 2.1 authorization flow.



### How to connect:

**Step 1: Set up the MCP client**  
Follow the steps provided on the individual MCP server pages.

**Step 2: Authorize access**     
* When prompted, your **MCP client** redirects you to Avalara's secure sign in page
* **Sign in** with your Avalara credentials
* **Review the permissions** requested by the client for access to specific MCP server capabilities
* **Grant consent** to complete the OAuth flow  

## Available Servers


| Server | Description | Install |
|:-------|:------------|:--------|
| [Avalara AvaTax MCP Server](https://developer.avalara.com/mcp-servers/avatax/) | This server provides comprehensive access to tax calculations, transaction management, nexus handling, and compliance data. | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-avatax-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9hdmF0YXgifQ==) |
| [Avalara Returns MCP Server](https://developer.avalara.com/mcp-servers/managed-returns/) | This server provides comprehensive access to tax returns management, filing calendars, and compliance data. | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-returns-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9yZXR1cm5zIn0=) |
| [Avalara Tax Registrations and Business Licenses MCP server](https://developer.avalara.com/mcp-servers/business_licensing/) | Provides access to Avalara Tax Registration and Business Licenses APIs for license guidance, sales and payroll tax registrations, questionnaire management, and business activity validation. | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-business-licensing-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9idXNpbmVzcy1saWNlbnNpbmcifQ==) |
| [Avalara E-Invoicing & Live Reporting MCP Server](https://developer.avalara.com/mcp-servers/E-Invoicing/) | MCP server providing AI agents access to Avalara's global e-invoicing and live reporting APIs for retrieving document statuses, downloading legal/compliant documents, and enabling seamless compliance across jurisdictions worldwide. | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-e-invoicing-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9lLWludm9pY2luZyJ9) |
| [Avalara Exemption Certificates MCP Server](https://developer.avalara.com/mcp-servers/exemption-certificate-management/) | Provides access to the Avalara Exemption Certificate Management API for managing certificates, customer profiles, and company data. | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-exemption-certificates-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9leGVtcHRpb24tY2VydGlmaWNhdGVzIn0=) |
| [Avalara Cross-Border Trade Services MCP Server](https://developer.avalara.com/mcp-servers/cross-border/) | The Cross-Border Trade Services MCP server supports AI agents by providing tools to perform cross-border transactions, including duty calculations, and access to Trade and Tariff content libraries (including import trade restrictions). | [![Add to Cursor](https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg)](cursor://anysphere.cursor-deeplink/mcp/install?name=avalara-cross-border-mcp-server&config=eyJ1cmwiOiJodHRwczovL21jcC5hdmFsYXJhLmNvbS9jcm9zcy1ib3JkZXIifQ==) |


### Troubleshooting common issues:
* **Connection failed**: Verify your Avalara account status and internet connection.
* **Permission denied**: Make ensure your account has access to the requested services.
* **HTTP 429 (Too Many Requests)**: You've exceeded the server's rate limit.
* Wait a few minutes before retrying.
* Check the server's rate limit details on its individual page.
  


