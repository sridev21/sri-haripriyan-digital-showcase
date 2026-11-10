# Sri Haripriyan Digital Showcase

Create a web app design for my personal portfolio. Add more and more ynamic danimations and transition effects. The site should be more attractive. Use these data from my resume:"
Sri Haripriyan S mail: sris.haripriyan@gmail.com LinkedIn: linkedin.com/in/sri-haripriyan GitHub: github.com/sri-haripriyan LeetCode: leetcode.com/u/sri-hari321/ Education Mahendra College of Engineering 2021 – 2025 BE Computer Science and Engineering CGPA: 8.3/10 Relevant Coursework: Data Structures, Object-Oriented Programming, DBMS, Operating Systems, Computer Networks Class XII (State Board, Attur): 83.83% (2020) | Class X (State Board, Attur): 93.6% (2018) Experience Backend Developer Intern (Remote) Dec 2024 – Feb 2025 International Institute of SDGs and Public Policy Research Tech stack: Node.js, Express.js, MongoDB, node-cron • Built the backend of an Intern Management Application with a team of 12 interns and 3 admins, used by a research organisation to manage 100+ research interns, exposing 30+ REST endpoints. • Implemented APIs to fetch each intern’s allotted and shared work, track task completion and performance, enforce leave policy, record attendance and on-time check-ins. • Cut report generation time (including PDF export) from ∼4–5 s to ∼2–2.5 s (about 50% faster) by adding indexes on the tasks collection and optimising queries with MongoDB aggregation pipelines. • Automated routine admin work with node-cron: cleanup of completed interns’ tasks and unneeded data, attendance checks that disable accounts below 85% attendance, and account-expiry notifications at internship completion. Software Engineer Intern (Training Program) Oct 2025 – Dec 2025 HashedIn by Deloitte • Completed a structured weekly training on Spring Boot, GenAI (RAG, multi-agent systems) and data engineering, building one hands-on project per module (see Projects). Projects Alcognerd | MERN, Redis, BullMQ, Socket.io, React Query alcognerd.site Nov 2024 – Feb 2025 • Built a full-stack event management platform for organising free and paid events, with real-time chat using Socket.io. • Reduced event attendance processing time by 70% by caching attendance data in Redis during the live event, with the TTL set to the event end time and the cache invalidated when a QR code is scanned on the frontend. • Moved registration emails to a BullMQ queue with Nodemailer, so event registration no longer blocks on email retries. • Cut redundant API calls with React Query; integrated Cloudinary with Multer for image uploads and delivery. Codebase Q&A and Report Assistant (GenAI) | Python, FastAPI, LangGraph, RAG, PostgreSQL Training project, HashedIn • Built a codebase Q&A chatbot where users upload a zip or repository and ask questions about the codebase, using RAG with PostgreSQL and database migrations. • Designed a LangGraph multi-agent system: an orchestrator agent routes each request to a chat, report or analysis agent, each with at least 2 tools. • Added a human-in-the-loop review step so users approve generated code reports before they are finalised. Service Marketplace Backend (Urban Company-style) | Java, Spring Boot, JUnit Training project, HashedIn • Developed the backend REST APIs for a home-services marketplace using Spring Boot and wrote JUnit test cases for the application. Data Cleaning Pipeline | Databricks, Apache Spark, Python, Pandas Training project, HashedIn • Built a pipeline on Databricks that cleans text data (removing duplicates, normalising fields) into structured, non-null rows across 9 tables, processing the tables in parallel with Apache Spark. Technical Skills Languages: Java, C++, JavaScript, Python, SQL Backend: Node.js, Express.js, Spring Boot, FastAPI, REST APIs Databases & Messaging: MongoDB, PostgreSQL, Redis, BullMQ, Kafka (basic) GenAI & Data: RAG, LangGraph, Multi-Agent Systems, Apache Spark, Databricks, Pandas Frontend: React.js, React Query, Tailwind CSS, Socket.io Tools & Cloud: Git, GitHub, JUnit, AWS (basics) Core CS: Data Structures & Algorithms, OOP, DBMS Achievements • Solved 360+ problems on LeetCode."

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://sri-haripriyan-digital-showcase.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/fcbc2466-2315-5cef-b0db-14ebad1697e2).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
