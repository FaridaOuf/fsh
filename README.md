# fsh
FSH Net: The Unified Student Life Market
🚀 Overview
FSH Net is a centralized "Market" for the NYUAD student experience. It solves the "Tab Apocalypse"—the extreme friction caused by fragmenting student life across four disconnected platforms:

Albert (SIS): Academic records & Bursar holds.

Brightspace (LMS): Coursework & deadlines.

Campus Services: Meal plan balances & Flex Dirhams.

Student Portal: Administrative tasks & ID management.

🧠 Project Logic: The Agentic Pipeline
FSH Net uses an Asynchronous Agentic Architecture to transform raw data into a prioritized survival guide:

Unified Ingestion: The app fetches a structured mock_student.json from a GitHub-hosted repository, simulating an aggregated RESTful response from university silos.

Secure Middleware: A Vite Proxy routes requests to the Opus Job Operator API. This ensures the x-service-key is injected server-side, protecting credentials from client-side exposure.

Cross-Platform Correlation: The payload is processed by an Opus Workflow. The AI Agent performs a correlation analysis—for example, recognizing that an "ID Expiry" in the Portal blocks "Marketplace Access" in Campus Services, prioritizing administrative fixes over academic study blocks to ensure basic student subsistence.

Async Polling & Delivery: The React frontend implements a Latency-Aware Polling Loop to monitor job status. Once completed, it delivers a "Rationale" explaining the logic behind the suggested priorities.

