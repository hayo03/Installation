## Preparing for the Chatbot Development Tutorial
In preparation for the tutorial, we can start by setting up a few tools that will ensure we make the most out of the online sessions and focus on learning about chatbots. These tools that we will be using are the following:
  - Python. it's the programming language we will be relying on for our code examples. We are preparing the tutorial so that the programming requirements are minimal, and if you had any experience with another programming language you can still play and modify the examples we provide.
  - Code Editor. We strongly suggest installing a code editor for writing and editing the python code. We are using Visual Studio Code, but feel free to use your editor of choice in case you have one already installed. 
  - Ngrok. It's a powerful tool that will allow us to publish on the Web the services we develop (locally) without the complexity of deploying them into servers. We need ngrok so that our backend services are available to the chatbots we design in DialogFlow.

Below we provide instructions on how to install and test your environment for these tools. Jump directly to the section of interest if you already have some of these tools installed.

## Install Python 3 
1. According to your OS system, download and install Python from [Here](https://www.python.org/downloads/). Choose the latest version, i.e. "Download Python 3.9". 
2. To make sure that Python is installed successfully, run "python3" in the terminal (OS, Ubuntu) or in PowerShell (Windows).The result of this has to be like the following:

<p align="center">
  <img src="images/python3run.png">
</p>

## Install Visual Studio Code 
According to your OS system, download and install Visual Studio Code from [Here](https://code.visualstudio.com/download). 

## Install Ngrok
Download it from [here](https://ngrok.com/download), unzip it, and in the terminal (OS, Ubuntu) or in PowerShell (Windows) just run the following commands:

```
cd Path_To_Ngrok
./ngrok http 8081 (or ngrok http 8081 if the first one does not work)

```

The result of this run has to be like the following:

<p align="center">
  <img src="images/ngrokrun.png">
</p>

<b>Note.</b> Please note that a Ngrok session will still available only for 2 hours, so you have to rerun Ngrok each time these 2 hours expire.
