# AWS Cloud9-CodeWhisperer User-Manual 

## Introduction
AWS Cloud9 is a cloud-based Integrated Development Environment (IDE) that enables you to write, run, and debug code using just a browser. Cloud9 offers a pre-configured development environment with essential tools such as a code editor, debugger, terminal, and file browser. It supports the development of web applications, serverless applications, and various software types.

## Getting Started with Cloud9
### Step 1:
To get started with AWS Cloud9, log in to your Cloud9 environment. Open the provided URL in your browser and use the provided IAM credentials for login.

**Example:**
- IDE URL: [https://ap-south-1.console.aws.amazon.com/cloud9/ide/3f4f932d4cba45989140784b270d5e2f](https://ap-south-1.console.aws.amazon.com/cloud9/ide/3f4f932d4cba45989140784b270d5e2f)
- Account ID (12 digits) or account alias: 078741615235
- Username: User1
- Password: cTjxsi97@5GP
 
  <img width="258" alt="aws (2)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/01df0fa3-c51d-4f50-bf04-f780a37a439a">    <img width="247" alt="aws (1)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/88cd607a-b018-4319-8435-8f8578bb137a">

### Step 2: IDE Features
Once logged in to Cloud9 IDE, you'll find a code editor, debugger, terminal, and file browser.

<img width="800" alt="aws (7)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/dc5bc023-ec0c-4193-9e44-5fea0bec755c">

- **Code Editor:** Write, edit, and run code with features like syntax highlighting, autocompletion, and linting.
- **Debugger:** Step through code, inspect variables, and set breakpoints for easy debugging.
- **Terminal:** Interact with your AWS environment, run commands, manage files, and access AWS services.
- **File Browser:** Manage files and projects, open files, create new files, and folders.

### Step 3:
Before you start typing code ensure that CodeWhisperer is activated.

Navigate to aws-explorer --> Developer tools --> CodwWhisperer in the left-hand side of window, make sure CodeWhisperer is not on pause (incase its on resume Auto-suggestions mode then click on it : <img width="115" alt="image" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/5b83c890-74bd-4080-9be1-5353096e58bf">
 ).

Below is a screenshot of what you are expected to see: 
<img width="194" alt="image" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/447a912c-f1f0-406b-b1e1-c20a2bb9ae1b">

Also check the bottom of your page if you can see a tick mark implying its activated: <img width="86" alt="aws (8)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/e1f28818-a13f-428c-aa28-fc71c1d70d70"> 

In case you are not able to see a tick mark against CodeWhisperer, please contact L&D team - admin. 


### CodeWhisperer and Prompts Playbook
CodeWhisperer generates real-time code suggestions based on your comments and existing code. It's trained on billions of lines of code and can help with coding tasks and APIs.
<img width="701" alt="aws (4)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/f62a9171-7019-436d-9a04-94180befb6a4">

### Step 4:
Use the toggle tree (CTRL-I) to access user folders. Navigate to your assigned user folder to access examples.

<img width="205" alt="aws (5)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/499512a7-8f7f-44cd-bf32-27b9d855e95a">

### Step 5:
Follow the Amazon CodeWhisperer Immersion Day playbook and start with simple examples to understand how to use CodeWhisperer. As you type, CodeWhisperer will suggest relevant code.
<img width="715" alt="aws (3)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/95fc445d-b502-4a51-8b19-786b4860bf03">

Tips for Using Cloud9:
 * Use the code editor to write, edit, and run your code. 
 * Use the debugger to step through your code line by line, inspect variables, and set breakpoints. 
 * Use the terminal to interact with your AWS environment, or to install libraries such as boto3.  
example:
<img width="651" alt="aws (6)" src="https://github.com/RuchitaSuranagi/Cloud9-CodeWhisperer-Workshop/assets/55045069/1b5e875a-97c7-4b64-9351-b8940c7feb59">

### Additional Resources:
- [Amazon CodeWhisperer Immersion Day (workshops.aws)](https://catalog.us-east-1.prod.workshops.aws/workshops/6838a1a5-4516-4153-90ce-ac49ca8e1357/en-US/03-python)

Get started with some examples in Python. You will begin with a brief introduction and then you will have the opportunity to solve a few challenges. 

Basics 
Prompt Engineering 
User API Challenge 
Image API Challenge 
Deals API Challenge 

- [AWS Cloud9 Documentation](https://docs.aws.amazon.com/cloud9/index.html)
- [AWS Cloud9 User Guide](https://docs.aws.amazon.com/cloud9/latest/user-guide/)
- [AWS Cloud9 API Reference](https://docs.aws.amazon.com/cloud9/latest/APIReference/)
- [AWS Cloud9 CLI Reference](https://docs.aws.amazon.com/cli/latest/reference/cloud9/index.html)
