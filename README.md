# Awesome Spring AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources, tools, tutorials, and projects for building generative AI applications using Spring AI. This repository aims to help developers leverage the power of Large Language Models (LLMs) within the Spring ecosystem.

## Contents

- [What is Spring AI?](#what-is-spring-ai)
- [Official Resources](#official-resources)
    - [Documentation](#documentation)
    - [Spring AI Blogs](#spring-ai-blogs)
- [Learning Resources](#learning-resources)
    - [Books](#books)
    - [Articles](#articles)
    - [Online Training](#online-training)
        - [Udemy Courses](#udemy-courses)
    - [YouTube](#youtube)
        - [Channels](#channels)
        - [Talks & Videos](#talks--videos)
        - [General Playlists](#general-playlists)
    - [Podcasts](#podcasts)
    - [Workshops](#workshops)
- [Non-English Resources](#non-english-resources)
    - [Articles (Other Languages)](#articles-other-languages)
    - [Videos (Other Languages)](#videos-other-languages)
- [Code & Examples](#code--examples)
    - [Comprehensive Example Collections](#comprehensive-example-collections)
    - [Code Examples](#code-examples)
    - [UI Clients](#ui-clients)
    - [CLI Applications](#cli-applications)
    - [Extensions and Forks](#extensions-and-forks)
    - [Development Tools](#development-tools)
    - [Model Context Protocol](#model-context-protocol)
        - [Core Resources](#core-resources)
        - [MCP Servers for Spring Projects](#mcp-servers-for-spring-projects)
        - [Domain-Specific MCP Implementations](#domain-specific-mcp-implementations)
- [Community](#community)
    - [Who to Follow](#who-to-follow)
- [Tools & Performance](#tools--performance)
    - [Benchmarks](#benchmarks)
- [Contributing](#contributing)

## What is Spring AI?

Spring AI is a project from the Spring team that provides a familiar and consistent Spring-style developer experience for building AI applications. It simplifies the integration of Large Language Models and other AI capabilities into Spring applications, offering:

- Consistent abstractions across different AI providers
- Support for popular LLM providers
- Robust prompt engineering capabilities
- Built-in caching and retry mechanisms
- Vectorized storage integration
- Streaming responses
- Customizable model parameters
- Native Spring Boot integration

## Official Resources

### Documentation

- [Spring AI Project](https://spring.io/projects/spring-ai)
- [Spring AI Reference Documentation](https://docs.spring.io/spring-ai/reference/)
- [Spring AI API Documentation](https://docs.spring.io/spring-ai/docs/1.0.0-SNAPSHOT/api/)

### Spring AI Blogs

- [Your First Spring AI 1.0 Application](https://spring.io/blog/2025/05/20/your-first-spring-ai-1) - Complete tutorial building a production-ready dog adoption service with RAG, MCP, vector stores, and PostgreSQL (May 2025)
- [Repository Vector Search Methods](https://spring.io/blog/2025/05/23/vector-search-methods) - Technical guide on implementing vector search with Spring Data 3.5, covering Vector type, SearchResults, and search methods (May 2025)
- [MCP Authorization in Practice with Spring AI and OAuth2](https://spring.io/blog/2025/05/19/spring-ai-mcp-client-oauth2) - Implementation of the revised MCP spec: securing Spring AI MCP servers and clients with an external OAuth2 Authorization Server (May 2025)
- [Dynamic Tool Updates in Spring AI's Model Context Protocol](https://spring.io/blog/2025/05/04/spring-ai-dynamic-tool-updates-with-mcp) - How to dynamically update tools available to AI assistants using Spring AI's MCP implementation (May 2025)
- [Using Spring AI 1.0.0-SNAPSHOT: Part 2 – Important Changes and Updates](https://spring.io/blog/2025/04/04/spring-ai-using-snapshots-part-2) - Continuation of the snapshot series, detailing Spring AI's module restructuring, new artifact IDs, and migration steps for Spring AI 1.0.0-SNAPSHOT (April 2025)
- [Securing Spring AI MCP Servers with OAuth2](https://spring.io/blog/2025/04/02/mcp-server-oauth2) - How to add OAuth2 authentication to Spring AI's Model Context Protocol servers using Spring Security and Authorization Server (April 2025)
- [Spring AI Prompt Engineering Patterns](https://spring.io/blog/2025/04/14/spring-ai-prompt-engineering-patterns) - Best practices and patterns for effective prompt engineering in Spring AI applications (April 2025)
- [Spring AI with Docker Model Runner](https://spring.io/blog/2025/04/10/spring-ai-docker-model-runner) - Integration tutorial for using Docker Model Runner with Spring AI for local development (April 2025)
- [Building Effective Agents with Spring AI (Part 1)](https://spring.io/blog/2025/01/21/spring-ai-agentic-patterns) - Introduces five fundamental agentic patterns (Chain, Parallelization, Routing, Orchestrator-Workers, Evaluator-Optimizer) with implementations in Spring AI (January 2025)
- [Agentic AI is the future! Agentic AI is now!](https://spring.io/blog/2025/01/21/spring-ai-agentic-patterns) - Exploring agentic patterns in Spring AI for building autonomous AI systems (January 2025)
- [Leverage the Power of 45k, free, Hugging Face Models with Spring AI and Ollama](https://spring.io/blog/2024/10/22/leverage-the-power-of-45k-free-hugging-face-models-with-spring-ai-and-ollama)
- [Supercharging Your AI Applications with Spring AI Advisors](https://spring.io/blog/2024/10/02/supercharging-your-ai-applications-with-spring-ai-advisors)
- [Spring AI with NVIDIA LLM API](https://spring.io/blog/2024/08/20/spring-ai-with-nvidia-llm-api)
- [Spring AI Embraces OpenAI's Structured Outputs: Enhancing JSON Response Reliability](https://spring.io/blog/2024/08/09/spring-ai-embraces-openais-structured-outputs-enhancing-json-response)
- [Spring AI with Groq - a blazingly fast AI inference engine](https://spring.io/blog/2024/07/31/spring-ai-with-groq-a-blazingly-fast-ai-inference-engine)
- [Spring AI with Ollama Tool Support](https://spring.io/blog/2024/07/26/spring-ai-with-ollama-tool-support)
- [Spring AI - Structured Output](https://spring.io/blog/2024/05/09/spring-ai-structured-output)
- [Spring AI - Multimodality - Orbis Sensualium Pictus](https://spring.io/blog/2024/04/19/spring-ai-multimodality-orbis-sensualium-pictus)
- [Function Calling in Java and Spring AI using the latest Mistral AI API](https://spring.io/blog/2024/03/06/function-calling-in-java-and-spring-ai-using-the-latest-mistral-ai-api)
- [AI Meets Spring Petclinic: Implementing an AI Assistant with Spring AI (Part I)](https://spring.io/blog/2024/09/26/ai-meets-spring-petclinic-implementing-an-ai-assistant-with-spring-ai-part-i)
- [AI Meets Spring Petclinic: Implementing an AI Assistant with Spring AI (Part II)](https://spring.io/blog/2024/09/27/ai-meets-spring-petclinic-implementing-an-ai-assistant-with-spring-ai-part)
- [Spring Pet Klinik - Kotlin](https://github.com/sdeleuze/spring-petklinik)

## Learning Resources

### Books

- ["Spring AI in Action" by Craig Walls (Manning)](https://www.manning.com/books/spring-ai-in-action)
- ["Spring AI for Your Organization - GCP Vertex AI Edition" by Muthukumaran Navaneethakrishnan (Leanpub)](https://leanpub.com/springai)
- ["Beginning Spring AI" by Andrew Lombardi and Joseph Ottinger](https://www.wecodefire.com/p/beginning-spring-ai-released)

### Articles

- [Building AI-Native APIs with Spring AI and Model Context Protocol](https://www.thedavestack.com/spring-ai-mcp/) - Practical guide to implementing MCP servers in Spring Boot applications, introducing the "dual API paradigm" for AI integration with existing services using tools, resources, and prompts (September 2025)
- [Creating Private AI Applications with Spring AI and GPT OSS](https://ik.am/entries/867/en) - Comprehensive tutorial demonstrating Spring AI integration with local gpt-oss:20b model using Ollama, featuring RAG, chat memory, structured output, and building an immigration advisor chatbot (September 2025)
- [Mastering Spring AI: Easily Add LLM Smarts to Your Spring Boot Applications](https://mobisoftinfotech.com/resources/blog/mastering-spring-ai/) - Demonstrates swapping between GPT-4 and Gemini with Spring AI configuration; highlights avoiding vendor lock-in (August 2025)
- [Spring AI Concepts Tutorial With Examples](https://javatechonline.com/spring-ai-concepts-tutorial/) - Updated guide for Spring AI 1.0 GA: concepts (models, prompts, embeddings), ChatModel/ChatClient, advisors, and chatbot example (March 2025, updated August 2025)
- [Agentic AI through Spring AI: Basic Examples](https://medium.com/@amritshankardutta/agentic-ai-through-spring-ai-basic-examples-xxx) - Introduces minimal implementations of agent-based AI patterns in Spring AI, covering vector DB, conversation memory, tool calling, RAG, structured outputs, guardrails, and metrics (June 2025)
- [From Docs to Dialogue: Building a Production-Ready AI Assistant with Spring Boot and Milvus](https://milvus.io/blog/docs-to-dialogue-spring-ai-milvus.md) - Step-by-step tutorial creating a Spring Boot + Spring AI app that uses Milvus for RAG with ChatClient abstraction (June 2025)
- [Building Effective AI Agents with Spring Boot](https://medium.com/@arfatbinkileb/building-effective-ai-agents-with-spring-boot-xxx) - Deep-dive into agent architectures (chaining, parallelization, orchestration) implemented with Spring AI, includes GitHub repo (May 2025)
- **Spring AI with Amazon Bedrock Series by Vadym Kazulkin** - Four-part comprehensive series by AWS Serverless Hero exploring Spring AI integration with Amazon Bedrock and Model Context Protocol implementations:
  - [Part 1: Introduction and the Sample Application](https://dev.to/aws-heroes/spring-ai-with-amazon-bedrock-part-1-introduction-and-the-sample-application-4hof) - Introduction to Spring AI with Amazon Bedrock featuring a conference search application with tools and chat memory (August 2024)
  - [Part 2: Exploring Model Context Protocol STDIO Transport](https://dev.to/aws-heroes/spring-ai-with-amazon-bedrock-part-2-exploring-model-context-protocol-stdio-transport-3o89) - Implementation of MCP server using STDIO transport with tool discovery and natural language interactions (August 2024)
  - [Part 3: Exploring Model Context Protocol SSE Transport](https://dev.to/aws-heroes/spring-ai-with-amazon-bedrock-part-3-exploring-model-context-protocol-sse-transport-48ah) - Demonstrates Server-Sent Events transport for Model Context Protocol with conference search tools (September 2024)
  - [Part 4: Exploring Model Context Protocol Streamable HTTP Transport](https://dev.to/aws-heroes/spring-ai-with-amazon-bedrock-part-4-exploring-model-context-protocol-streamable-http-transport-2o5h) - Final part exploring MCP server implementation using Streamable HTTP transport protocol (September 2024)
- [Understanding Tool/Function Calling in LLMs (Step-by-Step Examples in REST and Spring AI](https://muthuishere.medium.com/understanding-tool-function-calling-in-llms-step-by-step-examples-in-rest-and-spring-ai-2149ecd6b18b) - Learn how to implement OpenAI-style tool calling — from raw REST to elegant Spring AI annotations (July 2025)
- [Semantic search with embeddings in Spring & Kotlin](https://medium.com/p/83e2c2f3406f) - Comprehensive guide to the use of embeddings in Spring AI (April 2025)
- [Spring AI in Java Applications](https://medium.com/@alxkm/power-of-ai-in-java-applications-with-spring-ai-eed97c8408b2) - Vision for enterprise AI integration with Spring (March 2025)
- [Configuring MCP-Client SSE using Spring AI](https://medium.com/@shaamamanoharan/configuring-mcp-client-sse-in-spring-boot-fb07371c35a7) - Technical guide for configuring Server-Sent Events with MCP clients (February 2025)
- [Spring AI: A Beginner's Guide (Part 1)](https://medium.com/@kushparsaniya/spring-ai-a-beginners-guide-part-1-8a0ef9c52f21) & [Part 2](https://medium.com/@kushparsaniya/spring-ai-a-beginners-guide-part-2-dff1f353650b) - Multi-part walkthrough of Spring AI fundamentals. Part 1 covers integrating chat models (OpenAI/Ollama) in Spring Boot; Part 2 dives into the Advisor API (December 2024)
- [Why Spring AI: The Seamless Path to Generative AI](https://spring.io/blog/2024/11/19/why-spring-ai) - Article explaining the benefits of Spring AI and why you may consider it in favour of other AI frameworks (November 2024)
- [Building a Generative AI Application with Spring AI](https://medium.com/@clemsonbradley/building-a-generative-ai-application-with-spring-ai-d58e02a5f1f) - Project-based learning walkthrough for building a complete Spring AI application (November 2024)
- [Spring Boot Meets AI](https://medium.com/@vermaswati3/how-ai-can-be-integrated-into-a-spring-boot-application-spring-ai-f9795c98f099) - Practical guide to using OpenAI & Anthropic in a diet-planner application (October 2024)
- [Getting Started with Spring AI (Java Code Geeks)](https://www.javacodegeeks.com/2024/09/getting-started-with-spring-ai.html) - Simple introduction to Spring AI for Java developers (September 2024)
- [Getting Started with Spring AI](https://medium.com/@arvindcoder/getting-started-with-spring-ai-c5a630b1d7c2) - Introduction to Spring AI's core components and model abstractions (August 2024)
- [How to Write GenAI Applications with Java (Foojay.io)](https://foojay.io/today/spring-ai-generative-ai-java/) - Comprehensive guide covering RAG and Spring AI templates (July 2024)

### Online Training

### Udemy Courses

- [From Java Dev to AI Engineer: Spring AI Fast Track](https://www.udemy.com/course/java-spring-ai/) - Build AI Apps with Spring AI, OpenAI, RAG, MCP, AI Testing, Observability, Speech & Image Generation by Madan Reddy & Eazy Bytes (2024)
- [Build AI Apps with Spring AI, OpenAI, Ollama & SpringBoot](https://www.udemy.com/course/build-ai-apps-with-spring-ai-openai-springboot/) - Learn chat with LLMs, Retrieval-Augmented Generation, tool calling, and multimodal AI using Spring AI (August 2024)
- [Spring AI - GenAI with Telusko](https://www.udemy.com/course/spring-ai-genai/) - Build AI-powered Spring Boot applications using SpringAI with OpenAI, Ollama, RAG, vector databases, with multimodal capability by Navin Reddy (2024)
- [Master Generative AI with Java and Spring Boot | Spring AI](https://www.udemy.com/course/gen-ai-spring/) - Use Java and Spring to build Artificial Intelligence driven applications and lifecycle management by Shabbir Dawoodi (2024)
- [In-Depth: Developing Generative AI Applications with Spring](https://www.udemy.com/course/in-depth-developing-generative-ai-applications-with-spring/) - Mastering Spring AI and Advanced Generative AI Technologies by Ken Krueger (2024)
- [Build AI Customer Support with Spring AI and React](https://www.udemy.com/course/build-modern-ai-powered-web-apps-with-spring-ai-and-react/) - Build a Professional AI Customer Support System using Spring AI, Spring Boot, and React by Samson Alfred (2024)
- [Spring AI: Creating Workflows, Agents and Parsing data](https://www.udemy.com/course/spring-ai-creating-workflows-agents-and-parsing-data/) - Creating intelligent workflows, autonomous agents, and advanced data parsing by Verissimo Ribeiro (2024)
- [Spring AI: From AI Fundamentals to Spring AI Insights](https://www.udemy.com/course/spring-ai-insights/) - Use Java to Harness the Power of Spring AI with OpenAI by Uladzislau Zhurauliou (2024)
- [Spring AI: Beginner to Guru](https://www.udemy.com/course/spring-ai-beginner-to-guru/) - Use Java to Unlock the Power of OpenAI's ChatGPT with Spring AI by John Thompson (2024)
- [Mastering Spring AI: Build AI with Java](https://www.udemy.com/course/mastering-spring-ai-build-ai-with-java/) - Harness the Power of AI to Transform Your Java Applications by Pritesh Mistry (2024)
- [Spring AI for Beginners: Build GenAI & LLM Apps](https://www.udemy.com/course/spring-ai-for-beginners-build-genai-llm-apps-in-easy-steps/) - Step-by-Step Guide to Master Spring AI by Bharath Thippireddy (2024)
- [Spring AI with Neo4j: Knowledge Graph RAG](https://www.udemy.com/course/java-spring-ai-neo4j-openai-knowledge-graph-rag/) - RAG (Retrieval Augmented Generation) with Vector Similarity and Knowledge Graph using Spring AI, Neo4J, and OpenAI by Timotius Pamungkas (2024)


#### Talks & Videos
- [Practical Agentic RAG with Spring AI in Modern Enterprise Apps • Dan Dobrin @ Spring I/O 2025](https://www.youtube.com/watch?v=l4Azzw1e0ns) - Enterprise-focused agentic RAG implementation with Spring AI (May 2025)
- [The State of the Art of Spring AI • Josh Long • GOTO 2025](https://www.youtube.com/watch?v=9mOuvrZtLbc) - Comprehensive overview of Spring AI's current state, advances, roadmap, and capabilities as of mid-2025 (May 2025)
- [Code Smarter, Not Harder: AI-Powered Dev Hacks for All • Dan Vega @ Spring I/O 2025](https://www.youtube.com/watch?v=xxxx) - Practical AI dev hacks for Spring apps, demonstrating productivity boosts with Spring AI (May 2025)
- [Modular RAG Architectures with Java and Spring AI by Thomas Vitale @ Spring I/O 2025](https://www.youtube.com/watch?v=yQQEnXRMvUA) - Practical guide to building Retrieval-Augmented Generation architectures using Java and Spring AI (May 2025)
- [Codepocalypse Now: LangChain4j vs. Spring AI | J-Spring 2025](https://www.youtube.com/watch?v=w35WrPfZYxA) - Comparison between Spring AI and LangChain4j frameworks, exploring trade-offs and use cases (May 2025)
- [Using OpenRouter in Java Spring AI](https://www.youtube.com/watch?v=IyenmAPe3us) - One API for multiple AI model providers with Spring AI integration (May 2025)
- [Spring AI & Cloud Foundry: Bootiful, Agentic, Production](https://www.youtube.com/watch?v=mBMq2BqfjyA) - Productionizing Spring AI applications on Cloud Foundry platform (April 2025)
- [From Single-Shot LLMs to Intelligent Agents](https://www.youtube.com/watch?v=l38CPjOYsHk) - Building intelligent agents with Spring AI framework (April 2025)
- [Spring AI Tutorial — Advisors](https://www.youtube.com/watch?v=k5tsu3Aos8k) - Deep dive into Advisors in Spring AI (April 2025)
- [Spring AI Tutorial — Model Context Protocol (MCP)](https://www.youtube.com/watch?v=z9H-qgbJNHI) - Using Model Context Protocol with Spring AI (April 2025)
- [AI for Java Developers: Full Course / Workshop on Getting Started with Spring AI](https://www.youtube.com/watch?v=FzLABAppJfM) - Comprehensive workshop covering Spring AI fundamentals for Java developers (June 2025)
- [Breaking News: Spring AI Going GA in May 2025! 1.0.0-M7](https://www.youtube.com/watch?v=7ZqCwbc-EUk) - Announcement of Spring AI reaching general availability milestone with production-ready features (May 2025)
- [Spring AI Tutorial: Integrate ChatGPT with Spring Boot & OpenAI](https://www.youtube.com/watch?v=wExWF6VtN2E) - Practical tutorial on integrating ChatGPT with Spring Boot applications (May 2025)
- [Integrate AI into Your Enterprise in Minutes with Spring AI](https://www.youtube.com/watch?v=jIAP7e8ju-M) - Quick guide to enterprise AI integration using Spring AI (April 2025)
- [Prompt Engineering with Spring AI • Josh Long on Christian Tzolov's Review](https://www.youtube.com/shorts/B1dan9IWph0) - April 2025
- [Spring AI Deep Dive • Mark Pollack & Josh Long @ Devnexus](https://youtu.be/uPWebxgEwlE?si=JprirPQzuQdefyRe) - April 2025
- [#1 Spring AI Tutorial | Introduction](https://www.youtube.com/watch?v=4nBG848oArI) - Introductory tutorial covering Spring AI basics and setup (March 2025)
- [MCP, it's easy as ABC...](https://www.youtube.com/watch?v=cE1h-rC2o2U) - Model Context Protocol introduction and basics (March 2025)
- [Bootiful Spring AI](https://www.youtube.com/watch?v=uPWebxgEwlE) - Thanks to Devnexus for permission to represent this video (March 2025)
- [What's New in Spring AI M4 • Josh Long](https://www.youtube.com/watch?v=6fYjOTVTvOc) - February 2025
- [Intelligent Applications with Spring AI • Patrick Baumgartner @ JFokus 2025](https://www.youtube.com/watch?v=NBa2nuxqEJw) - February 2025
- [Spring Boot and Vaadin with Spring AI MCP • Marcus Hellberg](https://twitter.com/marcushellberg/status/1886678718200078609) - February 2025
- [Spring AI Course • freeCodeCamp](https://www.youtube.com/watch?v=9Crrhz0pm8s) - December 2024
- [Building Agents with AWS: Complete Tutorial • Josh Long & James Ward](https://www.youtube.com/watch?v=Y291afdLroQ) - November 2024
- [Spring AI Introduction: Building AI Applications in Java with Spring](https://www.youtube.com/watch?v=yyvjT0v3lpY) - Introduction to building AI-powered Java applications using Spring AI framework (April 2024)
- [Concerto for Java and AI - Building Production-Ready LLM Apps • Spring I/O 2024](https://www.youtube.com/watch?v=3zTf8NxF-6o) - Production-ready LLM applications using Spring AI examples and patterns (May 2024)
- [Building & Monetizing Generative AI Plugins with Spring AI • SpringOne 2024](https://www.youtube.com/watch?v=UmeoLny4nSk) - Creating and monetizing AI plugins using Spring AI framework (September 2024)
- [Supercharging your AI Applications with Spring AI Advisors • Spring Team](https://spring.io/blog/2024/10/02/supercharging-your-ai-applications-with-spring-ai-advisors) - October 2024
- [Spring AI Is All You Need • Christian Tzolov • GOTO Amsterdam 2024](https://www.youtube.com/watch?v=vuhMti8B5H0) - June 2024
- [Practical GenAI with Spring AI • Rod Johnson @ YOW! 2024](https://www.youtube.com/watch?v=4oaK3rKHiqs) - June 2024
- [Introducing Spring AI by Christian Tzolov / Mark Pollack @ Spring I/O 2024](https://www.youtube.com/watch?v=umKbaXsiCOY) - May 2024
- [Bringing GenAI to the Modern Enterprise. A production use-case. In Serverless Java !! • Dan Dobrin • Devoxx Belgium 2024](https://devoxx.be/talk/?id=8188) - May 2024
- [Bootiful Spring Boot • Josh Long @ SpringOne 2024](https://www.youtube.com/watch?v=ex7rnzIMmlk) - January 2024
- [Bootiful Artificial Intelligence • Josh Long, Mark Pollack & Rod Johnson @ SpringOne 2024](https://www.youtube.com/watch?v=N4ptoEo5gxY) - January 2024
- [Spring AI: Seamlessly Integrating AI into Your Enterprise Java Applications](https://youtu.be/kfRyY0wsZHM?si=qzIshk0GJqVTyrNm) - December 2023
- [Overview of Spring AI @ Devoxx 2023](https://www.youtube.com/watch?v=7OY9fKVxAFQ) - November 2023
- [Spring Tips: Spring AI](https://www.youtube.com/watch?v=aNKDoiOUo9M) - October 2023
- [Introducing Spring AI • Add Generative AI to your Spring Applications](https://www.youtube.com/watch?v=1g_wuincUdU) - October 2023
- [Spring AI at Spring.IO Keynotes](https://youtu.be/XUz4LKZx83g?t=2940) - October 2023

#### Office Hours & Community Livestreams

- [Spring Office Hours S4E25: Live from SpringOne @ Explore 2025](https://www.youtube.com/watch?v=xbZVg_r2Iho) - Spring community updates including Spring AI segments and updates (March 2025)
- [Spring Office Hours S4E17: Spring AI + Google Gemini: Beyond the Demo](https://www.youtube.com/watch?v=xbZVg_r2Iho) - Deep dive into Spring AI integration with Google Gemini models (February 2025)

#### General Playlists

- [Spring AI Tutorial - SivaLabs](https://www.youtube.com/watch?v=oP7tn_YfoOk&list=PLuNxlOYbv61hmSWcdM0rtoWT0qEjZMIhU) - Comprehensive Spring AI tutorial series covering fundamentals, integrations, and practical implementations (September 2025)
- [AI Native DevCon - Spring 2025](https://www.youtube.com/playlist?list=PLISstAySqk7Lt1qUF0qWS2F15qBNesyzU) - Conference playlist featuring Spring AI material and related AI-native development content (Spring 2025)
- [Craig Walls' Spring AI Playlist](https://www.youtube.com/watch?v=1g_wuincUdU&list=PLH5OU4wXVJc9aECkMUVPCi8g3pzs8pZ3E)
- [Dan Vega's Playlist](https://www.youtube.com/playlist?list=PLZV0a2jwt22uoDm3LNDFvN6i2cAVU_HTH)
- [Devoxx Playlist](https://www.youtube.com/@DevoxxForever)
- [Telusko Spring AI Tutorial Playlist](https://www.youtube.com/playlist?list=PLsyeobzWxl7qJSZcMaN18c5l-k2n1FWHx) - Comprehensive tutorial series covering Spring AI implementation with OpenAI, Anthropic, and Ollama integration
- [AI - Artificial Intelligence Playlist](https://www.youtube.com/playlist?list=PL41m5U3u3wwnzJMaMaSwKWa_CGyG3jY0X) - Collection of videos covering Spring AI and general artificial intelligence concepts and implementations

### Workshops

- [Spring AI Zero to Hero Workshop](https://github.com/asaikali/spring-ai-zero-to-hero) - Example applications showing how to use Spring AI to build Generative AI projects.
- (outdated) [Workshop material for Azure OpenAI](https://github.com/Azure-Samples/spring-ai-azure-workshop) - contains step-by-step examples from 'hello world' to 'retrieval augmented generation'
- [Gemini Workshop for Spring AI Java Developers • Dan Dobrin](https://github.com/ddobrin/gemini-workshop-for-spring-ai-java-developers) - workshop materials for the Java developer building Gen AI applications with Gemini models using Spring AI
- [Exploring interactions with LLMs : Practical insights with Spring AI](https://github.com/AxaFrance/spring-ai-workshop) - A self-paced workshop designed to practice Spring AI basics and discover interactions with LLMs.

## Non-English Resources

### Articles (Other Languages)

- ["Deep Learning" sobre Spring AI: primeros pasos](https://www.paradigmadigital.com/dev/deep-learning-spring-ai/) - Spanish introduction to Spring AI concepts and building a simple Spring Boot chatbot (May 2025)
- [Spring AI e Groq: Guia Completo para Criar um Assistente Inteligente](https://bilotta.dev/spring-ai-groq-tutorial) - Portuguese tutorial on using Spring AI with Groq, including prompt engineering with CATS framework (August 2025)
- [Spring AI入门教学：从零搭建智能应用（2025最新实践）](https://blog.csdn.net/liujibo520/article/details/137xxx) - Chinese guide to Spring AI, building a chatbot with Azure OpenAI, streaming responses, memory, multimodal support (March 2025)

### Videos (Other Languages)

- [2025年最新 Spring AI Alibaba 入门到进阶实战教程 (Bilibili Series)](https://www.bilibili.com/video/BVxxxx) - Chinese 54-part video course on Spring AI Alibaba, covering LLMs, RAG, function calling, and e-commerce chatbot building (June 2025)

## Code & Examples

### Comprehensive Example Collections

- [Spring AI Samples by Thomas Vitale](https://github.com/ThomasVitale/llm-apps-java-spring-ai) - Extensive collection of samples showing how to build Java applications powered by Generative AI and Large Language Models (LLMs). Includes examples for different AI models, RAG implementations, and various Spring AI features.

- [Spring AI Examples by Craig Walls](https://github.com/habuma/spring-ai-examples) - Comprehensive repository with dozens of examples covering all major Spring AI capabilities, model integrations, and implementation patterns. Created by the author of "Spring AI in Action".

- [Spring AI Showcase by Piotr Minkowski](https://github.com/piomin/spring-ai-showcase) - Modular demo project showcasing multiple Spring AI features including prompt templates, chat memory, structured output, function calling, RAG with Pinecone vector store, and image models. Supports multiple AI providers (OpenAI, Mistral, Ollama, Azure OpenAI) with profile-based configuration.

### Code Examples

- [Spring AI Official Examples](https://github.com/spring-projects/spring-ai-examples) - Comprehensive official repository containing examples for all Spring AI features including MCP dynamic tools, prompt engineering patterns, agentic workflows, vector stores, and various model integrations (2025)
- [Spring AI Docker Model Runner Example](https://github.com/eddumelendez/spring-ai-dmr) - Integration example showing how to use Docker Model Runner with Spring AI for local development and testing (2025)
- [Spring PetClinic AI](https://github.com/spring-petclinic/spring-petclinic-ai) - The classic Spring PetClinic application enhanced with a chatbot powered by Spring AI. Demonstrates natural language interaction with application data, allowing users to query and modify pet clinic information through conversation. Supports both OpenAI and Azure OpenAI as LLM providers. Detailed in a two-part blog series on spring.io.
- [Flight Booking Assistant](https://github.com/tzolov/playground-flight-booking) - Spring AI powered expert system demo that simulates a flight booking assistant. Demonstrates how to build domain-specific AI assistants using Spring AI.
- [Spring AI with QianFan](https://gitee.com/dino9527/spring-ai-examples.git) - Spring AI support for various AI language models from QianFan. Shows how to interact with QianFan language models and create a multilingual conversational assistant based on QianFan models.
- [Similarity Search using Spring AI](https://github.com/thecodemonkey/SimilaritySearch) - Implementation of a simple similarity search. Demonstrating how to use Kotlin or Java with Spring-AI to generate embeddings and perform simple similarity searches (March 2025)

### UI Clients

- [Spring AI HTMX MCP](https://github.com/habuma/spring-ai-examples/tree/main/spring-ai-htmx-mcp) - Example of building a modern, interactive UI for Spring AI applications using HTMX. Demonstrates how to create a responsive chat interface with minimal JavaScript by leveraging HTMX's server-side rendering capabilities combined with Spring AI's Model Context Protocol.

- [Spring AI Vaadin](https://github.com/spring-ai-community/spring-ai-vaadin) - Integration of Spring AI with Vaadin, a Java web framework for building modern web applications. Provides components and examples for creating rich, interactive AI-powered UIs with pure Java, without requiring JavaScript or HTML knowledge.

- [DocumentGPT](https://github.com/salmar/documentgpt-spring-ai) - A RAG-based document query system by Sergi Almar that allows users to upload documents and chat with them using Spring AI's vector search capabilities. Features a web-based user interface for document upload and interactive querying.

- [Spring AI Playground](https://github.com/JM-Lab/spring-ai-playground) - A web UI designed to make it easy for Java developers to experiment with and integrate AI models. Provides an interactive interface for testing different prompts and models.

### CLI Applications

- [Spring AI Chat Bot CLI](https://github.com/tzolov/spring-ai-cli-chatbot) - Command-line chatbot with Retrieval-Augmented Generation (RAG) and conversational memory capabilities. Demonstrates how to build interactive CLI applications with Spring AI.

- [Spring AI Powered Local CLI Chat Bot](https://github.com/JM-Lab/spring-ai-local-cli-chatbot) - A fully local, Spring AI-powered CLI chatbot that runs entirely on your machine with no external services required. Perfect for offline development or privacy-sensitive applications.

### Extensions and Forks

- [Spring AI Alibaba](https://github.com/alibaba/spring-ai-alibaba) - An extension of Spring AI that provides an agentic AI framework for Java developers. Adds support for Alibaba Cloud QWen models and Dashscope services, along with additional features like conversation memory, RAG support, and function calling. Maintains compatibility with the Spring AI API while offering specialized capabilities for Alibaba Cloud's AI ecosystem.

### Development Tools

- [Arconia Ollama Dev Service](https://arconia.io/docs/arconia/latest/dev-services/ollama/) - A Spring Boot development service that automatically manages Ollama instances for local LLM development. Simplifies testing and development with local models by handling container lifecycle and configuration. Integrates seamlessly with Spring AI's Ollama support.

### Model Context Protocol

#### Core Resources
- [MCP Client Documentation](https://docs.spring.io/spring-ai/reference/api/clients/mcp-client.html) - Official documentation for implementing the Model Context Protocol client in Spring AI applications.
- [MCP Client Examples](https://github.com/spring-projects/spring-ai-examples/tree/main/model-context-protocol) - Comprehensive examples showcasing the Model Context Protocol implementation in Spring AI, including client-server communication, tool discovery, filesystem operations, weather services, web search integration, and dynamic tool updates.
- [MCP Annotations](https://github.com/spring-ai-community/mcp-annotations) - Annotation-based programming model for implementing MCP servers and clients. Provides a clean, declarative approach to handling MCP operations with reduced boilerplate code. Includes core annotations that depend only on the MCP Java SDK and a Spring AI integration module.

#### MCP Servers for Spring Projects
- [Spring Batch MCP Server](https://github.com/fmbenhassine/spring-batch-lab/tree/main/sandbox/spring-batch-mcp-server) - An MCP service for introspecting Spring Batch applications, providing AI assistants with access to batch job information.
- [Spring Cloud Config MCP Server](https://github.com/ryanjbaxter/spring-cloud-config/tree/mcp-server) - An experimental MCP server implementation for Spring Cloud Config that exposes configuration management operations as AI tools, allowing AI assistants to retrieve, update, and refresh application configurations, as well as encrypt/decrypt sensitive values.
- [JVM Diagnostics MCP](https://github.com/brunoborges/jvm-diagnostics-mcp) - A Model Context Protocol service for obtaining JVM diagnostics, allowing AI assistants to access runtime information about Java applications.

#### Domain-Specific MCP Implementations
- [Kotlin Crypto Price MCP Server](https://github.com/gaplo917/kotlin-cyrpto-price-spring-mcp-server-demo) - A Kotlin-based Spring AI MCP server that provides real-time cryptocurrency price information from Binance.
- [Spring AI MCP Database Integration Example](https://github.com/anjeludo/spring-ai-mcp) - A practical implementation of MCP with Spring AI featuring two server applications exposing database operations (person and account data) via @Tool annotations and a client application that discovers and uses these tools with OpenAI models.
- [GitHub MCP Application](https://x.com/Stephan007/status/1910640447740838356) - A 100% Java GitHub MCP application built on Spring AI by Stephan Janssen, creator of Devoxx.
- [Druid MCP Server](https://github.com/iunera/druid-mcp-server) - A Java-based Enterprise MCP server for Apache Druid that provides extensive tools, resources, and AI-assisted prompts for managing and analyzing Druid clusters using spring-ai-1.1.0 Milestone with the new @Mcp Annotations (@McpTool) and Oauth
- [AWS Sample MCP Demos](https://github.com/aws-samples/Sample-Model-Context-Protocol-Demos) - Collection of examples showing how to use Model Context Protocol with AWS services, including Spring AI implementations.

## Community

### Who to Follow

- [Christian Tzolov](https://x.com/christzolov)
- [Josh Long](https://twitter.com/starbuxman)
- [Dan Vega](https://twitter.com/therealdanvega)
- [Thomas Vitale](https://twitter.com/ThomasVitale)
- [Dan Dobrin](https://x.com/ddobrin)
- [Marcus Hellberg](https://twitter.com/marcushellberg)
- Lize Roes
- [Bouke Nijhuis](https://twitter.com/boukenijhuis)
- [Guillaume Laforge](https://twitter.com/glaforge)
- [Brian Sam-Bodden](https://x.com/bsbodden)
- [Adib Saikali](https://x.com/asaikali)
- [Clémentine Fourrier](https://x.com/clefourrier)
- [Craig Walls](https://x.com/habuma)
- [Ilja Leyberman](https://www.linkedin.com/in/ilja-leyberman-3489aa1a1/)


## Podcasts

- [This Day in AI](https://thisday.in/ai)
- [Practical AI from Changelog](https://changelog.com/practicalai)
- [Latent Space](https://www.latent.space/)
- [Your Undivided Attention](https://www.humanetech.com/podcast)
- [TWIML (This Week in Machine Learning)](https://twimlai.com/)
- [Gradient Decent](https://gradientdescent.co/)
- [Spring Office Hours](https://www.youtube.com/@SpringSourceDev)
- [Bootiful Podcast](https://bootifulpodcast.fm/)

## YouTube

### Channels

- [The Neural Maze](https://www.youtube.com/channel/UCaixkLsW_TWWe_0yZNmvPaw)
- [The Turing Lectures (General AI)](https://www.turing.ac.uk/events/the-turing-lectures)
## Tools & Performance

### Benchmarks

- [OpenLLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)

## Contributing

Your contributions are always welcome! Please read the contribution guidelines first.
