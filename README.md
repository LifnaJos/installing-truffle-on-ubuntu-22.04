## Steps for installing Truffle on Ubuntu 22.04 LTS
**1. Install Node.js via NVM (Node Version Mananger)** : 

Run the Command, ```wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-26%2009-48-29.png)

Note : 
- To avoid permission errors when installing globally, Node.js (NPM) recommends installing Node.js with a Node version manager (NVM) on Mac and Linux Operating systems
- When the NVM script finishes downloading you will receive a completion message that will instruct you to **close and reopen your terminal to begin using NVM**

**2. Verify NVM Installation** : ```nvm```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-49-34.png)

**3. Install a Truffle compatible version of Node.js** : ```nvm install 18```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-50-09.png)

Note : Verify that NPM is installed : ```npm```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-50-38.png)

Note : 
- It is good practice to run the **npm doctor** command after setting up the  Node.js environment on the computer.
- Npm doctor checks whether the Npm installation packages are configured and installed correctly.
- Npm doctor always looks at the latest version of Npm version available.
- Ignore the warnings and continue onto installing Truffle in the next step.

Run the command, ```npm doctor```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-26%2014-07-16.png)

As per the comments, run the command : ```npm install -g npm@10.1.0```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-26%2014-04-21.png)

**4. Install Truffle** : ```npm install -g truffle```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-51-47.png)

Note : Some warnings or conflicts, may be listed this is typical and should work normally as long as there are no errors.

**5. Verify that Truffle is installed** : ```truffle version```

![NVM](https://github.com/LifnaJos/installing-truffle-on-ubuntu-22.04/blob/main/images/Screenshot%20from%202023-09-25%2021-52-19.png)

## Acknowledgement
* [Truffle Suite Installation on Ubuntu 22.04](https://github.com/orgs/trufflesuite/discussions/5732) helped me to fix the errors in installing Truffle in Ubuntu
* [Guide to Truffle the gateway to Full Stack Blockchain Development](https://trufflesuite.com/guides/ultimate-guide-to-truffle-the-gateway-to-full-stack-blockchain-development/)
* [YouTube Video](https://www.youtube.com/watch?v=pblVFU0mytI)
* [Basic Writing & Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
