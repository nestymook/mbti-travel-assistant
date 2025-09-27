# Hosting Strands Agents with OpenAI models in Amazon Bedrock AgentCore Runtime

## Overview

In this tutorial we will learn how to host your existing agent, using Amazon Bedrock AgentCore Runtime. 

We will focus on a Strands Agents with OpenAI model example. For Strands Agents with Amazon Bedrock model check [here](../01-strands-with-bedrock-model) and 
for LangGraph with Amazon Bedrock model check [here](../02-langgraph-with-bedrock-model)


### Tutorial details

| Information         | Details                                                                  |
|:--------------------|:-------------------------------------------------------------------------|
| Tutorial type       | Conversational                                                           |
| Agent type          | Single                                                                   |
| Agentic Framework   | Strands Agents                                                           |
| LLM model           | GPT 4.1 mini                                                             |
| Tutorial components | Hosting agent on AgentCore Runtime. Using Strands Agent and OpenAI Model |
| Tutorial vertical   | Cross-vertical                                                           |
| Example complexity  | Easy                                                                     |
| SDK used            | Amazon BedrockAgentCore Python SDK and boto3                             |

### Tutorial Architecture

In this tutorial we will describe how to deploy an existing agent to AgentCore runtime. 

For demonstration purposes, we will  use a Strands Agent using Amazon Bedrock models

In our example we will use a very simple agent with two tools: `get_weather` and `get_time`. 

<div style="text-align:left">
    <img src="images/architecture_runtime.png" width="100%"/>
</div>

### Tutorial key Features

* Hosting Agents on Amazon Bedrock AgentCore Runtime
* Using OpenAI models
* Using Strands Agents