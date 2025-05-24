# CryptoSun Docs
Documentation for CryptoSun renewable Solana energy network <br>
📚 <a href="https://3rdtest.webflow.io/docs/getting-started">Full Documentation</a> 📚


## API Reference

Our API documentation is available at <a>https://3rdtest.webflow.io/docs/apis</a>

Common endpoints:

1.) `/api/v1/transactions` - Create and query transactions <br>
2.) `/api/v1/blocks` - Get block information <br>
3.) `/api/v1/accounts` - Account management and balance queries <br>
4.) `/api/v1/contracts` - Smart contract deployment and interaction


### Creating a New Doc

We welcome contributions to the CryptoSun documentation! This section explains how to create a new document and add it to the repository, ensuring consistency and clarity for all users.

### Prerequisites

1.) Git: Ensure Git is installed and configured. <br>
2.) Markdown Editor: Use a text editor like VS Code or Typora for writing Markdown. <br>
3.) Access: Fork the repository or have write access to contribute directly. <br>

### Steps to Create a New Doc

1.) Fork or Clone the Repository <br>

Fork the repo on GitHub or clone it locally:
  
    git clone https://github.com/Absolute-Solar/Docs.git
    cd cryptosun-docs

2.) Create a New Branch:

Create a branch for your new doc:

    git checkout -b docs/add-new-topic

3.) Add Your Document

Navigate to the docs/ folder and create a new Markdown file (e.g., new-topic.md). <br>
Use the following template for consistency:

    # Title of Your Document
    
    ## Overview
    Briefly describe the purpose of this document.
    
    ## Details
    Provide detailed information, steps, or explanations.
    
    ## Examples
    Include code snippets, commands, or use cases if applicable.
    ```bash
    example command


4.) Update the Docs Index

Open docs/index.md or the relevant navigation file. <br>
Add a link to your new document:

    - [New Topic](new-topic.md)

5.) Commit Your Changes
Stage and commit your changes:

    git add docs/
    git commit -m "Add new doc on [topic name]"


6.) Push and Create a Pull Request

Push your branch to GitHub:

    git push origin docs/add-new-topic

Go to the repository on GitHub and create a pull request (PR). Describe the purpose of your new doc in the PR description.

### Best Practices

Keep It Clear: Use simple language and short sentences. <br>

Follow Style Guide: Check STYLE_GUIDE.md for formatting rules (e.g., use ## for subsections, code blocks for commands). <br>

Test Links: Ensure all links in your doc are valid. <br>

Preview Locally: Use a Markdown viewer or run a local server (e.g., mkdocs serve if using MkDocs) to check rendering. <br>

### Need Help?

Check existing docs in the docs/ folder for examples. <br>
Ask questions in the issue tracker or join our Discord. <br>
Refer to CONTRIBUTING.md for detailed contribution guidelines. <br>

Thank you for helping improve CryptoSun’s documentation!

## Contributing 

We welcome contributions from the community! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on:

1.) Code of conduct <br>
2.) Development workflow <br>
3.) Pull request process <br>
4.) Coding standards <br>
5.) Testing requirements

---

*This project is currently in [development/beta/production] stage. [Any important disclaimers or notes]*


