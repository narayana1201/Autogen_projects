Autogen Projects
This repository contains projects built using the Autogen Framework.

# Coding Agent:

The Coding Agent allows you to develop backend Python modules with the assistance of an AI agent powered by LLMs like ChatGPT and Gemini. You can specify a "work_dir" folder name, and the agent will automatically create the directory and save the generated code files in it.

**How It Works:**

User Input: The agent comprehends your input.
Code Generation: It writes the code in the specified directory.
Execution & Debugging: The agent executes the code using PowerShell command-line tools. If any errors occur, the agent will debug, rewrite, and re-execute the code until it runs successfully on the local system.
# Installation
**Follow these steps to set up the environment:**

**1. Create a New Environment:**
   virtualenv venv
**2. Activate the Environment:**
   venv\Scripts\activate
**3. Install Requirements:**
   pip install -r requirements.txt
**4. Start the Agent:**
   python coding_agent.py






# References
**Autogen Documentation :** https://microsoft.github.io/autogen/

Autogen GitHub Repository : https://github.com/microsoft/autogen/tree/main


