# 🛒 Awesome Retail & Consumer Goods AI 🚀

A curated list of **AI + Azure** GitHub samples, tools, and accelerators for **Retail & Consumer Goods**. From customer service copilots to supply chain smarts, this repo highlights powerful ways to modernize and transform the industry using Microsoft AI technologies.

---

## 🧠 Featured Projects

## 🔍 AI Search & Chat with Your Data

#### 🔹 [azure-search-openai-demo](https://github.com/Azure-Samples/azure-search-openai-demo)  
**Use Case:** Personalized product Q&A, customer support chatbots, content discovery  
**Architecture Overview:**  
- Uses **Azure AI Search** to index retail documents or product catalogs  
- Embeds content via **Azure OpenAI embeddings**  
- User queries are enhanced with **RAG (Retrieval-Augmented Generation)**  
- Frontend app built with **React + TypeScript**  
- Backend is a **Python API** hosted on Azure Web Apps or Container Apps

---

#### 🔹 [chat-with-your-data-solution-accelerator](https://github.com/Azure-Samples/chat-with-your-data-solution-accelerator)  
**Use Case:** Multi-source customer service Copilot  
**Architecture Overview:**  
- Combines structured/unstructured data using **Azure AI Search + OpenAI**  
- Uses **Prompt Flow** to orchestrate query flow and LLM interactions  
- Deployable with **azd CLI** (Azure Developer CLI)  
- Includes monitoring, CI/CD, and deployment pipelines

---

#### 🔹 [azure-search-vector-samples](https://github.com/Azure/azure-search-vector-samples)  
**Use Case:** Semantic product search, knowledge base lookup  
**Architecture Overview:**  
- Demonstrates hybrid search (text + vector) using **Azure AI Search**  
- Embeddings created via **OpenAI or HuggingFace models**  
- Includes Python notebooks, REST APIs, and JavaScript examples  
- Great for integrating into web stores or retail portals

---

## 🧾 Intelligent Document Processing

#### 🔹 [azure-ai-document-processing-samples](https://github.com/Azure-Samples/azure-ai-document-processing-samples)  
**Use Case:** Invoice reading, receipt scanning, loyalty form automation  
**Architecture Overview:**  
- Uses **Azure AI Document Intelligence (Form Recognizer)** for extraction  
- Integrates with **OpenAI** to classify/explain content  
- Sample pipelines include **Logic Apps**, **Azure Functions**, and **Blob Triggers**  
- Outputs structured JSON ready for downstream workflows

---

## 👨‍💼 Storefront & Customer Experience

#### 🔹 [azure-ai-agent-service-enterprise-demo](https://github.com/Azure-Samples/azure-ai-agent-service-enterprise-demo)  
**Use Case:** AI assistant for store employees or customer self-service kiosks  
**Architecture Overview:**  
- Uses **Azure AI Agent Service** + **Bing Search** + internal content  
- GPT-4o powered responses with **streaming** capabilities  
- Fully containerized, deployable to **Azure Container Apps**  
- Authenticated via Azure Entra ID (AAD) with RBAC

---

#### 🔹 [get-started-with-ai-chat](https://github.com/Azure-Samples/get-started-with-ai-chat)  
**Use Case:** Add AI-powered chat into any website or portal  
**Architecture Overview:**  
- Simple front-end app using **HTML + JS + OpenAI**  
- Backend optional — can integrate with your own API  
- Great lightweight starting point for chat UIs

---

## 📦 Supply Chain & Operations

#### 🔹 [contoso-chat](https://github.com/Azure-Samples/contoso-chat)  
**Use Case:** Internal Copilot for supply chain management, inventory, logistics  
**Architecture Overview:**  
- Implements **multi-intent RAG** using Prompty and Azure AI  
- Uses **Azure AI Search** to pull internal documents (e.g., delivery SLAs)  
- Deployment automation via **GitHub Actions**  
- Built-in evaluation tools to improve prompt quality and results

---

## 📊 Data & Analytics

#### 🔹 [aistudio-end-to-end-baseline-architecture](https://github.com/Azure-Samples/aistudio-end-to-end-baseline-architecture)  
**Use Case:** Build a scalable AI retail analytics platform  
**Architecture Overview:**  
- Leverages **Microsoft Fabric** for data pipeline + Power BI for reporting  
- Integrates with **Azure OpenAI** and **AI Search**  
- Secure by default using **Azure Private Link**, **Managed Identity**, and **Bicep** templates  
- Ideal for companies needing repeatable, secure AI infra

---

## 🛠 Tech Stack

- **Azure OpenAI** (ChatGPT, GPT-4, Embeddings)  
- **Azure AI Search** (Semantic, Vector, Hybrid Search)  
- **Prompt Flow** + **Copilot Studio**  
- **Azure Functions**, **Static Web Apps**, **Bicep**  
- **Microsoft Fabric** + Power BI for analytics  
- **Azure AI Document Intelligence**, **Logic Apps**, **Blob Storage**

---

## 🧭 Use Cases

- Personalized shopping assistants (Copilot for customers)  
- Document intelligence (Receipts, Invoices, Claims)  
- Product recommendations & upsell engines  
- Employee training bots  
- **AI-powered product and content search**  
- RAG over product manuals, return policies, store ops guides  
- Sales forecasting using generative analytics  
- Real-time Q&A over enterprise data for store teams

---

## 🤝 Contribute

Got a sample, use case, or demo to add? [Open a PR](https://github.com/your-repo-name/pulls) and help grow the retail AI community!

---

## 📢 About

Built for solution architects, devs, and retail leaders transforming their tech stack with Azure AI.
