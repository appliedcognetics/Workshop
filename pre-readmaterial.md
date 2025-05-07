<!-- ---------- Styles (include once at the top of your .md) -------- -->
<style>
.agenda-table{
  border-collapse:collapse;
  width:100%;
  font-size:0.95rem;
}
.agenda-table th,
.agenda-table td{
  border:1px solid #555;
  padding:6px 8px;
}
.agenda-table th{
  background:#333;
  color:#fff;
}
.agenda-table tr:nth-child(odd){          /* skips the header automatically */
  background:#1f1f1f;
  color:#eee;
}
.agenda-table tr:nth-child(even){
  background:#262626;
  color:#eee;
}
</style>
# Microsoft 2 Day Workshop & Pre-Read Materials
## Workshop Agenda

### Day&nbsp;1 – Foundations & Initial Build
<table class="agenda-table">
  <tr><th>Time</th><th>Duration</th><th>Session</th><th>Format</th><th>Related&nbsp;pre-read</th></tr>
  <tr><td>09:00 – 09:10</td><td>10&nbsp;min</td><td>Welcome &amp; Objectives</td><td>Presentation</td><td>–</td></tr>
  <tr><td>09:10 – 10:10</td><td>60&nbsp;min</td><td>Agents &amp; Agentic Systems</td><td>Presentation</td><td>Agents and Agentic Systems</td></tr>
  <tr><td>10:10 – 10:50</td><td>40&nbsp;min</td><td>Toolchain &amp; Tool-Calling Overview (SK, AI Foundry, MCP, Azure Functions, Vector Store)</td><td>Presentation</td><td>Build Agentic System Components</td></tr>
  <tr><td>10:50 – 11:05</td><td>15&nbsp;min</td><td><strong>Break</strong></td><td>–</td><td>–</td></tr>
  <tr><td>11:05 – 12:35</td><td>90&nbsp;min</td><td>Use-Case Discovery &amp; Crafting the User Experience</td><td>Hands-on</td><td>Use-Case Exploration &amp; Ideation; Crafting a User Experience</td></tr>
  <tr><td>12:35 – 13:35</td><td>60&nbsp;min</td><td><strong>Lunch</strong></td><td>–</td><td>–</td></tr>
  <tr><td>13:35 – 16:45</td><td>190&nbsp;min</td><td><strong>Lab 1 – Build Vector Store, Knowledge Graph &amp; Assemble the Agentic System</strong></td><td>Hands-on</td><td>Build Agentic System Components; Assembling the Agentic System</td></tr>
  <tr><td>16:45 – 17:00</td><td>15&nbsp;min</td><td><strong>Break</strong></td><td>–</td><td>–</td></tr>
  <tr><td>17:00 – 17:25</td><td>25&nbsp;min</td><td>Day-1 Wrap-up &amp; Q&amp;A</td><td>Presentation</td><td>–</td></tr>
</table>

---

### Day&nbsp;2 – End-to-End Build, Validation &amp; Evaluation
<table class="agenda-table">
  <tr><th>Time</th><th>Duration</th><th>Session</th><th>Format</th><th>Related&nbsp;pre-read</th></tr>
  <tr><td>09:00 – 09:15</td><td>15&nbsp;min</td><td>Recap &amp; Day-2 Goals</td><td>Presentation</td><td>–</td></tr>
  <tr><td>09:15 – 11:00</td><td>105&nbsp;min</td><td><strong>Build Sprint 1 – End-to-End Solution: Deploy, Modify &amp; Test</strong></td><td>Hands-on</td><td>Assembling the Agentic System</td></tr>
  <tr><td>11:00 – 11:15</td><td>15&nbsp;min</td><td><strong>Break</strong></td><td>–</td><td>–</td></tr>
  <tr><td>11:15 – 12:45</td><td>90&nbsp;min</td><td>Build Sprint 2 – Data Pipelines &amp; Validation</td><td>Hands-on</td><td>Build Agentic System Components</td></tr>
  <tr><td>12:45 – 13:45</td><td>60&nbsp;min</td><td>Testing, Tracing &amp; Evaluation</td><td>Hands-on</td><td>Evaluating the Agentic Application</td></tr>
  <tr><td>13:45 – 14:15</td><td>30&nbsp;min</td><td>Evaluation &amp; Responsible AI Briefing</td><td>Presentation</td><td>Evaluating the Agentic Application</td></tr>
  <tr><td>14:15 – 15:15</td><td>60&nbsp;min</td><td><strong>Lunch</strong></td><td>–</td><td>–</td></tr>
  <tr><td>15:15 – 16:00</td><td>45&nbsp;min</td><td>Demo &amp; Peer Review</td><td>Hands-on</td><td>Evaluating the Agentic Application</td></tr>
  <tr><td>16:00 – 16:15</td><td>15&nbsp;min</td><td><strong>Break</strong></td><td>–</td><td>–</td></tr>
 </table>

## Workshop Work

Lab 1 – Build Vector Store, Knowledge Graph & Assemble the Agentic System

- Need labs that will hydrate a vector store and knowledge graph with data from the use case.
 1) Get the Document Set
 2) Build an Index with AI Foundry

## Trouble Shooting
-- KeyBased Authentication not allowed to blob storage issue
-- Look in the connected resources for the hub and find the name of the storage account
-- Check the Firewall Under networking for the storage account

https://stccoulthrus461777698848.blob.core.windows.net/7a10966c-358b-46d9-a408-b0bcb710a37f-azureml-blobstore/azureml/64c67147-c41b-42c0-8009-6412e4f358a1/index/


