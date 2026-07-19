# LangChain v1 Crash Course - Part 1

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Introduction, LangChain v1 Updates, UV Package Manager & Project Setup
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No additional information has been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0}

---

# Table of Contents

1. Course Introduction
2. LangChain Section Overview
3. Why a New LangChain Crash Course?
4. Major Updates in LangChain v1
5. Development Environment
6. UV Package Manager
7. Creating a New Project
8. Initializing the Repository
9. Creating a Virtual Environment
10. Part Summary

---

# 1. Course Introduction

The instructor begins by introducing the overall course.

The complete course is approximately

```
10.5 Hours
```

and is intended to summarize almost every important topic that has evolved in

- Generative AI
- Agentic AI

over the past few months.

The course is designed as a **one-shot resource**, but the instructor mentions that completing and understanding the entire content may take nearly **one month**. :contentReference[oaicite:1]{index=1}

---

# Topics Covered in the Complete Course

The instructor briefly introduces the roadmap of the complete course.

The major topics include

```
Generative AI

↓

Agentic AI

↓

LangChain

↓

LangGraph

↓

Traditional RAG

↓

Agentic RAG

↓

Vectorless RAG

↓

Deep Agents

↓

Deep Research Agents

↓

AI Security

↓

Guardrails

↓

LLM Evaluation

↓

LLM Gateway
```

The goal is to cover all major concepts that have recently evolved in the Generative AI ecosystem. :contentReference[oaicite:2]{index=2}

---

# 2. LangChain Section Overview

The instructor explains that this section is dedicated to

```
LangChain Version 1
```

He mentions that he has already created

- LangChain playlists
- LangGraph playlists
- End-to-end projects

on his channel.

This crash course focuses specifically on the **latest updates** introduced in LangChain v1. :contentReference[oaicite:3]{index=3}

---

# 3. Why a New LangChain Crash Course?

According to the lecture,

LangChain has introduced several updates in its latest version.

Instead of watching multiple individual videos,

the instructor combines everything into one updated crash course.

The primary goal is to remain

```
Up-to-date
```

with the latest LangChain documentation.

---

# Areas Updated in LangChain

The instructor specifically mentions updates related to

- Agent Creation
- Memory
- Middleware
- Model Integration
- Tool Calling
- Structured Output
- Message Types
- Short-Term Memory
- Streaming
- Guardrails

These topics will be covered throughout the LangChain section. :contentReference[oaicite:4]{index=4}

---

# 4. Documentation Structure

The instructor opens the latest LangChain documentation.

The documentation now contains multiple sections.

```
LangChain

LangGraph

Deep Agents
```

The intention is to study each of these using the most recent documentation so that the implementation always follows the latest APIs. :contentReference[oaicite:5]{index=5}

---

# 5. Development Environment

Before writing any code,

the instructor prepares the development environment.

He mentions several IDEs that can be used.

Examples discussed include

```
VS Code

Cursor

Google AI Studio IDE
```

During the lecture,

the demonstrations are performed using

```
Google AI Studio IDE
```

The instructor mentions that this IDE provides agent support and code suggestions while developing applications. :contentReference[oaicite:6]{index=6}

---

# Project Folder

A new project folder is created.

```
langchain-updated
```

The instructor starts everything from scratch so that the complete project setup can be demonstrated.

---

# 6. UV Package Manager

The lecture introduces

```
UV Package Manager
```

The instructor describes it as

- a Python package manager
- a project manager
- written in Rust
- extremely fast

The objective is to use UV throughout the LangChain crash course instead of older installation methods. :contentReference[oaicite:7]{index=7}

---

# Installing UV

The instructor explains that

the installation instructions are available on the official UV website.

Separate installation commands exist for

- macOS
- Linux
- Windows

For Windows,

the installation is demonstrated using

```
PowerShell
```

After executing the installation command,

UV gets installed on the system.

---

# Why UV?

According to the lecture,

UV makes it easier to

- create projects
- manage dependencies
- manage environments

while remaining on the latest versions of packages.

---

# 7. Creating a New Project

After installing UV,

the instructor begins creating the project.

The first step is to initialize the working directory.

Command used

```bash
uv init
```

The lecture emphasizes remembering this command.

Its purpose is

```
Initialize

↓

Working Repository
```

Executing this command creates the initial project structure. :contentReference[oaicite:8]{index=8}

---

# Files Created

After running

```bash
uv init
```

the project contains files such as

```
pyproject.toml

main.py

.python-version
```

---

# pyproject.toml

The instructor explains that

this file contains information such as

- Python version
- project configuration

In the lecture,

the generated Python version is

```
Python 3.13
```

The instructor recommends always working with the latest Python version whenever possible. :contentReference[oaicite:9]{index=9}

---

# 8. Creating a Virtual Environment

The next step is creating a virtual environment.

Command used

```bash
uv venv
```

The lecture explains that this is the simplest command for creating a virtual environment using UV.

Once executed,

UV creates the environment using the current Python version.

Example shown in the lecture

```
Python 3.13.2
```

The virtual environment is then created automatically. :contentReference[oaicite:10]{index=10}

---

# Why Create a Virtual Environment?

The instructor states that

before installing any libraries,

the virtual environment should be activated.

Libraries are installed inside this environment,

keeping the project isolated.

---

# Activating the Environment

The activation command is copied from the generated virtual environment.

After executing it,

the terminal indicates that

the virtual environment is active.

The project is now ready for dependency installation.

---

# Workflow So Far

The setup process followed in the lecture is

```
Install UV

↓

Create Project Folder

↓

uv init

↓

Project Initialized

↓

uv venv

↓

Virtual Environment Created

↓

Activate Virtual Environment
```

---

# Key Observations

