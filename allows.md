Act as a Senior Java Production Support Engineer and AI Solution Architect.

Build an AI-powered Log Analyzer for our Java Spring Boot applications running on Azure Kubernetes Service (AKS).

Requirements:

1. Accept application logs in TXT, JSON and multiline stack trace formats.
2. Identify exceptions, warnings, recurring errors and abnormal patterns.
3. Group similar exceptions and calculate their frequency.
4. Identify the first failure in a sequence of related errors.
5. Detect possible database connectivity, timeout, memory and thread-pool issues.
6. Identify affected Java classes, methods and API endpoints wherever possible.
7. Generate a root-cause hypothesis with supporting log evidence.
8. Recommend actionable debugging steps and possible code fixes.
9. Support large log files through streaming or chunk processing.
10. Never expose passwords, tokens, customer data or other sensitive information.

Technical requirements:

- Java 17+
- Spring Boot
- Modular architecture
- REST API
- Configurable log parsers
- Unit tests using JUnit 5 and Mockito
- Docker support

First inspect the repository and propose the architecture.
Then implement the solution incrementally.

Do not invent root causes. Clearly distinguish confirmed findings from hypotheses.
