# ES6 Classes Project

This project is aimed at helping you understand and practice ES6 classes in JavaScript. By the end of this project, you should be able to explain the following concepts without the need for external assistance:

1. How to define a Class
2. How to add methods to a class
3. Why and how to add a static method to a class
4. How to extend a class from another
5. Metaprogramming and symbols

## Requirements

Before you begin, make sure you meet the following requirements:

- Operating System: Ubuntu 18.04 LTS
- Node.js Version: 12.11.x
- Editors Allowed: vi, vim, emacs, Visual Studio Code
- Ensure all your files end with a new line.
- A `README.md` file at the root of the project folder is mandatory.
- Use the `.js` extension for your code files.
- Testing will be done using Jest with the command `npm run test`.
- Code will be verified against linting standards using ESLint.
- Your code must pass all tests and linting checks. You can verify the entire project by running `npm run full-test`.

## Setup

### Installing NodeJS 12.11.x

To install Node.js 12.11.x in your home directory on Ubuntu 18.04 LTS, follow these steps:

```bash
# Download the NodeSource setup script
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh

# Run the setup script with sudo
sudo bash nodesource_setup.sh

# Install Node.js and npm
sudo apt install nodejs -y

# Verify Node.js and npm versions
nodejs -v
npm -v

