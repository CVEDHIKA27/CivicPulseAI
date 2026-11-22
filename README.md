# CivicPulseAI – AI-Powered Multi-Agent Citizen Grievance Management System with RAG

## Project Overview

CivicPulseAI is an AI-powered Multi-Agent Citizen Grievance Management System designed to simplify and improve the process of registering, analyzing, managing, tracking, and monitoring public complaints.

The system connects citizens and government authorities through an intelligent digital platform. It integrates Multi-Agent Artificial Intelligence and Retrieval-Augmented Generation (RAG) to support intelligent complaint processing, classification, department routing, and resolution tracking.

CivicPulseAI uses four specialized AI agents coordinated through LangGraph, along with a RAG-based knowledge retrieval module powered by ChromaDB.

The platform aims to improve transparency, organize public grievance management, and support better coordination between citizens and administrative authorities.

---

## Problem Statement

Traditional complaint management systems often involve manual complaint processing, delayed responses, difficulties in identifying responsible departments, limited complaint tracking, and inefficient coordination between citizens and government authorities.

These challenges make it difficult to manage public grievances effectively and maintain transparency throughout the complaint resolution process.

CivicPulseAI addresses these problems through an intelligent digital platform that combines Multi-Agent AI, RAG-based knowledge retrieval, structured complaint management, and location-based monitoring.

---

## Project Objectives

- To provide a digital platform for citizen complaint registration.
- To automate complaint understanding and classification using AI techniques.
- To identify and recommend the appropriate government department for each complaint.
- To integrate RAG-based knowledge retrieval for accessing relevant municipal information.
- To support efficient complaint tracking and status monitoring.
- To provide administrative dashboards for complaint management.
- To improve transparency and coordination between citizens and authorities.
- To utilize Multi-Agent AI for intelligent grievance processing.

---

## Key Features

### 1. Citizen Complaint Management
- Citizen registration and login.
- Submission of public complaints.
- Complaint details and location information.
- Unique complaint number generation.

### 2. Multi-Agent AI Processing
Uses four specialized AI agents to process citizen complaints:

- **Complaint Understanding Agent:** Analyzes complaint descriptions and identifies relevant topics.
- **Complaint Classification Agent:** Determines the complaint category and priority.
- **Department Routing Agent:** Recommends the appropriate department based on complaint classification.
- **Resolution Tracking Agent:** Initializes and supports complaint status tracking.

### 3. RAG-Based Knowledge Retrieval
- Retrieves relevant information from municipal knowledge documents.
- Uses ChromaDB as the vector database.
- Generates local text embeddings using Sentence Transformers.
- Supports knowledge retrieval for water supply, road maintenance, waste management, electricity, and drainage.

### 4. Complaint Tracking
- Unique complaint identification.
- Complaint status monitoring.
- Complaint history and timeline.
- Status updates by authorized officers.

### 5. Officer Dashboard
- View and manage registered complaints.
- Review AI-generated complaint analysis.
- Update complaint status.
- Monitor complaint information.

### 6. Location-Based Visualization
- Location selection during complaint submission.
- GPS latitude and longitude support.
- Geographical complaint visualization using interactive maps.
- Complaint markers based on available location information.

### 7. Complaint Analytics
- Total complaint statistics.
- Pending and resolved complaint counts.
- High-priority complaint monitoring.
- Complaint category distribution.
- Graphical representation of complaint information.

---

## System Architecture

CivicPulseAI follows a Multi-Agent AI and RAG-based architecture.

### Main System Modules

1. **Citizen Interface:** Allows citizens to register, log in, submit complaints, and track their complaints.
2. **Complaint Management Module:** Handles complaint registration, storage, and status management.
3. **AI Processing Module:** Executes the specialized AI agents through LangGraph.
4. **RAG Knowledge Retrieval Module:** Retrieves relevant municipal information using ChromaDB.
5. **Database Management Module:** Stores user details, complaints, departments, complaint history, and AI analysis records.
6. **Officer Dashboard:** Enables authorities to review and manage complaints.
7. **Monitoring and Analytics Module:** Provides complaint timelines, geographical visualization, and statistical reports.

