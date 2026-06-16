
# <img src="A-Check.png" alt="A-Check" width="60"> Avalara

**This is a non-community repo, created and maintained by Avalara**
___

## Avalara MCP Servers


[MCP (Model Context Protocol)](https://modelcontextprotocol.io/docs/getting-started/intro)   servers connect AI applications with Avalara's tax compliance systems in a standardized way. MCP servers allow partners and developers to integrate AI-driven tax workflows, automate cross-border compliance, and access Avalara's regularly updated tax content.

Avalara-supported MCP servers include AvaTax, Returns, E-Invoicing and Live Reporting, Tax Registrations and Business Licenses and Exemption Certificate Management, Cross Border Trade, and Tax Content. More services will be added over time.



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

## Available MCP Servers


| Server | Description | Install |
|:-------|:------------|:--------|
| [Avalara AvaTax MCP server](https://developer.avalara.com/mcp-servers/avatax/) | Provides access to the Avalara AvaTax API for tax calculation, transaction management, nexus handling, and compliance data. | <a href="https://cursor.com/en/install-mcp?name=avalara-avatax&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2F2YXRheCJ9"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Returns MCP server](https://developer.avalara.com/mcp-servers/returns/) | Provides access to the Avalara Global Returns API for tax returns management, filing calendars, and compliance data. | <a href="https://cursor.com/en/install-mcp?name=avalara-returns&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL3JldHVybnMiLCJoZWFkZXJzIjp7IkF1dGhvcml6YXRpb24iOiJCZWFyZXIgand0X3Rva2VuX2hlcmUifX0%3D"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Tax Registrations and Business License MCP server](https://developer.avalara.com/mcp-servers/business_licensing/) | Provides access to Avalara Tax Registration and Business Licenses APIs for license guidance, sales and payroll tax registrations, questionnaire management, and business activity validation. | <a href="https://cursor.com/en/install-mcp?name=avalara-bl&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2JsIiwiaGVhZGVycyI6eyJBdXRob3JpemF0aW9uIjoiQmVhcmVyIGFjY2Vzc190b2tlbl9oZXJlIn19"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara E-Invoicing & Live Reporting MCP server](https://developer.avalara.com/mcp-servers/E-Invoicing/) | Provides access to Avalara E-Invoicing and Live Reporting APIs for retrieving document statuses, downloading compliant documents, and managing compliance across jurisdictions. | <a href="https://cursor.com/en/install-mcp?name=avalara-elr&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2VsciJ9"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Exemption Certificates Management MCP server](https://developer.avalara.com/mcp-servers/exemption-certificate-management/) | Provides access to the Avalara Exemption Certificate Management API for managing certificates, customer profiles, and company data. | <a href="https://cursor.com/en/install-mcp?name=avalara-ecm&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2VjbSJ9"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Cross-Border Trade Services MCP server](https://developer.avalara.com/mcp-servers/cross-border/) | The Cross-Border Trade Services MCP server supports AI agents by providing tools to perform cross-border transactions, including duty calculations, and access to Trade and Tariff content libraries (including import trade restrictions). | <a href="https://cursor.com/en/install-mcp?name=avalara-cross-border&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2Nyb3NzLWJvcmRlciJ9"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Tax Content MCP server](https://developer.avalara.com/mcp-servers/atc/) | Provides access to Avalara Tax Content (ATC) data, including Transaction Tax Export (TTE) Configurations, Jobs, Communications and User Defined Functions for Lodging and Autorental. | <a href="https://cursor.com/en/install-mcp?name=avalara-atc&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2F0YyJ9"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Communications MCP server](https://developer.avalara.com/mcp-servers/comms/) | Provides access to Avalara Communications tax calculation services, supporting taxes for voice, data, VoIP, and messaging transactions. It also provides reference data including tax types, jurisdiction codes, and location information. | <a href="https://cursor.com/en/install-mcp?name=avalara-comms&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2NvbW1zIn0%3D"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Dev Documentation MCP server](https://developer.avalara.com/mcp-servers/docs/) | Provides access to Avalara developer documentation and integration guides, including technical documentation, product information, how-to guides, and code examples. | <a href="https://cursor.com/en/install-mcp?name=avalara-docs&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2RvY3MifQ%3D%3D"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |
| [Avalara Classification MCP server](https://developer.avalara.com/mcp-servers/classification/) | Provides Harmonized System (HS) code classification for cross-border transactions. Supports managed classification requests, HS code validation and verification, and AI-powered import and export, and enriched trade compliance content lookup. | <a href="https://cursor.com/en/install-mcp?name=avalara-classification&config=eyJ0eXBlIjoiaHR0cCIsInVybCI6Imh0dHBzOi8vbWNwLmF2YWxhcmEuY29tL2NsYXNzaWZpY2F0aW9uIn0%3D"><img src="https://developer.avalara.com/_next/static/images/cusrsorinstalldark-38837d7218a6c5107baf81b454bddd11.svg" alt="Add to Cursor"></a> |


### Troubleshooting common issues:
* **Connection failed**: Verify your Avalara account status and internet connection.
* **Permission denied**: Make ensure your account has access to the requested services.
* **HTTP 429 (Too Many Requests)**: You've exceeded the server's rate limit.
* Wait a few minutes before retrying.
* Check the server's rate limit details on its individual page.



