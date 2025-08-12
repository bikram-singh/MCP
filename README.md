# MCP Repository - GitHub Actions Calculator

## 📋 Project Overview

This repository demonstrates the creation and implementation of a GitHub Actions CI/CD workflow using the **GitHub MCP (Model Context Protocol) Server**. The project showcases automated workflow creation, configuration, and execution through AI-assisted development.

## 🎯 Project Objectives

- Create a GitHub Actions workflow with manual trigger capabilities
- Implement user input collection through `workflow_dispatch` event
- Perform automated calculations and display results
- Demonstrate MCP server integration for repository management

## 🛠️ What We Built

### GitHub Actions Workflow: Add Two Numbers Calculator

**File Location**: `.github/workflows/add-numbers.yml`

**Workflow Features**:
- ✅ **Manual Trigger**: Uses `workflow_dispatch` for on-demand execution
- ✅ **User Input Collection**: Prompts for two numbers when triggered
- ✅ **Automated Calculation**: Adds the input numbers together
- ✅ **Multi-format Output**: Console logs and formatted summary
- ✅ **Professional UI**: Clean results display in GitHub Actions interface

## 🚀 How to Use the Workflow

### Step-by-Step Instructions:

1. **Navigate to Actions**
   - Go to the repository: https://github.com/bikram-singh/MCP
   - Click on the **Actions** tab

2. **Select the Workflow**
   - Find "Add Two Numbers Calculator" in the workflow list
   - Click on the workflow name

3. **Run the Workflow**
   - Click the **"Run workflow"** button
   - Enter your desired numbers in the input fields:
     - `First Number`: Enter any numeric value
     - `Second Number`: Enter any numeric value
   - Click **"Run workflow"** to execute

4. **View Results**
   - Monitor the workflow execution in real-time
   - Check the detailed logs for step-by-step output
   - View the formatted summary with calculation results

## 🔧 Technical Implementation

### Workflow Configuration

```yaml
name: Add Two Numbers Calculator

on:
  workflow_dispatch:
    inputs:
      first_number:
        description: 'Enter the first number'
        required: true
        type: number
        default: '0'
      second_number:
        description: 'Enter the second number'
        required: true
        type: number
        default: '0'
```

### Key Workflow Steps

1. **Repository Checkout**: Uses `actions/checkout@v4`
2. **Input Display**: Shows the user-provided numbers
3. **Calculation Logic**: Performs addition using shell arithmetic
4. **Result Formatting**: Creates professional output displays
5. **Summary Generation**: Builds markdown summary for GitHub UI

## 🤖 MCP Server Integration

This project was created using the **GitHub MCP Server**, which enabled:

### Automated Repository Operations
- **Repository Creation**: Programmatic creation of the MCP repository
- **File Management**: Automated creation of workflow files
- **Content Generation**: AI-assisted workflow configuration
- **Documentation**: Automated README generation

### MCP Server Capabilities Demonstrated
- Repository initialization with proper structure
- GitHub Actions workflow creation and configuration
- File content generation with proper formatting
- Commit management and version control integration

## 📊 Workflow Output Example

When executed, the workflow provides:

### Console Output
```
First number: 15
Second number: 25
Calculation: 15 + 25 = 40
🧮 Addition Calculator Result 🧮
================================
First Number:  15
Second Number: 25
Sum:           40
================================
✅ Calculation completed successfully!
```

### Summary Table
| Input | Value |
|-------|-------|
| First Number | 15 |
| Second Number | 25 |
| **Sum** | **40** |

## 🎉 Project Achievements

### Successfully Implemented:
- ✅ GitHub repository creation via MCP server
- ✅ Automated CI/CD workflow development
- ✅ User input collection mechanism
- ✅ Mathematical operation automation
- ✅ Professional result presentation
- ✅ Comprehensive documentation

### Technologies Used:
- **GitHub Actions**: Workflow automation platform
- **YAML Configuration**: Workflow definition language
- **Shell Scripting**: Calculation and output logic
- **Markdown**: Documentation and result formatting
- **MCP Server**: AI-assisted development platform

## 🔄 Workflow Trigger Events

Current Configuration:
- **Manual Trigger**: `workflow_dispatch` with user inputs

Potential Extensions:
- Schedule-based triggers (`cron`)
- Push-based triggers (`push`)
- Pull request triggers (`pull_request`)
- Issue-based triggers (`issues`)

## 🚀 Future Enhancements

Potential improvements and extensions:

1. **Advanced Operations**
   - Multiplication, subtraction, division
   - Complex mathematical functions
   - Matrix operations

2. **Input Validation**
   - Range validation
   - Type checking
   - Error handling

3. **Output Options**
   - File generation
   - Email notifications
   - Slack integration

4. **Multi-language Support**
   - Python calculations
   - JavaScript operations
   - Other programming languages

## 📝 Development Process

### MCP Server Workflow:
1. **Repository Initialization**: Automated repo creation
2. **Workflow Design**: AI-assisted configuration
3. **Implementation**: Automated file creation
4. **Testing**: Manual workflow execution
5. **Documentation**: Comprehensive README generation

## 🤝 Contributing

To contribute to this project:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the workflow
5. Submit a pull request

## 📞 Support

For questions or issues:
- Create an issue in this repository
- Check the GitHub Actions documentation
- Review the workflow logs for troubleshooting

---

**Created with ❤️ using GitHub MCP Server**

*This project demonstrates the power of AI-assisted development and automated CI/CD pipeline creation.*