## Objectives

To learn how to build an agentic system using the latest tools and technologies on Microsoft platforms. The workshop will be a combinations of presentation and hand on workshop. The goal is to provide the participants a firm grounding in the Microsoft Agentic Ecosystem to quickly create rapid of value prototypes for which will seamlessly transition to Enterprise grade agentic deployments. 

Key Sections of the Workshop will include:
1) Agents and Agentic Systems
2) Use Case Exploration and Ideation   
3) Crafting a User Experience
4) Build Agentic System Components
5) Assembling the Agentic System
6) Evaluating the Agentic Application

## Suggested Pre-Read Material

### HAX Toolkit
The HAX Toolkit is for teams building user-facing AI products. It helps you conceptualize what the AI system will do and how it will behave. Use it early in your design process.
https://www.microsoft.com/en-us/haxtoolkit/

### AutoGen:
https://microsoft.github.io/autogen/stable/user-guide/agentchat-user-guide/tutorial/index.html

### AI Search & Vector Store
Understand  Vector search and Embedding Models, and how they are used in the Microsoft AI Search and Vector Store. The goal is to understand how to use the tools to build agentic systems.

https://learn.microsoft.com/en-us/azure/search/vector-store
https://learn.microsoft.com/en-us/azure/search/vector-search-overview
https://learn.microsoft.com/en-us/azure/search/knowledge-store-concept-intro


### Copilot Studio
Low Code option for building agents and agentic systems, review the documentation to understand the capabilities available out of the box.

https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio

#### Agent M365 SDK
The Microsoft 365 Agents SDK is used to build self-hosted agents. It's a collection of libraries and tools that allow you to build an agent in code. The SDK facilitates communication between a client and one or more agents by handling the conversation between them. The SDK provides an easy path to incorporate Microsoft AI services, such as Graph, Azure OpenAI, and non-Microsoft AI services.
https://learn.microsoft.com/en-us/microsoft-365/agents-sdk/agents-sdk-overview

#### Teams Toolkit for Visual Studio
https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/teams-toolkit-fundamentals

### Semantic Kernel

A enterprise grade framework for building agents and agentic systems, review the documentation good to get a grounding in the code concepts, memory, tools and planners. The goal is to understand how to use the tools to build agentic systems.
    https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio

#### Semantic Kernel Agent Framework:
    https://learn.microsoft.com/en-us/semantic-kernel/frameworks/agent/?pivots=programming-language-python

#### Semantic Process Framework:
    https://learn.microsoft.com/en-us/semantic-kernel/frameworks/process/process-framework


### AI Foundry 
Understand the core components of the Azure AI Foundry.
https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry

- [Model Catalog](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/model-catalog-overview)
- [Responsible AI](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-use-of-ai-overview)
- [Evaluations](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-approach-gen-ai)
- [Tracing](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/trace)
- [Azure AI Agent Service](https://learn.microsoft.com/en-us/azure/ai-services/agents/overview)

#### AI Templates
https://azure.github.io/awesome-azd/


#### AI Foundry VS Code Extension
https://devblogs.microsoft.com/foundry/azure-ai-foundry-vscode-extension-preview/

https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/trace

#### Azure AI Model Inference 
https://devblogs.microsoft.com/dotnet/azure-ai-model-catalog-dotnet-inference-sdk/


### Use Cases
https://github.com/Azure-Samples/graphrag-legalcases-postgres/tree/main

https://github.com/Azure-Samples/aisearch-openai-rag-audio

### The Cutting Edge
https://devblogs.microsoft.com/foundry/semantic-kernel-a2a-integration/

https://devblogs.microsoft.com/foundry/get-started-azure-openai-advanced-audio-models/

https://devblogs.microsoft.com/foundry/integrating-azure-ai-agents-mcp-typescript/


https://devblogs.microsoft.com/foundry/evaluation-metrics-azure-ai-foundry/

https://devblogs.microsoft.com/foundry/ai-red-teaming-agent-preview/

https://devblogs.microsoft.com/foundry/azure-ai-mem0-integration/

https://devblogs.microsoft.com/foundry/
welcome-to-azure-ai-foundry-blog/

### Data
https://blog.fabric.microsoft.com/en-US/blog/playbook-for-metadata-driven-lakehouse-implementation-in-microsoft-fabric/


https://learn.microsoft.com/en-us/microsoft-copilot-studio/advanced-generative-actions#how-does-generative-orchestration-work

https://akasearch.net/


https://cohere.com/blog?utm_campaign=Cohere%20Newsletter&utm_medium=email&_hsenc=p2ANqtz-8F6cpSSHMeHCIw7DjOVMkkBMtY1plpPUgx-072tMy40H3xvPBxeDMQ_8va0GG_xfjbJ6x_vZFQ4ZE7csqP1uNq20zK7h1XEdqZHpF_pxBxqmMlMQ8&_hsmi=359199602&utm_content=359199602&utm_source=hs_email


https://github.com/microsoft/deepRAG/blob/main/docs/ARCHITECTURE.md

# Lab Materials

Distillation
https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/concept-model-distillation

## Tracing

Open Telemetry 
https://opentelemetry.io/docs/specs/semconv/gen-ai/


##APIM Gateways

https://github.com/Azure-Samples/AI-Gateway?tab=readme-ov-file



## Labs with Agents
https://github.com/Azure-Samples/AI-Gateway?tab=readme-ov-file#-labs-with-ai-agents


## Reference Architectures
https://github.com/microsoft/azure-genai-design-patterns/tree/main
