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
    - [YouTube](#youtube)
        - [Channels](#channels)
        - [Talks & Videos](#talks--videos)
        - [General Playlists](#general-playlists)
    - [Podcasts](#podcasts)
    - [Workshops](#workshops)
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
        - [Other MCP example projects](#other-mcp-example-projects)
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

- [Dynamic Tool Updates in Spring AI's Model Context Protocol](https://spring.io/blog/2025/05/04/spring-ai-dynamic-tool-updates-with-mcp) - How to dynamically update tools available to AI assistants using Spring AI's MCP implementation
- [Spring AI Prompt Engineering Patterns](https://spring.io/blog/2025/04/14/spring-ai-prompt-engineering-patterns) - Best practices and patterns for effective prompt engineering in Spring AI applications
- [Agentic AI is the future! Agentic AI is now!](https://spring.io/blog/2025/01/21/spring-ai-agentic-patterns) - Exploring agentic patterns in Spring AI for building autonomous AI systems
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

- [Spring AI with Amazon Bedrock - Part 1: Introduction and Sample Application](https://dev.to/aws-heroes/spring-ai-with-amazon-bedrock-part-1-introduction-and-the-sample-application-4hof) - Tutorial demonstrating how to build a conference search application using Spring AI and Amazon Bedrock's Converse API, covering tool-based interaction with language models (August 2025)
- [Building Java AI Agents with Spring AI](https://aws-experience.com/emea/smb/e/90912/building-java-ai-agents-with-spring-ai) - Technical guide focused on creating intelligent software agents using Java programming and the Spring AI technology platform (2025)
- [Spring AI in Java Applications](https://medium.com/@oleksandr.klymenko/power-of-ai-in-java-applications-with-spring-ai-62bc2c2aa849) - Vision for enterprise AI integration with Spring (March 2025)
- [Configuring MCP-Client SSE using Spring AI](https://medium.com/@shaamamanoharan/configuring-mcp-client-sse-in-spring-boot-fb07371c35a7) - Technical guide for configuring Server-Sent Events with MCP clients (February 2025)
- [Spring AI: A Beginner's Guide (Part 1)](https://medium.com/@kushparsaniya/spring-ai-a-beginners-guide-part-1-8a0ef9c52f21) & [Part 2](https://medium.com/@kushparsaniya/spring-ai-a-beginners-guide-part-2-dff1f353650b) - Multi-part walkthrough of Spring AI fundamentals. Part 1 covers integrating chat models (OpenAI/Ollama) in Spring Boot; Part 2 dives into the Advisor API (December 2024)
- [Building a Generative AI Application with Spring AI](https://medium.com/@clemsonbradley/building-a-generative-ai-application-with-spring-ai-d58e02a5f1f) - Project-based learning walkthrough for building a complete Spring AI application (November 2024)
- [Spring Boot Meets AI](https://medium.com/@vermaswati3/how-ai-can-be-integrated-into-a-spring-boot-application-spring-ai-f9795c98f099) - Practical guide to using OpenAI & Anthropic in a diet-planner application (October 2024)
- [Getting Started with Spring AI (Java Code Geeks)](https://www.javacodegeeks.com/2024/09/getting-started-with-spring-ai.html) - Simple introduction to Spring AI for Java developers (September 2024)
- [Getting Started with Spring AI](https://medium.com/@arvindcoder/getting-started-with-spring-ai-c5a630b1d7c2) - Introduction to Spring AI's core components and model abstractions (August 2024)
- [How to Write GenAI Applications with Java (Foojay.io)](https://foojay.io/today/spring-ai-generative-ai-java/) - Comprehensive guide covering RAG and Spring AI templates (July 2024)
- [Spring AI 1.0 Brings AI to the Developer Masses (AWS)](https://community.aws/content/2xLkItwKHrZ5EweKTz9uPpYHyPk/spring-ai-1-0-brings-ai-to-the-developer-masses) - Overview of Spring AI 1.0 features and how it enables Java developers to build AI-powered applications. (May 2025)
- [Google Cloud and Spring AI 1.0](https://cloud.google.com/blog/topics/developers-practitioners/google-cloud-and-spring-ai-10) - Explains integration possibilities between Spring AI and Google Cloud services. (May 2025)
- [Spring AI and Elasticsearch as your vector database (Elastic)](https://www.elastic.co/search-labs/blog/spring-ai-elasticsearch-application) - How to use Elasticsearch as a vector database with Spring AI. (May 2025)
- [Build fast, production-worthy AI apps with Spring AI and Redis (Redis)](https://redis.io/blog/build-fast-production-worthy-ai-apps-with-spring-ai-and-redis/) - Guide to using Redis with Spring AI for scalable, production-ready AI applications. (May 2025)
- [Spring AI and MongoDB: How to Build RAG Applications (MongoDB)](https://dev.to/mongodb/how-to-build-rag-applications-with-spring-ai-and-mongodb-5gaj) - Tutorial on building Retrieval-Augmented Generation (RAG) apps with Spring AI and MongoDB. (May 2025)
- [Spring AI 1.0 GA released with Oracle Vector Database support (Oracle)](https://blogs.oracle.com/developers/post/spring-ai-10-ga-released-with-oracle-vector-database-support) - Announcement and technical overview of Oracle Vector Database support in Spring AI 1.0. (May 2025)
- [Spring AI 1.0 Released, Streamlines AI Application Development with Broad Model Support (InfoQ)](https://www.infoq.com/news/2025/05/spring-ai-1-0-streamlines-apps/) - News article summarizing the 1.0 release and its impact. (May 2025)
- [Production-Worthy AI With Spring AI 1.0 (The New Stack)](https://thenewstack.io/production-worthy-ai-with-spring-ai-1-0/) - Explores production use cases and architecture patterns enabled by Spring AI 1.0. (May 2025)
- [Building Intelligent Spring Boot Applications with Spring AI and MCP: A Complete Guide](https://medium.com/bliblidotcom-techblog/building-intelligent-spring-boot-applications-with-spring-ai-and-mcp-a-complete-guide-d77ae3785b1c) - Comprehensive guide to implementing MCP architecture with practical examples for building AI-powered enterprise applications (June 2025)
- [Building AI-Driven Applications With Spring AI](https://javapro.io/2025/04/22/building-ai-driven-applications-with-spring-ai/) - In-depth tutorial covering ChatClient API, structured output, advanced AI patterns including tool calling and RAG (April 2025)
- [Creating Your First Model Context Protocol (MCP) Server in Java](https://www.danvega.dev/blog/2025/03/26/creating-your-first-mcp-server-java) - Complete step-by-step tutorial on building MCP servers with Spring Boot and Spring AI (March 2025)
- [Using RAG and Vector Store with Spring AI](https://piotrminkowski.com/2025/02/24/using-rag-and-vector-store-with-spring-ai/) - Detailed tutorial on implementing Retrieval Augmented Generation (RAG) with Pinecone vector database (February 2025)
- [Integrating AI with Spring Boot: A Beginner's Guide](https://mydeveloperplanet.com/2025/01/08/integrating-ai-with-spring-boot-a-beginners-guide/) - Beginner-friendly tutorial covering chat responses, streaming, system messages, chat memory, and prompt templates (January 2025)
- [Spring AI: Integrating Artificial Intelligence into the Spring Ecosystem](https://medium.com/@agitrubard/spring-ai-integrating-artificial-intelligence-into-the-spring-ecosystem-5b10a2657ab8) - Comprehensive overview of Spring AI architecture, key features, use cases, and advantages (2025)
- [Integrating LLM into Java Applications with Spring AI — Chat Client API](https://medium.com/@johnidouglasmarangon/integrating-llm-into-java-applications-with-spring-ai-chat-client-api-21e0bacedced) - Comprehensive guide covering the Chat Client API, streaming responses, and structured output with practical examples (2025)

### Online Training

- [Spring AI: Beginner to Guru (Udemy)](https://www.udemy.com/course/spring-ai-beginner-to-guru/?couponCode=CP130525US) - Comprehensive course covering Spring AI fundamentals, integration with various LLM providers, prompt engineering, and building AI-powered applications
- [Mastering Spring AI: Build AI with Java (Udemy)](https://www.udemy.com/course/mastering-spring-ai-build-ai-with-java/?couponCode=CP130525US) - Advanced course focused on building production-ready AI applications with Spring AI and Java
- [Spring AI for Beginners: Build GenAI & LLM Apps (Udemy)](https://www.udemy.com/course/spring-ai-for-beginners-build-genai-llm-apps-in-easy-steps/?couponCode=CP130525US) - Step-by-step guide for beginners to create generative AI applications with Spring AI
- [Spring AI with Neo4j: Knowledge Graph RAG (Udemy)](https://www.udemy.com/course/java-spring-ai-neo4j-openai-knowledge-graph-rag/?couponCode=CP130525US) - Specialized course on implementing Knowledge Graph RAG (Retrieval Augmented Generation) using Spring AI and Neo4j graph database
- [Java Spring Boot AI Live Course](https://courses.telusko.com/learn/Java-Spring-Boot-AI-Live-Course) - A hands-on course covering Java, Spring Boot, and modern AI integration, including the use of AI coding assistants and prompt engineering. Starts July 20th, duration 5-6 months.
- [Build AI Apps with Spring AI, OpenAI, Ollama & SpringBoot)](https://www.udemy.com/course/build-ai-apps-with-spring-ai-openai-springboot/?couponCode=MT260825G2) - Are you ready to build AI-powered Java applications with real-world use cases? This hands-on course will teach you how to integrate cutting-edge AI capabilities into your Spring Boot applications using the Spring AI framework and OpenAI). 

#### Talks & Videos
- [MCP in Java Spring AI: Web Search + Selenium](https://www.youtube.com/watch?v=2QIXs5nlvAU) - Learn to enhance LLMs with external tools using Spring AI's Model Context Protocol, including web search with Brave Search MCP and browser automation with Selenium MCP. - June 2025
- [Getting Started with Spring AI by Simplilearn](https://www.youtube.com/watch?v=b_MMLZO_drM) - This video provides a deep dive into Spring AI, covering project setup with Spring Initializer, key components like ChatService.java, and real-world use cases. By the end, you'll have a solid understanding of how to integrate AI into your own applications. - June 2025
- [Spring AI MCP Client & Server with Ollama for your enterprise application with HTTP SSE](https://www.youtube.com/watch?v=chBd2Ls_4_Y) - This video provides an end-to-end guide on implementing a SEE Sync MCP using Ollama. It covers creating a basic chat client, configuring an enterprise application, and setting up a custom SSE Spring MCP server and client. - June 2025
- [MCP Weather API Tutorial](https://www.youtube.com/watch?v=C23FGvqhE6c) - This hands-on tutorial demonstrates how to turn a standard weather API into an intelligent AI tool using the Model Context Protocol (MCP). It breaks down Spring AI's MCP annotations and provides a step-by-step code walkthrough. - June 2025
- [MCP, it's easy as ABC...](https://www.youtube.com/watch?v=cE1h-rC2o2U) - February 2025
- [Bootiful Spring AI](https://www.youtube.com/watch?v=uPWebxgEwlE) - Thanks to Devnexus for permission to represent this video- March 2025
- [What's New in Spring AI M4 • Josh Long](https://www.youtube.com/watch?v=6fYjOTVTvOc) - February 2025
- [Intelligent Applications with Spring AI • Patrick Baumgartner @ JFokus 2025](https://www.youtube.com/watch?v=NBa2nuxqEJw) - February 2025
- [Spring Boot and Vaadin with Spring AI MCP • Marcus Hellberg](https://twitter.com/marcushellberg/status/1886678718200078609) - February 2025
- [Prompt Engineering with Spring AI • Josh Long on Christian Tzolov's Review](https://www.youtube.com/shorts/B1dan9IWph0) - April 2025
- [Spring AI Deep Dive • Mark Pollack & Josh Long @ Devnexus](https://youtu.be/uPWebxgEwlE?si=JprirPQzuQdefyRe) - April 2025
- [Spring AI Course • freeCodeCamp](https://www.youtube.com/watch?v=9Crrhz0pm8s) - December 2024
- [Building Agents with AWS: Complete Tutorial • Josh Long & James Ward](https://www.youtube.com/watch?v=Y291afdLroQ) - November 2024
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

#### General Playlists

- [Craig Walls' Spring AI Playlist](https://www.youtube.com/watch?v=1g_wuincUdU&list=PLH5OU4wXVJc9aECkMUVPCi8g3pzs8pZ3E)
- [Dan Vega's Playlist](https://www.youtube.com/playlist?list=PLZV0a2jwt22uoDm3LNDFvN6i2cAVU_HTH)
- [Devoxx Playlist](https://www.youtube.com/@DevoxxForever)
- [Telusko Spring AI Tutorial Playlist](https://www.youtube.com/playlist?list=PLsyeobzWxl7qJSZcMaN18c5l-k2n1FWHx) - Comprehensive tutorial series covering Spring AI implementation with OpenAI, Anthropic, and Ollama integration
- [AI - Artificial Intelligence Playlist](https://www.youtube.com/playlist?list=PL41m5U3u3wwnzJMaMaSwKWa_CGyG3jY0X) - Collection of videos covering Spring AI and general artificial intelligence concepts and implementations

### Workshops

- [Building Java AI Agents with Spring AI](https://catalog.workshops.aws/java-spring-ai-agents/en-US) - AWS workshop focused on building intelligent Java agents using Spring AI framework (August 2025)
- [Spring AI Zero to Hero Workshop](https://github.com/asaikali/spring-ai-zero-to-hero) - Example applications showing how to use Spring AI to build Generative AI projects.
- (outdated) [Workshop material for Azure OpenAI](https://github.com/Azure-Samples/spring-ai-azure-workshop) - contains step-by-step examples from 'hello world' to 'retrieval augmented generation'
- [Gemini Workshop for Spring AI Java Developers • Dan Dobrin](https://github.com/ddobrin/gemini-workshop-for-spring-ai-java-developers) - workshop materials for the Java developer building Gen AI applications with Gemini models using Spring AI
- [Exploring interactions with LLMs : Practical insights with Spring AI](https://github.com/AxaFrance/spring-ai-workshop) - A self-paced workshop designed to practice Spring AI basics and discover interactions with LLMs.


## Code & Examples

### Comprehensive Example Collections

- [Spring AI Samples by Thomas Vitale](https://github.com/ThomasVitale/llm-apps-java-spring-ai) - Extensive collection of samples showing how to build Java applications powered by Generative AI and Large Language Models (LLMs). Includes examples for different AI models, RAG implementations, and various Spring AI features.

- [Spring AI Examples by Craig Walls](https://github.com/habuma/spring-ai-examples) - Comprehensive repository with dozens of examples covering all major Spring AI capabilities, model integrations, and implementation patterns. Created by the author of "Spring AI in Action".

- [Spring AI Showcase by Piotr Minkowski](https://github.com/piomin/spring-ai-showcase) - Modular demo project showcasing multiple Spring AI features including prompt templates, chat memory, structured output, function calling, RAG with Pinecone vector store, and image models. Supports multiple AI providers (OpenAI, Mistral, Ollama, Azure OpenAI) with profile-based configuration.

### Code Examples

- [Spring PetClinic AI](https://github.com/spring-petclinic/spring-petclinic-ai) - The classic Spring PetClinic application enhanced with a chatbot powered by Spring AI. Demonstrates natural language interaction with application data, allowing users to query and modify pet clinic information through conversation. Supports both OpenAI and Azure OpenAI as LLM providers. Detailed in a two-part blog series on spring.io.

- [Flight Booking Assistant](https://github.com/tzolov/playground-flight-booking) - Spring AI powered expert system demo that simulates a flight booking assistant. Demonstrates how to build domain-specific AI assistants using Spring AI.

- [Spring AI with QianFan](https://gitee.com/dino9527/spring-ai-examples.git) - Spring AI support for various AI language models from QianFan. Shows how to interact with QianFan language models and create a multilingual conversational assistant based on QianFan models.

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

#### Domain-Specific MCP Implementations
- [Kotlin Crypto Price MCP Server](https://github.com/gaplo917/kotlin-cyrpto-price-spring-mcp-server-demo) - A Kotlin-based Spring AI MCP server that provides real-time cryptocurrency price information from Binance.
- [Spring AI MCP Database Integration Example](https://github.com/anjeludo/spring-ai-mcp) - A practical implementation of MCP with Spring AI featuring two server applications exposing database operations (person and account data) via @Tool annotations and a client application that discovers and uses these tools with OpenAI models.
- [GitHub MCP Application](https://x.com/Stephan007/status/1910640447740838356) - A 100% Java GitHub MCP application built on Spring AI by Stephan Janssen, creator of Devoxx.
- [AWS Sample MCP Demos](https://github.com/aws-samples/Sample-Model-Context-Protocol-Demos) - Collection of examples showing how to use Model Context Protocol with AWS services, including Spring AI implementations.

#### Other MCP example projects
- [Cloud Foundry MCP](https://github.com/cpage-pivotal/cloud-foundry-mcp) - Example of using Spring AI's Model Context Protocol (MCP) to build a conversational assistant for Cloud Foundry. Demonstrates how to create a domain-specific AI assistant that can help users with Cloud Foundry operations and troubleshooting.
- [Spring AI Recipe Finder MCP](https://github.com/timosalm/spring-ai-recipe-finder-mcp) - A recipe finder application built with Spring AI's Model Context Protocol. Demonstrates how to create a domain-specific assistant that can help users find recipes based on ingredients and preferences.
- [JVM Diagnostics MCP](https://github.com/brunoborges/jvm-diagnostics-mcp) - A Model Context Protocol service for obtaining JVM diagnostics, allowing AI assistants to access runtime information about Java applications.
- [MCP Time](https://github.com/alexandreroman/mcp-time/tree/main) - A unique MCP example demonstrating the use of MCP managed prompts rather than tools. Shows how to register and implement prompt templates that can be dynamically retrieved and used by MCP clients.
- [MCP Chess](https://github.com/alexandreroman/mcp-chess/blob/main/README.md) - An MCP server that provides chess functionality for AI assistants. Implements tools to generate chess board images from FEN notation, suggest next moves, and check if moves are legal. Built with Spring Boot and Spring AI.
- [MCP Location](https://github.com/alexandreroman/mcp-location/tree/main) - An MCP server that provides user location functionality through both tools and prompts. Features two implementation strategies: one using a network API to determine location from IP address, and another using a static configured location. Demonstrates the dual approach of offering both tool-based and prompt-based interfaces.


## Community

- [Spring AI Community](https://github.com/spring-ai-community) - Community-driven repository for sharing knowledge, examples, and resources related to Spring AI.

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