- The LangChain section focuses on the latest Version 1 updates.
- The instructor recommends using the newest documentation.
- UV Package Manager is used throughout the project.
- `uv init` initializes the repository.
- `uv venv` creates the virtual environment.
- The virtual environment should be activated before installing libraries.

---

# Part 1 Summary

In this part, the instructor introduces the overall AI course and begins the LangChain v1 crash course. The lecture explains why a new LangChain tutorial is required, highlighting the major updates introduced in Version 1. The development environment is prepared using the **UV Package Manager**, a new project is initialized using `uv init`, and a virtual environment is created with `uv venv`. At this stage, the project setup is complete and ready for dependency installation.

---

**Next:** Part 2 covers **Requirements File, Installing Libraries, `pyproject.toml`, API Keys, `.env` setup, and preparing the project for building LangChain applications.**
# LangChain v1 Crash Course - Part 2

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Installing Libraries, Project Configuration, API Keys & Environment Setup
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No additional information has been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0}

---

# Table of Contents

1. Installing Project Dependencies
2. Creating `requirements.txt`
3. Installing Libraries using UV
4. Understanding `pyproject.toml`
5. Version Management
6. API Keys
7. Creating `.env`
8. Installing Additional Libraries
9. Preparing the Project
10. Beginning the LangChain Notebook
11. Part Summary

---

# 1. Installing Project Dependencies

After creating and activating the virtual environment,

the next step is installing all required libraries.

The instructor mentions that

keeping track of package versions is important,

and the UV Package Manager simplifies this process. :contentReference[oaicite:1]{index=1}

---

# 2. Creating `requirements.txt`

A new file is created outside the virtual environment.

```
requirements.txt
```

The instructor adds the libraries that will be required throughout the course.

The libraries shown are

```text
langchain

langchain-community

langchain-openai

langchain-groq

python-dotenv

langchain-google-genai
```

These are treated as the default libraries for the upcoming examples.

The instructor also mentions that suggestions may appear while typing,

but recommends typing the package names manually. :contentReference[oaicite:2]{index=2}

---

# Purpose of `requirements.txt`

The file contains all the libraries that need to be installed for the project.

Instead of installing packages individually,

they can all be installed together.

---

# 3. Installing Libraries using UV

The instructor demonstrates installing every dependency from

```
requirements.txt
```

using the command

```bash
uv add -r requirements.txt
```

This installs every library listed inside the file.

---

## Previous Approach

The lecture compares this with the earlier approach.

Previously,

installation was commonly done using

```bash
pip install -r requirements.txt
```

With UV,

the equivalent command becomes

```bash
uv add -r requirements.txt
```

After execution,

all the listed libraries are installed automatically. :contentReference[oaicite:3]{index=3}

---

# 4. Installed Versions

Once installation completes,

the instructor opens

```
pyproject.toml
```

instead of checking package versions manually.

The file now contains

the versions of every installed dependency.

Examples shown include

```
langchain

langchain-community

langchain-google-genai

...
```

The lecture emphasizes that

this file provides a clear view of the package versions currently being used. :contentReference[oaicite:4]{index=4}

---

# Why Check `pyproject.toml`?

According to the instructor,

this helps identify

- current package versions
- project dependencies
- base versions used during development

This becomes useful even if newer versions are released later.

---

# Recommendation

The instructor recommends

always trying to work with

```
Recent Versions
```

of LangChain,

since

- new functionality is added,
- some features may be deprecated,
- and some APIs may move to different libraries.

---

# Workflow So Far

```
Create requirements.txt

↓

Add Required Libraries

↓

uv add -r requirements.txt

↓

Dependencies Installed

↓

Check pyproject.toml
```

---

# 5. Creating API Keys

The next step is preparing the API keys required for the project.

The instructor demonstrates creating three API keys.

```
Google API Key

Groq API Key

OpenAI API Key
```

These will be used throughout the LangChain examples. :contentReference[oaicite:5]{index=5}

---

## Google API Key

The lecture demonstrates opening

```
Google AI Studio
```

The process shown is

```
Dashboard

↓

Create API Key

↓

Select Project

↓

Generate Key
```

The generated key is copied for later use.

---

## Groq API Key

Similarly,

the instructor opens the Groq dashboard

and creates a new API key.

---

## OpenAI API Key

The same process is repeated for

OpenAI.

By the end,

all three API keys are available.

---

# 6. Creating `.env`

To store these keys,

the instructor creates a file named

```
.env
```

The API keys are pasted into this file.

The `.env` file now contains

```
Google API Key

Groq API Key

OpenAI API Key
```

These keys will later be loaded into the application. :contentReference[oaicite:6]{index=6}

---

# 7. Installing Additional Libraries

The instructor also installs one additional package

for working with Jupyter Notebook.

Command used

```bash
uv add ipykernel
```

The lecture explains that

`ipykernel`

provides the kernel required by Jupyter notebooks.

---

## Installing Individual Libraries

The instructor explains that

whenever only one library needs to be installed,

the command is

```bash
uv add library_name
```

Example

```bash
uv add ipykernel
```

---

## Installing Multiple Libraries

When libraries already exist inside

```
requirements.txt
```

the command remains

```bash
uv add -r requirements.txt
```

The lecture distinguishes these two installation methods. :contentReference[oaicite:7]{index=7}

---

# Summary of UV Commands

## Initialize Project

```bash
uv init
```

---

## Create Virtual Environment

```bash
uv venv
```

---

## Install All Libraries

```bash
uv add -r requirements.txt
```

---

## Install Single Library

```bash
uv add library_name
```

---

# 8. Preparing the Project

At this point,

the instructor summarizes everything completed so far.

The project now contains

- Virtual Environment
- Requirements File
- Installed Dependencies
- API Keys
- `.env`
- Updated `pyproject.toml`

The environment is now completely prepared for LangChain development. :contentReference[oaicite:8]{index=8}

---

# 9. Beginning the LangChain Notebook

