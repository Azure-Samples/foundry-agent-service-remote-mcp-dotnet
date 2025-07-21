# Porting QuickStart Sample for Azure Functions
I need to port the Azure AI Foundry Agent Service with Remote MCP Functions from Python to [.NET].
- the Python origin is in this repo: https://github.com/Azure-Samples/foundry-agent-service-remote-mcp-python/
- the .NET output is in this current repo (which is https://github.com/Azure-Samples/foundry-agent-service-remote-mcp-dotnet/)

Prereq steps:
- the working origin repo already exists and has been verified
- the output repo has already been created, even if it is in an empty state
- this prompt is run in the context of the output repo

Steps:
- Create a complete specification in the ./github/prompts folder first and await for approval to perform migration using the new specification prompts.  Guide the user how to take the next step
- Use Azure and Azure Functions best practices MCP tools:
"azmcp_bestpractices_azurefunctions_get-code-generation",
"azmcp_bestpractices_azurefunctions_get-deployment",
"bestpractices_azurefunctions_get-code-generation",
"bestpractices_azurefunctions_get-deployment"
- Validate the template by running the steps in the readme after performing the migration
