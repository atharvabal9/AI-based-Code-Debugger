#AI Based Code Debugger

AI Based Code Debugger is a Spring Boot library that enhances your debugging workflow by automatically explaining exceptions and providing actionable solutions using AI, powered by the GroqCloud API. It’s designed to save developers time by making error messages more understandable and accessible in multiple languages.

Features

Automatic Error Explanation – Captures exceptions thrown in your Spring Boot application and generates detailed, human-readable explanations.

Multi-Language Support – Understand errors in your preferred language, enabling teams across different regions to debug faster.

Drop-in Integration – Easily integrate into any existing Spring Boot project without major code changes.

Requirements

Java: 21 or higher

Build Tool: Maven

Framework: Spring Boot 3.3.0 or higher

Once integrated, the library intercepts exceptions from your controllers, sends the error details to the AI model, and returns a structured JSON response with explanations, causes, and possible solutions.