The instructor creates a new folder

```
updated-langchain
```

Inside it,

the first notebook is created.

```
langchain_intro.ipynb
```

The notebook uses

the virtual environment created earlier.

The first markdown cell identifies the notebook as

```
LangChain Version 1
```

To verify that everything works correctly,

a simple Python statement is executed successfully.

The instructor also confirms that

the `.env` file has been loaded correctly,

indicating that the project setup is complete. :contentReference[oaicite:9]{index=9}

---

# Complete Setup Workflow

```
Install UV

↓

Initialize Project

↓

Create Virtual Environment

↓

Activate Environment

↓

Create requirements.txt

↓

Install Libraries

↓

Verify pyproject.toml

↓

Generate API Keys

↓

Create .env

↓

Install ipykernel

↓

Create Notebook

↓

Ready for LangChain Development
```

---

# Key Observations

- Dependencies are managed using the UV Package Manager.
- `requirements.txt` stores all project libraries.
- `uv add -r requirements.txt` installs every dependency.
- `pyproject.toml` records the installed package versions.
- Three API keys are created:
  - Google
  - Groq
  - OpenAI
- API keys are stored inside `.env`.
- `ipykernel` is installed for Jupyter Notebook support.
- The project setup is completed before writing any LangChain code.

---

# Part 2 Summary

In this part, the instructor prepares the complete development environment required for LangChain v1. A `requirements.txt` file is created containing the necessary libraries, which are installed using the **UV Package Manager**. The installed package versions are verified through `pyproject.toml`. The instructor then generates **Google**, **Groq**, and **OpenAI** API keys, stores them in a `.env` file, installs `ipykernel` for notebook support, and finally creates the first Jupyter notebook. At the end of this section, the project is fully configured and ready to begin building LangChain applications.

---

**Next:** Part 3 covers **What is an Agent, limitations of plain LLMs, Tool Calling, Agent Architecture, `create_agent()`, creating the first tool, invoking an agent, message format, tool execution flow, and understanding autonomous agents.**
# LangChain v1 Crash Course - Part 3A

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Introduction to Agents, Limitations of LLMs, Tool Calling & Creating the First Agent
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No additional concepts have been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0}

---

# Table of Contents

1. Beginning with Agents
2. What is an LLM?
3. A Simple Generative AI Application
4. Limitation of Plain LLMs
5. Why Tools are Needed
6. What is an Agent?
7. Previous Agent Creation Approach
8. Creating an Agent in LangChain v1
9. The `create_agent()` Function
10. Initial Agent Structure
11. Part Summary

---

# 1. Beginning with Agents

After completing the project setup,

the instructor begins the most important topic of the LangChain crash course:

```
Agents
```

According to the lecture,

although Generative AI initially focused mainly on Large Language Models (LLMs),

the current focus has shifted toward

```
Agentic AI
```

The instructor describes agents as a very important topic that is widely discussed today. :contentReference[oaicite:1]{index=1}

---

# 2. Starting with a Plain LLM

The lecture first explains how a normal LLM works before introducing agents.

A simple architecture is shown.

```
User

↓

LLM

↓

Response
```

The LLM may be

- OpenAI
- Google Gemini
- Groq
- Any Open Source Model

The overall flow is straightforward.

---

# Example

Input

```
Write a 200-word paragraph
about Artificial Intelligence.
```

Execution

```
Input

↓

LLM

↓

Output
```

Output

```
200-word paragraph
```

The instructor refers to this as a simple

```
Generative AI Application.
```

The LLM receives an input,

processes it,

and generates an output. :contentReference[oaicite:2]{index=2}

---

# Basic LLM Workflow

```
User Query

↓

LLM

↓

Generated Response
```

This is the traditional way most Generative AI applications operate.

---

# 3. Limitation of Plain LLMs

The instructor then presents a question that exposes an important limitation.

Example

```
Tell me today's AI news.
```

At first glance,

this appears to be a simple request.

However,

the instructor explains why a plain LLM cannot reliably answer it.

---

# Training Cut-off

According to the lecture,

every LLM has

```
Training Data

↓

Cut-off Date
```

This means

the model has already been trained on historical information.

It does **not** automatically know

- today's news
- tomorrow's events
- recently published information

because that information did not exist during training. :contentReference[oaicite:3]{index=3}

---

# Problem Illustration

```
User

↓

Today's AI News

↓

LLM
```

The LLM alone

cannot answer this request because

it does not possess current information.

The instructor emphasizes that this is one of the fundamental limitations of using only a plain LLM.

---

# 4. Why External Tools are Required

To answer questions involving current information,

the LLM must depend on another component.

The lecture introduces this component as

```
Tool
```

Possible examples mentioned include

- Third-party APIs
- Google Search
- Other external tools

The exact implementation of the tool is not discussed yet,

but its purpose is clearly explained.

:contentReference[oaicite:4]{index=4}

---

# Updated Architecture

Instead of

```
User

↓

LLM

↓

Response
```

the architecture now becomes

```
           Tool

             ▲

             │

User → LLM ──┘

↓

Response
```

The LLM is now connected to an external tool.

---

# Role of the Tool

The instructor explains that

the tool contains

the information that the LLM does not possess.

For example,

if the tool has access to current news,

the LLM can obtain that information before generating a response.

---

# 5. Decision Making inside the LLM

When the user asks

```
Today's AI News
```

the LLM first evaluates the request.

It determines that

it cannot answer the question using only its own knowledge.

It therefore decides to call the appropriate tool.

The lecture emphasizes this decision-making capability as an important characteristic of agents. :contentReference[oaicite:5]{index=5}

---

# Context

Once the external tool is executed,

it returns information back to the LLM.

The instructor refers to this returned information as

```
Context
```

Overall flow

```
User

↓

LLM

↓

Tool

↓

Context

↓

LLM

↓

Final Output
```

