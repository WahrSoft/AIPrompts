# CoPilot Application Modernization Framework - Prompt Library

This repository contains a comprehensive prompt library designed to accelerate application modernization and Azure adoption using GitHub Copilot and other AI assistants. The prompts are organized into logical phases of the modernization journey, providing structured guidance for analyzing, migrating, and deploying applications to Azure.

## 🎯 Purpose

This prompt library empowers developers and architects to:
- **Systematically analyze** existing applications for modernization opportunities
- **Migrate applications** from legacy platforms to modern Azure services
- **Deploy modernized applications** following Azure best practices
- **Accelerate Azure adoption** through AI-assisted development workflows

## 📁 Repository Structure

The prompts are organized into three main phases of application modernization:

### 1. Analyze Phase (`1 - Analyze/`)
Discovery and assessment prompts for understanding existing applications and identifying modernization opportunities.

- **`Discover.txt`** - Comprehensive analysis prompts for solution modernization, dependency mapping, and categorization. Includes specialized detection for .NET Framework components requiring migration.

### 2. Migrate Phase (`2 - Migrate/`)
Platform-specific migration guidance and transformation prompts.

#### Java Applications (`Java/`)
- **`General.txt`** - General Java application migration prompts (to be expanded)

#### .NET Framework to .NET 8 (`NETFrameworkToNET8/`)
Specialized prompts for modernizing .NET Framework applications:
- **`ASMX.txt`** - ASMX Web Services migration guidance
- **`EntityFramework.txt`** - Entity Framework modernization prompts
- **`General.txt`** - General .NET Framework to .NET 8 migration
- **`Remoting.txt`** - .NET Remoting replacement strategies
- **`WCF.txt`** - WCF to modern alternatives migration
- **`Webforms.txt`** - Web Forms to modern web frameworks
- **`WindowsWorkflow.txt`** - Windows Workflow modernization

### 3. Deploy Phase (`3 - Deploy/`)
Deployment and infrastructure prompts for Azure.

- **`General.txt`** - Azure deployment best practices and automation

## 🚀 How to Use

1. **Start with Analysis**: Use prompts from the `1 - Analyze/` folder to understand your current application landscape
2. **Choose Migration Path**: Select appropriate prompts from `2 - Migrate/` based on your technology stack
3. **Deploy to Azure**: Apply `3 - Deploy/` prompts to establish your Azure infrastructure and deployment pipelines

## 🔧 Integration with AI Tools

These prompts are designed to work seamlessly with:
- **GitHub Copilot** - For code generation and modernization assistance
- **Azure OpenAI** - For architectural guidance and best practices
- **Other AI Assistants** - Compatible with various AI development tools

## 📊 Modernization Artifacts

The analysis prompts will generate a `modernization.json` file in your repository root, documenting:
- Legacy technology components identified
- Recommended migration paths
- Azure service mappings
- Modernization priorities

## 🤝 Contributing

To contribute new prompts or improve existing ones:
1. Follow the established folder structure
2. Ensure prompts are clear, actionable, and Azure-focused
3. Test prompts with real-world scenarios
4. Update this README when adding new categories

## 📋 Prerequisites

- Basic understanding of your application architecture
- Access to GitHub Copilot or similar AI development tools
- Azure subscription for deployment phases

## 🎓 Getting Started

1. Clone this repository to your development environment
2. Review the `Discover.txt` prompt to understand the analysis process
3. Run the discovery analysis on your target application
4. Follow the generated recommendations through the migration and deployment phases

## 📞 Support

For questions about specific modernization scenarios or prompt usage, please refer to the individual prompt files or open an issue in this repository.

---

*This prompt library is part of a comprehensive Application Modernization framework designed to accelerate Azure adoption through AI-assisted development practices.*