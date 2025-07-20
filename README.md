# AI Architecture Model Overview Guide

This guide will provide an overview of the 7 layers of the AI Architecture Model.

#### Table of Contents

1. [Physical Layer](#physical)
2. [Data Link Layer](#data-link)
3. [Computation Layer](#computation)
4. [Knowledge Layer](#knowledge)
5. [Learning Layer](#learning)
6. [Representation Layer](#representation)
7. [Application Layer](#application)
8. [Supplemental Resources](#supplemental)

<hr />

## <a name="physical">1. Physical Layer</a>

* *Focus: Hardware and Infrastructure.*
* Provides a surface for AI models to run and process data, relying upon Tensor Processing Units (TPUs) and GPUs (e.g., AMD, NVIDIA).
  + Google is known for designing TPUs, with various partners assisting with the manufacturing of these units.
* This layer is responsible for high speed data processing, storage, and distributing AI data processing workloads.
* **Notable Uses:** On-premise AI servers, and popular cloud-based platforms (e.g., Amazon's AWS, Google Cloud, Microsoft Azure).

<hr />

## <a name="data-link">2. Data Link Layer</a>

* *Focus: Model Serving and API Integration.*
* Integrates apps with AI models using pipelines and API systems.
  + Enhances availability, scalability, and security of systems.
* Operates via model servicing (e.g., FastAPI, TensorFlow), MLOps, and AI orchestration (e.g., AutoGPT, LangChain) tools.
* **Notable Uses:** AI-embedded apps and Software-as-a-Service (SaaS) solutions.
  
<hr />

## <a name="computation">3. Computation Layer</a>

* *Focus: Processing and Logical Execution.*
* Responsible for logical execution and inference, as well as processing data in real-time.
  + Relies on GPUs and TPUs as AI accelerators, and utiizes edge AI and distributed computing processes. 
* Allows for usage of AI frameworks (e.g., JAX, PyTorch, TensorFlow).
* **Notable Uses:** AI models operating via a variety of setups (e.g., federated learning, on-cloud, on-device).

<hr />

## <a name="knowledge">4. Knowledge Layer</a>

* *Focus: External Data Retrieval and Reasoning Engine Operations.*
* Refines AI decision-making capabilities by consulting external data sources.
  + Consultation of big data improves reasoning, data retrieval, and fact checking capabilities.
* Relies upon vector searches, knowledge graphs, and Retrieval-Augmented Generation (RAG).
* **Notable Uses:** Large Language Model (LLM) code assistants (e.g., AskCodi, GitHub Copilot, Google Search, Ollama, Semantic Search).

<hr />

## <a name="learning">5. Learning Layer</a>

* *Focus: Model Training and Optimization.*

(TODO)

<hr />

## <a name="representation">6. Representation Layer</a>

* *Focus: Data Processing and Feature Engineering.*

(TODO)

<hr />

## <a name="application">7. Application Layer</a>

* *Focus: AI Interfaces and Deployment.*

(TODO)

<hr />

## <a name="supplemental">8. Supplemental Resources</a>

* *[eWeek Types of AI Models Article](https://www.eweek.com/artificial-intelligence/ai-model-types/)*
* *[Google Developers Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)*
* *[IBM 'What is an AI Model?' Article](https://www.ibm.com/think/topics/ai-model)*
  
<hr />