Only after receiving this context

does the LLM generate the final response.

---

# 6. What is an Agent?

The lecture now introduces the basic idea of an agent.

According to the instructor,

an agent is an LLM that can

- make simple decisions,
- determine when a tool is required,
- invoke that tool,
- obtain context,
- and finally generate an answer.

The instructor refers to this as

```
Basic Agent
```

or

```
Autonomous Agent.
```

:contentReference[oaicite:6]{index=6}

---

# Basic Agent Flow

```
User Query

↓

LLM

↓

Decision

↓

Tool

↓

Context

↓

LLM

↓

Final Response
```

Unlike a plain LLM,

the model now performs an additional decision-making step.

---

# Why is it Autonomous?

According to the lecture,

the model itself decides

- whether a tool is required,
- which tool should be called,
- and when the response should be generated.

The user does not manually select the tool.

---

# 7. Previous Approach for Building Agents

The instructor briefly discusses how agents were previously created.

Earlier,

developers had to manually combine

```
LLM

+

Tool

+

Architecture
```

The architecture mentioned in the lecture is

```
ReAct Architecture
```

This required additional setup and linkage between

the LLM

and

the tools.

The instructor remarks that this process was comparatively more difficult. :contentReference[oaicite:7]{index=7}

---

# LangChain v1 Simplification

The instructor explains that

LangChain Version 1

has simplified this process considerably.

Creating agents now requires much less code.

This simplification is one of the major improvements introduced in the updated framework.

---

# 8. Creating the First Agent

The lecture now begins writing the code.

The required import is

```python
from langchain.agents import create_agent
```

The instructor introduces

```
create_agent()
```

as the primary function for building an agent in LangChain Version 1. :contentReference[oaicite:8]{index=8}

---

# Agent Object

An agent object is created.

```python
agent = create_agent(...)
```

The lecture explains that

the remaining parameters will configure

how the agent behaves.

---

# Parameters Used

The first parameter specifies

the model.

Example shown

```python
model="gpt-5"
```

---

The second parameter is

```python
tools=[]
```

At this stage,

the tools list is intentionally left empty

because no tools have been created yet.

---

The instructor also specifies

a system prompt.

Example

```text
You are a helpful assistant.
```

This becomes the instruction supplied to the LLM whenever the agent is executed.

The lecture also briefly experiments with

```
verbose=True
```

but removes it after observing that it is not currently supported in this example. :contentReference[oaicite:9]{index=9}

---

# Initial Agent Structure

Since no tools have been added,

the generated agent consists only of

```
Start

↓

Model

↓

End
```

This represents a simple LLM pipeline.

The instructor notes that

the tool connection is currently missing

because the tools list is empty.

---

# Workflow So Far

```
User

↓

Agent

↓

Model

↓

Output
```

The agent has been successfully created,

but it has not yet gained any additional capabilities through tools.

---

# Key Observations

- Agentic AI builds upon traditional LLM applications.
- Plain LLMs cannot answer questions requiring current information.
- External tools provide missing context.
- The LLM decides when a tool is needed.
- The returned information from the tool is referred to as **Context**.
- LangChain v1 simplifies agent creation through `create_agent()`.
- Initially, the agent contains only the model because no tools have been added.

---

# Part 3A Summary

In this part, the instructor introduces the concept of **Agents** by first explaining the limitations of traditional LLM-based applications. A plain LLM can answer questions based only on its training data and cannot access current information such as today's news. To overcome this limitation, the LLM is connected to external **tools**, which provide additional **context** before the final response is generated. This decision-making ability forms the basis of an **Agent**. The lecture concludes by introducing LangChain v1's `create_agent()` function and creating the first agent with an empty tools list, establishing the foundation for adding tool-calling capabilities in the next section.

---

**Next:** **Part 3B** covers **creating the first tool (`get_weather()`), connecting it to the agent, automatic tool selection, `agent.invoke()`, message formats, Human/AI/Tool messages, execution flow, and autonomous tool calling.**
# LangChain v1 Crash Course - Part 3B

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Creating the First Tool, Tool Calling, Agent Invocation & Message Flow
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No additional concepts have been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0}

---

# Table of Contents

1. Adding the First Tool
2. Connecting the Tool to the Agent
3. Updated Agent Architecture
4. Running an Agent
5. Message Format
6. Tool Calling
7. Conversation Flow
8. Displaying Responses
9. Autonomous Agents
10. Version Verification
11. Part Summary

---

# 1. Creating the First Tool

Until now,

the agent contains only

```
Start

↓

Model

↓

End
```

Since no tools are connected,

the model behaves like a normal LLM.

The instructor now creates the first tool.

---

## Weather Function

A Python function is defined.

```python
def get_weather(city: str) -> str:
    return f"The weather in {city} is sunny."
```

The lecture also adds a **docstring**.

Example

```text
Get the weather for a city.
```

The instructor explains that this function will later become a tool that the agent can call. :contentReference[oaicite:1]{index=1}

---

# Purpose of the Function

The weather function is only a demonstration.

Instead of making a real API request,

it simply returns

```text
The weather in <city> is sunny.
```

The instructor mentions that in a real application,

this function could call an external weather API.

---

# 2. Adding the Tool to the Agent

After defining the function,

it is added to the tools list.

Instead of

```python
tools=[]
```

the tools parameter now contains

```python
tools=[get_weather]
```

The weather function has now become part of the agent. :contentReference[oaicite:2]{index=2}

---

# Updated Agent

The instructor explains that

the agent is now smarter than before.

Previously,

the model had no external capabilities.

Now,

it can invoke the weather tool whenever required.

---

# 3. Updated Agent Architecture

Before adding the tool

```
Start

↓

Model

↓

End
```

---

After adding the tool

```
          Weather Tool

               ▲

               │

Start → Model ─┘

↓

End
```