### Multi-Agent Workflow

The complaint processing workflow consists of four specialized agents and one RAG retrieval stage:

1. Complaint Understanding Agent
2. Complaint Classification Agent
3. RAG Knowledge Retrieval
4. Department Routing Agent
5. Resolution Tracking Agent

**Workflow Orchestration:** LangGraph coordinates the processing sequence and combines the results.

---

## Technologies Used

### Frontend
- React.js
- JavaScript
- Vite
- HTML5
- CSS3
- React Router
- Leaflet
- React-Leaflet
- Chart.js
- React Chart.js 2

### Backend
- Python
- FastAPI
- Uvicorn
- SQLAlchemy
- Pydantic

### Database
- PostgreSQL
- ChromaDB

### Artificial Intelligence and Machine Learning
- Multi-Agent AI Architecture
- LangGraph
- LangChain
- Retrieval-Augmented Generation (RAG)
- Sentence Transformers
- all-MiniLM-L6-v2 Embedding Model
- Gemini API
- Nexus API

### Development Tools
- Visual Studio Code
- Git
- GitHub
- Python Virtual Environment

---

## Database Management

CivicPulseAI uses PostgreSQL for structured application data and ChromaDB for vector-based knowledge retrieval.

### PostgreSQL Tables

- **Users:** Stores citizen and officer account information.
- **Departments:** Stores department details.
- **Complaints:** Stores complaint descriptions, categories, priorities, locations, and statuses.
- **Complaint History:** Maintains complaint status updates and remarks.
- **AI Analysis:** Stores AI agent outputs and RAG retrieval information.

### ChromaDB

ChromaDB stores vector embeddings of municipal knowledge documents and supports semantic retrieval of relevant information.

---

## Municipal Knowledge Base

The RAG module uses municipal knowledge documents covering the following categories:

- Water Supply
- Road Maintenance
- Waste Management
- Electricity
- Drainage

These documents provide reference information for the knowledge retrieval process.

**Note:** The municipal knowledge documents are intended for academic demonstration and are not official government regulations.

---

## Project Team

**Project Title:** CivicPulseAI – AI-Powered Multi-Agent Citizen Grievance Management System with RAG

**Developed By:**

1. Vedhika C
2. Sindhu Priya

**Department:** B.E. Computer Science and Engineering

**Institution:** Vivekanandha College of Engineering for Women

**Semester:** Seventh Semester

**Academic Year:** 2026

---

## Repository Structure

The project source code is provided as a ZIP archive in this repository.

- `CivicPulseAI_SourceCode.zip` – Complete project source code archive.
- `README.md` – Project documentation.

The source archive contains the frontend, backend, AI agents, RAG implementation, municipal knowledge documents, database-related modules, and supporting files.

---

## How to Access the Project

1. Open the CivicPulseAI GitHub repository.
2. Download `CivicPulseAI_SourceCode.zip`.
3. Extract the ZIP archive.
4. Open the extracted project folder in Visual Studio Code.
5. Refer to `requirements.txt` for Python dependencies and `package.json` for frontend dependencies.
6. Configure the required environment variables and database connection.
7. Follow the backend and frontend setup instructions before running the application.

---

## Expected Outcomes

- Simplified digital citizen complaint registration.
- Improved complaint understanding and classification.
- Intelligent department recommendation.
- Relevant municipal knowledge retrieval through RAG.
- Better complaint tracking and status monitoring.
- Improved administrative complaint management.
- Geographical visualization of public grievances.
- Data-driven complaint monitoring through analytics.
- Better coordination between citizens and government authorities.

---

## GitHub Repository

**Project Repository:**  
https://github.com/CVEDHIKA27/CivicPulseAI

---

## Project Conclusion

CivicPulseAI combines Multi-Agent Artificial Intelligence, Retrieval-Augmented Generation, and digital complaint management to provide an organized approach to public grievance handling.

By integrating intelligent complaint processing, municipal knowledge retrieval, department routing, location-based visualization, and complaint tracking, the system aims to support a smarter, more transparent, and more responsive citizen grievance management process.

**CivicPulseAI – Building a Smarter and More Responsive Citizen Grievance Management System.**
