# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: Real Estate Policy Assistant

Template path: templates/simple-rag/real-estate-policy-assistant

Short description:

A beginner-friendly RAG project for triaging education planning escalations

Architecture notes:

- The system will use a simple CRUD approach for data management, with a focus on scalability and maintainability.

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: The system will use a simple CRUD approach for data management, with a focus on scalability and maintainability.
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: User authentication and authorization; Escalation categorization and prioritization; Data storage and retrieval
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: User interface for escalation submission and tracking; Real-time categorization and prioritization display; User dashboard for escalation management
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: Unit testing, integration testing, and end-to-end testing using Pytest and Docker
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Escalation submission; Categorization and prioritization; Data storage and retrieval; User dashboard display