The lecture points out that

the visualization now includes

the tool connected to the model. :contentReference[oaicite:3]{index=3}

---

# Decision Making

Suppose the user asks

```
What is the weather
in Bangalore?
```

The model first determines

whether it already knows the answer.

Since weather information should come from the connected tool,

the model invokes

```
get_weather()
```

instead of generating the answer directly.

---

# Workflow

```
User

↓

Model

↓

Weather Tool

↓

Context

↓

Model

↓

Response
```

---

# 4. Running the Agent

The lecture demonstrates executing the agent.

The method used is

```python
agent.invoke(...)
```

This starts the complete execution of the agent. :contentReference[oaicite:4]{index=4}

---

# First Attempt

Initially,

the instructor passes only a string.

Example

```python
"What is the weather
like in New York?"
```

An error occurs.

The lecture intentionally keeps the error visible

to explain the correct input format.

---

# Reason for the Error

The instructor explains that

the agent expects

```
Dictionary Input
```

rather than a plain string.

Therefore,

the request format must be changed.

:contentReference[oaicite:5]{index=5}

---

# 5. Correct Message Format

The corrected input becomes

```python
{
    "messages": [
        {
            "role": "user",
            "content": "What is the weather like in New York?"
        }
    ]
}
```

The instructor mentions that

the request must be provided as

```
messages
```

rather than a plain string.

---

# User Role

The role supplied is

```text
user
```

The lecture states that

this represents a

```
Human Message.
```

More message types will be discussed later in the course.

---

# Input Flow

```
Dictionary

↓

messages

↓

role

↓

content
```

This is the expected format while using

```
create_agent()
```

:contentReference[oaicite:6]{index=6}

---

# 6. Tool Calling

After correcting the input,

the instructor executes the agent again.

This time,

the execution succeeds.

The lecture explains the complete sequence.

---

## Step 1

Human message reaches the agent.

```
What is the weather
like in New York?
```

---

## Step 2

The LLM examines the request.

It realizes

that weather information should be obtained

from the connected tool.

---

## Step 3

The tool

```
get_weather()
```

is called automatically.

---

## Step 4

The function returns

```
The weather in New York
is sunny.
```

This returned value becomes

```
Context.
```

---

## Step 5

The LLM receives the context

and generates

the final response.

The instructor emphasizes that

the tool invocation happens automatically. :contentReference[oaicite:7]{index=7}

---

# Why Does the Model Know Which Tool to Use?

The lecture answers an important question.

How does the model know

that it should call

```
get_weather()?
```

According to the instructor,

this happens because

the function contains a

```
Docstring.
```

Example

```text
Get the weather for a city.
```

The LLM understands

the purpose of the tool

from this description.

Therefore,

it selects the appropriate function automatically. :contentReference[oaicite:8]{index=8}

---

# Complete Conversation Flow

```
Human Message

↓

Model

↓

Tool Call

↓

Tool Message

↓

AI Message
```

The instructor demonstrates

that these messages appear

during execution.

---

# Types of Messages Observed

The execution displays

```
Human Message
```

↓

```
Tool Message
```

↓

```
AI Message
```

Each message represents

a different stage of execution.

---

# 7. Displaying the Response

The lecture stores

the returned value.

```python
response = agent.invoke(...)
```

The final response can then be displayed.

The instructor also explains that

the returned object contains

the complete conversation,

not only the final answer.

:contentReference[oaicite:9]{index=9}

---

# Extracting the Final Output

Instead of displaying

the complete conversation,

the last message can be selected.

The lecture retrieves

the content of the final message,

which represents

the agent's final response.

---

# Simplified Input

The instructor also demonstrates

a shorter syntax.

Instead of manually specifying

the role,

the query can simply be provided

inside the

```
messages
```

parameter.

Even with this simplified form,

the execution succeeds.

The lecture notes that

the framework automatically identifies

the message appropriately. :contentReference[oaicite:10]{index=10}

---

# Handling Minor Errors

During the demonstration,

the instructor intentionally leaves

some coding mistakes

and corrects them while recording.

Examples include

- incorrect input format
- spelling mistakes

Despite these corrections,

the framework is able to execute successfully once the input is properly structured.

The instructor keeps these mistakes visible

to help viewers understand

the debugging process.

---

# 8. Autonomous Agents

The lecture concludes by revisiting

the definition of an agent.

According to the instructor,

the agent

- receives the user query,
- decides which tool should be used,
- executes the tool,
- obtains context,
- and generates the final answer.

This complete process occurs automatically,

which is why it is referred to as an

```
Autonomous Agent.
```

The lecture also mentions that

multiple tools can be connected to the same agent,

and the model decides

which one should be invoked based on the user's request. :contentReference[oaicite:11]{index=11}

---

# Version Verification

Before concluding,

the instructor prints

the installed LangChain version.

Example shown

```python
import langchain

print(langchain.__version__)
```

The version displayed in the lecture is

```
1.1.0
```

This confirms that the demonstrations are performed using the updated LangChain Version 1.

---

# Overall Execution Flow

```
User Query

↓

Human Message

↓

LLM

↓

Decision

↓

Tool Call

↓

Context Returned

↓

AI Message

↓

Final Response
```

---

# Key Observations

- A Python function can be converted into a tool by adding it to the agent.
- The weather function is used only as a demonstration.
- The tool is connected through the `tools` parameter.
- `agent.invoke()` executes the complete agent workflow.
- Input must be supplied as a dictionary containing `messages`.
- The model automatically selects the correct tool.
- The tool's **docstring** helps the model understand its purpose.
- The returned object contains the complete conversation history.
- Multiple tools can be attached to the same agent.
- The model decides which tool should be executed.

---

# Part 3B Summary

