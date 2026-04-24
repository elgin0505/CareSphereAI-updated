# CareSphereAI-updated
CareSphereAI: An agentic healthcare solution built with the Google AI Ecosystem to address Malaysia’s transition toward an "Aged Society." Part of Project 2030: MyAI Future Hackathon.

🚀 Live Demo & Deployment
Cloud Run URL: [INSERT YOUR CLOUD RUN URL HERE] 
Video Demo: [INSERT YOUTUBE/GOOGLE DRIVE LINK]

📌 Problem Statement & National Relevance
As Malaysia moves toward "Aged Society" status, the public healthcare system faces unprecedented strain, particularly in Emergency Departments and home-care monitoring for the elderly. CareSphereAI is engineered to:
Bridge the Talent Gap: Transitioning from technology consumers to Sovereign Technology Builders.
Align with National Agendas: Directly supporting the Malaysia Madani framework, MyDIGITAL, and the NIMP 2030.
Reduce Bureaucratic Friction: Eliminating manual document verification and redefining clinical workflows.

🛠 Technical Stack (The "Build with AI" Mandate)
This project is built strictly on the Google AI Ecosystem Stack:
Component     |    	Technology        |      	Description			
The Intelligence	  Gemini 2.0 (Flash & Pro)	Core reasoning engine for healthcare diagnostics and logic.			
The Orchestrator	  Firebase Genkit         	Powers the Agentic AI workflows and autonomous execution.			
Development	        TypeScript / Node.js	    Modular backend architecture for high-fidelity performance.			
Infrastructure	    Google Cloud Run	        Serverless deployment in the asia-southeast1 region.			
CI/CD	              Google Cloud Build	      Automated regional build triggers for rapid iteration.			
Database	          Cloud Firestore	          Real-time NoSQL storage for readings, logs, and alerts.			

🌟 Key Features
Autonomous Alerts Center: Dispatches real-time alerts to caregivers based on patient health readings.
Medication Management: Automated tracking of schedules and adherence logs to ensure elderly safety.
Risk Assessment Engine: Intelligent diagnostics that categorize risk levels (High/Medium/Low) for clinical intervention.
Agentic Companion: A system capable of reasoning and planning multi-step care tasks rather than just answering questions.

🏗 Architectural Overview
The project follows a modern microservices approach:
Backend: A Dockerized Node.js application.
Deployment: Managed by cloudbuild.yaml, which builds the image, pushes it to the Google Container Registry, and deploys it to Cloud Run.
Data: Firestore indexes are optimized for chronological tracking of "readings" and "conversations".

💻 Local Setup Instructions
Clone the Repository: git clone https://github.com/[YOUR_USERNAME]/CareSphereAI.git
cd CareSphereAI/backend
Install Dependencies: npm ci
Environment Variables:
Create a .env file in the backend/ directory (refer to .env.example).
Run Development Server: npm run dev

📜 AI Disclosure
This project utilized Google Gemini for code optimization, debugging, and drafting technical documentation. All AI-generated components have been reviewed, verified, and integrated by the team to ensure ethical and functional alignment with Google’s AI Principles.
