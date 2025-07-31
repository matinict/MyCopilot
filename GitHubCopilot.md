
# GitHub Copilot for VS Code 

## Update & Upgrade your System

Run this in terminal:

    sudo apt update && sudo apt upgrade -y

  
## installation & Open VS Code
    # Install dependencies
    sudo apt install wget gpg -y
    
    # Import Microsoft GPG key
    wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor | sudo tee /usr/share/keyrings/microsoft.gpg > /dev/null
    
    # Add VS Code repository
    echo "deb [arch=amd64 signed-by=/usr/share/keyrings/microsoft.gpg] https://packages.microsoft.com/repos/code stable main" | sudo tee /etc/apt/sources.list.d/vscode.list
    
    # Update again (to include VS Code repo)
    sudo apt update
    
    # Install VS Code
    sudo apt install code -y
    #Launch VS Code Run: 
    code


## Go to Extensions (or press Ctrl+Shift+X)

## Search for GitHub Copilot

## Click Install

##After installation, sign in with your GitHub account

## Grant required permissions when prompted

## You're ready to use Copilot!

## Usage:

Start typing code and suggestions will appear

Press Tab to accept, or Esc to dismiss