In this part, the instructor demonstrates how a Python function becomes a **tool** by adding it to the agent's `tools` list. Using a simple `get_weather()` function, the lecture shows how the LLM automatically decides to invoke the correct tool based on the user's query. The proper input format for `agent.invoke()` is introduced using the `messages` dictionary, followed by the complete execution flow involving **Human Messages**, **Tool Messages**, and **AI Messages**. The section concludes by explaining why such systems are called **Autonomous Agents**, since the model independently decides when and which tool to use.

---

**Next:** **Part 4** covers **Model Integration (OpenAI, Google Gemini, Groq), `init_chat_model`, ChatOpenAI, ChatGoogleGenerativeAI, ChatGroq, Streaming, Batch Processing, and the introduction to Tool Creation.**
# LangChain v1 Crash Course - Part 4A

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Model Integration (OpenAI, Google Gemini & Groq)
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No additional concepts have been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0}

---

# Table of Contents

1. Introduction to Model Integration
2. Loading Environment Variables
3. `init_chat_model()`
4. OpenAI Model Integration
5. Google Gemini Integration
6. Direct Provider-Specific Classes
7. Groq Model Integration
8. Summary of Integration Methods
9. Part Summary

---

# 1. Introduction to Model Integration

After explaining how agents work, the instructor moves to the next important topic:

```
Model Integration
```

The objective is to learn how to integrate different LLM providers with a LangChain application.

The lecture focuses on three major providers:

- OpenAI
- Google Gemini
- Groq

The instructor explains that although each provider offers different models, LangChain provides a common way to interact with them. :contentReference[oaicite:1]{index=1}

---

# Models Discussed

## OpenAI

Examples mentioned:

- GPT-4.1
- GPT-4.5

---

## Google

Examples mentioned:

- Gemini 2.5 Flash

---

## Groq

The instructor demonstrates Groq using one of its supported models.

---

# Objective

Instead of learning a different workflow for every provider,

LangChain provides a unified interface for model integration.

---

# 2. Loading Environment Variables

Before loading any model,

the instructor first loads the API keys stored in the `.env` file.

The required modules are imported.

```python
import os
from dotenv import load_dotenv
```

The environment variables are initialized.

```python
load_dotenv()
```

The API keys are then accessed using

```python
os.getenv(...)
```

Examples shown include

- OpenAI API Key
- Google API Key
- Groq API Key

These keys are used throughout the remaining demonstrations. :contentReference[oaicite:2]{index=2}

---

# Environment Setup Workflow

```
.env

↓

load_dotenv()

↓

os.getenv()

↓

API Key Available

↓

Load Model
```

---

# 3. `init_chat_model()`

The instructor introduces a new function

```python
init_chat_model()
```

Import

```python
from langchain.chat_models import init_chat_model
```

According to the lecture,

this function provides a simple way to initialize chat models from different providers.

Instead of writing provider-specific code immediately,

the same initialization function can be used.

:contentReference[oaicite:3]{index=3}

---

# General Workflow

```
API Key

↓

init_chat_model()

↓

Model Object

↓

invoke()

↓

Response
```

---

# 4. OpenAI Integration

The first provider demonstrated is

```
OpenAI
```

A model is initialized using

```python
model = init_chat_model(...)
```

The instructor specifies the model name.

Example shown

```text
GPT-4.1
```

After correcting a small typing mistake,

the model is successfully initialized.

The returned object represents a ChatOpenAI model. :contentReference[oaicite:4]{index=4}

---

# Invoking the Model

Once initialized,

the model is executed using

```python
model.invoke(...)
```

Example prompt

```text
Hello, how are you?
```

The request is sent to the LLM,

and the returned response is stored.

---

# Returned Response

The response object contains

```
AI Message
```

along with

the generated content.

The instructor demonstrates that

the actual text can be extracted using

```python
response.content
```

This prints only the generated answer instead of the complete response object. :contentReference[oaicite:5]{index=5}

---

# OpenAI Workflow

```
Prompt

↓

GPT-4.1

↓

AI Message

↓

response.content
```

---

# Changing Models

The instructor explains that

changing the OpenAI model is straightforward.

For example,

another supported model can be specified simply by changing the model name.

The rest of the code remains unchanged.

---

# 5. Google Gemini Integration

The lecture next demonstrates

Google Gemini integration.

The same initialization function is used.

```python
init_chat_model(...)
```

However,

the provider is specified differently.

Instead of only providing a model name,

the instructor specifies

```
google_genai:model_name
```

The demonstrated example uses

```
Gemini 2.5 Flash
```

The lecture explains that

only the provider prefix and model name change,

while the overall workflow remains the same. :contentReference[oaicite:6]{index=6}

---

# Invoking Gemini

The model is invoked using

```python
model.invoke(...)
```

Example question

```text
Why do parrots talk?
```

The generated answer is returned by the Gemini model.

The instructor notes that

the first request may take a little longer,

after which subsequent requests execute normally.

---

# Google Gemini Workflow

```
Prompt

↓

Gemini

↓

AI Message

↓

response.content
```

---

# 6. Provider-Specific Classes

After demonstrating the generic initialization function,

the instructor introduces another approach.

Instead of

```python
init_chat_model()
```

provider-specific classes may be used directly.

---

## ChatOpenAI

Import

```python
from langchain_openai import ChatOpenAI
```

Initialization

```python
ChatOpenAI(...)
```

The remaining workflow stays the same.

```
Prompt

↓

ChatOpenAI

↓

Response
```

The instructor explains that this produces the same result as the previous approach,

but directly uses the OpenAI implementation. :contentReference[oaicite:7]{index=7}

---

## ChatGoogleGenerativeAI

The same idea is demonstrated for Google.

Import

```python
from langchain_google_genai import ChatGoogleGenerativeAI
```

The model is initialized,

followed by

```python
invoke()
```

The resulting output matches the earlier demonstration using `init_chat_model()`.

According to the lecture,

