# Privarcy-Ai-Companion
A privacy-focused generative AI assistant using Local LLMs, RAG, and MERN stack.

## Overview
A Generative AI assistant designed to prioritize user data privacy. Unlike cloud-based LLMs, this system executes inference locally or via secure private clouds, ensuring sensitive personal data never leaves the user's controlled environment.

## Key Features
-   **Local Inference:** Utilizes quantized models (Llama-3, Mistral) running on consumer hardware via Ollama.
-   **RAG (Retrieval-Augmented Generation):** Implements a knowledge retrieval pipeline using **Neo4j** (Graph Database) to provide context-aware answers without hallucination.
-   **Memory Management:** A sliding-window context memory system to retain conversation history efficiently.

## Tech Stack
-   **Frontend:** React.js, TailwindCSS
-   **Backend:** Node.js (Express), LangChain.js
-   **AI Engine:** Ollama (Local LLM), LangGraph
-   **Database:** Neo4j (Graph Storage), Pinecone (Vector Search)

## Research Focus
The primary goal is to benchmark the trade-off between **privacy preservation** and **inference latency** on edge devices.

## Current Status
-   [x] System Architecture & Privacy Protocol Design
-   [x] Local LLM Integration (Ollama)
-   [ ] Full-stack UI Implementation
