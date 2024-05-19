
# TypeScript Development Environment Setup

## Step 1: Install Node.js

1. Open your web browser and go to - [Node.js](https://nodejs.org/) (includes npm).
2. Click on the "LTS" version download button to download the Node.js installer.
3. Run the installer and follow the on-screen instructions, using the default settings.

<br/>

## Step 2: Install TypeScript

1. Open your terminal (Command Prompt or PowerShell on Windows).
2. Run the following command to install TypeScript globally:
* For Windows users: `npm install -g typescript`
* For Mac users: sudo `npm install -g typescript`

<br/>

## Step 3: Install Visual Studio Code (VSCode)

1. Go to VSCode [Visual Studio Code (VS Code)](https://code.visualstudio.com/) download page.
2. Download the appropriate version for your operating system.
3. Run the installer and follow the on-screen instructions.

<br/> 

## Step 3: Initialize TypeScript Configuration

###  Create a New Project Directory:

1. Choose or create a directory where you want to set up your TypeScript project. For example, you can create a directory named `typescript-project` on your desktop:

```bash
    mkdir ~/Desktop/typescript-project
    cd ~/Desktop/typescript-project
```

2. Open that folder in VSCode and open the integrated terminal (`View`> `Terminal`).
3. Initialize a TypeScript project with the command: `tsc --init`

`tsc --init` this command will generate the `ts.config` file

<br/>

## Step 5: Set Execution Policy (Windows Users Only)

1. go to the windows search bar, and search Powershell
2. Open it by right clicking `Run as an administrator`.
3. Set the execution policy by pasting this command: `Set-ExecutionPolicy RemoteSigned`

<br/>

## Step 6: Make it a Node.js Project

1. In the terminal, create a `package.json` file with the command: `npm init -y`

<br/>

## Step 7: Write TypeScript Code

1. Create a new TypeScript file in your project directory (e.g., `index.ts`).
2. Write your TypeScript code in this file


```bash
   console.log("This is my first line of code");   
```
<br/>

## Step 8: Transpile TypeScript to JavaScript

1. In the terminal, run the command: `tsc`
2. this `tsc` command will transplie the typescript code into the javascript code.

<br/>

## Step 9: Run Transpiled JavaScript


1. After transpilation, you'll find a corresponding JavaScript file in your project directory.
2. Run the JavaScript file using Node.js with the command: `node index.js`
3. You should see the output: `This is my first line of code`