both approaches are valid. :contentReference[oaicite:8]{index=8}

---

# Comparison

## Generic

```
init_chat_model()

↓

Provider

↓

Model
```

---

## Provider Specific

```
ChatOpenAI

or

ChatGoogleGenerativeAI

↓

Model
```

Both approaches ultimately load the desired LLM.

---

# 7. Groq Integration

The final provider demonstrated is

```
Groq
```

The lecture again starts with

```python
init_chat_model()
```

The provider prefix is changed to

```
groq:model_name
```

The instructor demonstrates invoking the model exactly as before.

Example question

```text
Why do parrots talk?
```

The Groq model generates the corresponding response. :contentReference[oaicite:9]{index=9}

---

# ChatGroq

The instructor also demonstrates

the provider-specific class.

Import

```python
from langchain_groq import ChatGroq
```

The model is initialized,

and

```python
invoke()
```

is used to generate the response.

The execution flow remains identical to the previous examples. :contentReference[oaicite:10]{index=10}

---

# Complete Integration Workflow

```
Load API Keys

↓

Choose Provider

↓

Initialize Model

↓

invoke()

↓

AI Response
```

---

# Two Ways to Load Models

## Method 1

Generic

```text
init_chat_model()
```

Supports

- OpenAI
- Google
- Groq

---

## Method 2

Provider-specific classes

```
ChatOpenAI

ChatGoogleGenerativeAI

ChatGroq
```

Both methods ultimately interact with the same LLM.

---

# Key Observations

- Environment variables are loaded using `load_dotenv()`.
- API keys are retrieved using `os.getenv()`.
- `init_chat_model()` provides a common interface for different providers.
- OpenAI, Gemini, and Groq follow almost identical invocation workflows.
- Responses are obtained using `invoke()`.
- `response.content` extracts only the generated text.
- Provider-specific classes are also available:
  - `ChatOpenAI`
  - `ChatGoogleGenerativeAI`
  - `ChatGroq`
- Both initialization approaches produce equivalent results.

---

# Part 4A Summary

In this part, the instructor explains how LangChain integrates with multiple Large Language Model providers. After loading API keys from the `.env` file, models from **OpenAI**, **Google Gemini**, and **Groq** are initialized using the generic `init_chat_model()` interface. The lecture then demonstrates an alternative approach using provider-specific classes such as `ChatOpenAI`, `ChatGoogleGenerativeAI`, and `ChatGroq`. Regardless of the provider, the workflow remains largely identical: initialize the model, invoke it with a prompt, and retrieve the generated response through `response.content`.

---

**Next:** **Part 4B** covers **Streaming, `model.stream()`, Batch Processing, `model.batch()`, `max_concurrency`, and the introduction to Tool Creation.**
# LangChain v1 Crash Course - Part 4B

> **Course:** Generative AI & Agentic AI Complete Course
>
> **Section:** LangChain v1 Crash Course
>
> **Topic:** Streaming, Batch Processing & Introduction to Tool Creation
>
> **Source:** These notes are based **strictly** on the lecture transcript provided. No concepts have been added beyond what is explained in the video. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

---

# Table of Contents

1. Why Streaming?
2. `model.stream()`
3. Comparing Streaming vs `invoke()`
4. Batch Processing
5. `model.batch()`
6. Parallel Execution
7. `max_concurrency`
8. When to Use Streaming & Batch
9. Introduction to Tool Creation
10. Part Summary

---

# 1. Why Streaming?

Until now,

every example has used

```python
model.invoke()
```

With `invoke()`,

the model generates the complete response first,

and only then returns it to the application.

The instructor points out that this introduces a delay,

especially for long responses,

because the user must wait until the entire generation finishes. :contentReference[oaicite:3]{index=3}

---

# Traditional Workflow

```
Prompt

↓

LLM

↓

Generate Entire Response

↓

Display Output
```

The complete answer appears only after generation finishes.

---

# Motivation for Streaming

Instead of waiting,

the instructor introduces

```
Streaming
```

where the generated content is displayed

while the model is still producing it.

---

# 2. Streaming with `model.stream()`

The lecture demonstrates using

```python
model.stream(...)
```

instead of

```python
model.invoke(...)
```

The returned object produces small chunks

as they are generated by the model.

These chunks are displayed immediately,

allowing the response to appear progressively. :contentReference[oaicite:4]{index=4}

---

# Example Flow

```
Prompt

↓

model.stream()

↓

Chunk 1

↓

Chunk 2

↓

Chunk 3

↓

...

↓

Complete Response
```

---

# Printing Streamed Output

The instructor iterates through

the generated chunks

and prints them one after another.

A delimiter and flushing mechanism are also demonstrated

to make the streamed output easier to observe.

Examples shown include

```python
end=...
```

and

```python
flush=True
```

These help display each generated chunk immediately. :contentReference[oaicite:5]{index=5}

---

# Example Prompt

The lecture demonstrates streaming using prompts such as

```text
Write me a 200-word paragraph
```

and

```text
Why do parrots have colorful feathers?
```

As the model generates text,

the content is displayed progressively,

rather than waiting for the entire paragraph to finish. :contentReference[oaicite:6]{index=6}

---

# Streaming Workflow

```
User Prompt

↓

LLM

↓

Generate Token

↓

Display Token

↓

Generate Next Token

↓

Display Next Token

↓

...

↓

Finished
```

---

# 3. Streaming vs `invoke()`

The instructor directly compares

the two approaches.

---

## Using Streaming

```
Prompt

↓

LLM

↓

Output appears continuously
```

The user starts seeing the response immediately.

---

## Using `invoke()`

```
Prompt

↓

LLM

↓

Wait...

↓

Wait...

↓

Complete Response
```

Nothing is displayed until generation is complete. :contentReference[oaicite:7]{index=7}

---

# Instructor's Observation

According to the lecture,

