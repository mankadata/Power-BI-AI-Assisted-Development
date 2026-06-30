# Power BI AI-Assisted Development Case Study

## Disclaimer
### Security Notice
Large Language Models (LLMs) may unintentionally expose sensitive information from semantic models, including data values or metadata, through logs or generated responses. Be cautious when sharing chat sessions, prompts, or project files publicly.
### Technical Limitation
The Power BI Modeling MCP Server currently supports modeling operations only. It cannot directly modify all Power BI metadata such as report page layouts, visual placements, or full report design elements.
________________________________________
## Project Overview
This portfolio project does not focus on star schema redesign or data engineering optimization.
The dataset used in this project was intentionally AI-generated, consisting of:
-	one fact table
-	one Date dimension table
This decision was intentional because the primary goal was to demonstrate a modern VS Code + Power BI MCP workflow, rather than solving complex data modeling challenges.

### The project focuses on:
-	AI-assisted Power BI development
-	advanced DAX measure creation
-	modern custom visual design using Deneb / Vega-Lite
-	UX-focused report design

Using synthetic data allowed me to safely experiment with advanced BI workflows without exposing real business data.
________________________________________
## Technology Stack & Development Workflow
This project was built using a modern analytics engineering workflow centered around Power BI, AI-assisted development, and user-focused report design.

### VS Code + Power BI MCP / CLI
The core development workflow was built around Visual Studio Code, Power BI MCP (Model Context Protocol), and Power BI Project files (PBIP / TMDL).
This enabled semantic model development, measure generation, metadata management, and documentation outside the traditional Power BI Desktop-only workflow.

AI-assisted development helped accelerate:
•	semantic model exploration
•	DAX generation and refactoring
•	measure documentation
•	report page planning
•	layout and navigation design
•	end-to-end BI documentation
________________________________________
## Power BI MCP (Model Context Protocol)
Power BI MCP served as the foundation of the AI collaboration workflow.

The easiest setup for MCP is using:
-	Visual Studio Code extension
-	GitHub Copilot Chat 

This was the approach used in this project, although manual setup is also possible.

Before using MCP, you must connect to a Power BI semantic model through one of the following:

#### Power BI Desktop
Connect to '[File Name]' in Power BI Desktop

#### Fabric Workspace Semantic Model
Connect to semantic model '[Semantic Model Name]' in Fabric Workspace '[Workspace Name]'

### PBIP Project Files
Open semantic model from PBIP folder '[Path to definition/TMDL folder]'

#### This project used the third approach (PBIP/TMDL).
Instead of generating isolated code snippets, the AI worked with full project context, including:
-	semantic model structure
-	relationships
-	measures
-	report metadata
-	folder hierarchy
-	design conventions
  
This created a more symbiotic development workflow where AI acted as a BI engineering copilot, not just a code generator.
