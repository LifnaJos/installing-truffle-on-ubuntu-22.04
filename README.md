## Steps for installing Truffle on Ubuntu 22.04 LTS
1. Install Node.js via NVM (Node Version Mananger)

```wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash```

Note : 
- To avoid permission errors when installing globally, Node.js (NPM) recommends installing Node.js with a Node version manager (NVM) on Mac and Linux Operating systems
- When the NVM script finishes downloading you will receive a completion message that will instruct you to close and reopen your terminal to begin using NVM

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-49-34.png)

2. Verify NVM Installation

```nvm```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-50-09.png)

3. Install a Truffle compatible version of Node.js

```nvm install 18```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-50-25.png)

Note : Verify that NPM is installed 

```npm```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-50-38.png)

Note : 
- It is good practice to run the **npm doctor** command after setting up the  Node.js environment on the computer.
- Npm doctor checks whether the Npm installation packages are configured and installed correctly.
- Npm doctor always looks at the latest version of Npm version available.
- Ignore the warnings and continue onto installing Truffle in the next step.

```npm doctor```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-51-00.png)

4. Install Truffle

```npm install -g truffle```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-51-47.png)

Note : Some warnings or conflicts, may be listed this is typical and should work normally as long as there are no errors.

5. Verify that Truffle is installed

```truffle version```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-52-19.png)