streaming provides a better user experience because

the generated text becomes visible

while it is still being produced.

---

# Comparison

| Streaming | invoke() |
|------------|----------|
| Output appears gradually | Output appears only at the end |
| Better user experience | User waits for completion |
| Useful for long responses | Simpler for short responses |

---

# 4. Batch Processing

The instructor next introduces

```
Batch Processing
```

Batch processing is described as

sending multiple independent requests

to the model simultaneously.

Rather than invoking the model once for each input,

multiple requests are grouped together

and processed in parallel. :contentReference[oaicite:8]{index=8}

---

# Why Batch?

Suppose there are multiple independent questions.

Instead of

```
Question 1

↓

Model
```

followed by

```
Question 2

↓

Model
```

and so on,

all questions can be submitted together.

---

# 5. `model.batch()`

The lecture demonstrates

```python
model.batch(...)
```

The input consists of

a list of prompts.

Examples shown include

```text
Why do parrots have colorful feathers?

How do airplanes fly?

What is quantum computing?
```

These are supplied together

to the batch function. :contentReference[oaicite:9]{index=9}

---

# Batch Workflow

```
Question 1

Question 2

Question 3

↓

model.batch()

↓

LLM

↓

Response 1

Response 2

Response 3
```

---

# Output

The instructor explains that

all responses are returned together,

rather than invoking the model separately

for each request.

---

# Benefits

According to the lecture,

batch processing can

- improve performance
- reduce cost
- execute requests in parallel

This makes it useful

when multiple independent prompts

must be processed simultaneously. :contentReference[oaicite:10]{index=10}

---

# 6. Parallel Execution

The instructor emphasizes that

batch requests are

```
Independent Requests
```

Each prompt is unrelated to the others.

Because of this,

they can be executed

in parallel.

---

# Parallel Architecture

```
Prompt 1 ─┐

Prompt 2 ─┼──► LLM

Prompt 3 ─┘

↓

Responses Returned Together
```

---

# 7. `max_concurrency`

The lecture introduces

a configuration parameter

called

```text
max_concurrency
```

This parameter specifies

how many requests

may execute in parallel.

Example shown

```python
config={
    "max_concurrency": 5
}
```

If ten prompts are supplied,

the instructor explains that

they can be processed

in groups,

based on the configured concurrency limit. :contentReference[oaicite:11]{index=11}

---

# Example

Suppose

```
10 Questions
```

are submitted.

If

```
max_concurrency = 5
```

then

```
Questions 1–5

↓

Execute

↓

Questions 6–10

↓

Execute
```

---

# Workflow

```
Input List

↓

Batch

↓

Concurrency Control

↓

LLM

↓

Responses
```

---

# 8. When to Use Streaming

The instructor notes that

streaming is especially useful

while developing chatbots,

where users expect

responses to begin appearing immediately.

---

# When to Use Batch

Batch processing is useful

when there are

multiple independent prompts

that should be processed together,

improving overall efficiency. :contentReference[oaicite:12]{index=12}

---

# 9. Introduction to Tool Creation

After completing model integration,

streaming,

and batch processing,

the instructor begins the next major topic:

```
Tools
```

The lecture recalls the earlier discussion on agents,

where an LLM becomes more capable

by connecting it to external tools. :contentReference[oaicite:13]{index=13}

---

# What is a Tool?

The instructor defines a tool

as a functionality

that the model can request

whenever additional capabilities are required.

Examples mentioned include

- Database access
- Web search
- Running code
- API requests
- News retrieval
- Other independent functionalities

These tools extend

the capabilities of the LLM

beyond its training data. :contentReference[oaicite:14]{index=14}

---

# Relationship with Agents

The instructor revisits

the earlier agent architecture.

```
User

↓

LLM

↓

Decision

↓

Tool

↓

Context

↓

LLM

↓

Response
```

The upcoming lectures focus on

creating these tools

and connecting them

to LangChain agents.

---

# Workflow Covered So Far

```
Project Setup

↓

Model Integration

↓

Streaming

↓

Batch Processing

↓

Tool Creation (Next)
```

---

# Key Observations

- `model.stream()` displays generated content progressively.
- Streaming improves responsiveness for long outputs.
- `model.invoke()` waits until the full response is generated.
- `model.batch()` processes multiple independent prompts together.
- Batch execution improves performance and can reduce cost.
- `max_concurrency` controls the number of parallel requests.
- Streaming is commonly used in chatbot applications.
- The next topic introduces creating tools for LangChain agents.

---

# Part 4B Summary

In this section, the instructor explains two important LangChain capabilities: **Streaming** and **Batch Processing**. Streaming allows responses to be displayed incrementally as they are generated, providing a better user experience than waiting for `model.invoke()` to finish. Batch processing enables multiple independent prompts to be sent to the model simultaneously using `model.batch()`, with optional control over parallel execution through `max_concurrency`. The lecture concludes by introducing **Tool Creation**, explaining that tools provide external functionality—such as web search, APIs, databases, or code execution—that agents can invoke whenever additional context or capabilities are required.

---

## LangChain v1 Crash Course Completed ✅

The complete LangChain v1 crash course notes now cover:

- **Part 1:** Project setup, UV Package Manager & environment creation
- **Part 2:** Dependencies, `requirements.txt`, `.env`, API keys & notebook setup
- **Part 3A:** Introduction to Agents, LLM limitations & `create_agent()`
- **Part 3B:** Tool calling, `agent.invoke()`, message flow & autonomous agents
- **Part 4A:** OpenAI, Gemini & Groq model integration
- **Part 4B:** Streaming, Batch Processing & introduction to Tool Creation

The subsequent sections of the course move beyond the LangChain crash course into deeper LangChain features (such as tools in detail, prompts, messages, memory, middleware, guardrails, structured output, and related topics), followed later by LangGraph and Deep Agents.