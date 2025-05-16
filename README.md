## Overview

**clockworKnowledge** is an open framework for building AI-augmented systems that help individuals and organizations structure, retrieve, and reason over their personal and shared knowledge. At its heart is the **Personal Knowledge Vault (PKV)**—a graph-native, AI-integrated platform that enables users to capture thoughts, documents, and experiences and explore them contextually through chat and search interfaces.

---

## Current Project: `menome-community`

The `menome-community` project serves as the foundation for the PKV system. It focuses on building and testing the **community and category infrastructure** required to semantically organize and retrieve knowledge across large collections of documents. Key features include:

* **Graph-based community detection** using cosine similarity and Leiden clustering.
* **Semantic indexing** of documents, questions, summaries, and notes.
* **Chat and search interface integration**, allowing questions to be answered in a contextualized and explainable way.
* **Knowledge Assets and Community Nodes** that act as persistent anchors for discovery and conversation.

This version serves as the sandbox for developing core GraphRAG patterns, working with embeddings, and shaping the UX architecture for chat- and graph-based exploration.

---

## Planned Expansion

The next phase of the project will build upon this foundation to support broader functionality and real-world deployments, including:

### ✅ Multi-Tenant Support (Basic)

* User and organization separation
* Secure user-level data partitioning
* Multi-session knowledge vaults

### ✅ Document Processing Pipeline

* OCR, text extraction, and semantic segmentation
* Embedding-based indexing and annotation
* Automatic topic and summary generation

### ✅ Simple Web UX

* Tailwind CSS + Next.js frontend
* Sidebar navigation with toggles for chat and browse modes
* Detail panels for interactive document and object exploration

### ✅ Capturing More Than Documents

* **Objects**: Support for physical or digital artifacts (e.g., artworks, field samples) with linked knowledge.
* **Memories**: Derived from chats, events, or past user interactions, timestamped and context-aware.

### ✅ Conversation-Derived Knowledge

* Background agents to extract and store insights, actions, and observations from chat
* Automated memory formation linked to documents and communities
* Support for future time-oriented queries ("Remind me what I said about X last week")

---

## Vision

The long-term goal is to create a **cognitively-aligned personal knowledge system**—a system that not only stores information but helps make sense of it. One that empowers users to organize their lives, work, and thinking as they evolve—supported by AI, grounded in context, and always under their control.


