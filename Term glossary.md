# **Coding Environments & Tools**

### 

### **CLI (Command Line Interface)**

A text-based interface where you type commands instead of clicking buttons.

### 

### **IDE (Integrated Development Environment)**

A software for writing code with features like autocomplete, debugging, and file management.

### 

### **Cursor**

An AI-powered coding editor where you write code with the help of AI. It can generate, fix, and explain code.

### 

### **Vibe Coding**

Another AI coding environment similar to Cursor that helps generate code using natural language prompts.

### 

### **Replit**

A browser-based environment that lets you write code, run it instantly, and deploy apps — no installation needed.

### 

### **N8n**

A visual automation builder (like Zapier but more powerful). You create workflows by connecting blocks. No coding required.

### 

### **Lovable**

An AI app builder that creates full frontends (UI, buttons, pages) from natural language. Great for fast prototypes.

# **Frontend Concepts**

### 

### **Frontend**

The part of a website/app users see and interact with (UI).

### 

### **HTML**

The building blocks of a webpage (structure).

### 

### **CSS**

Controls how a webpage looks (design, layout, colors).

### 

### **JavaScript**

The programming language that makes webpages interactive.

* React

### 

### **TypeScript**

JavaScript with added safety features — used in professional frontend development.

# **Backend Concepts**

### 

### **Backend**

The behind-the-scenes part of an application that processes logic, handles data, and communicates with databases.

### 

### **API (Application Programming Interface)**

A way for two systems to talk to each other.  
Example: your app calls an AI model through an API.

### 

### **Endpoint**

A specific URL in your backend that does something (e.g., `/login`).

### 

### **FastAPI**

A Python framework for building fast, simple backend APIs.

### 

### **Flask / Django**

Older Python backend frameworks. Django is full-featured; Flask is lightweight.

# **AI & Machine Learning**

### 

### **LLM (Large Language Model)**

Advanced AI models like GPT-4.1, GPT-5.1, Claude 3.5, etc.

### 

### **LangChain**

A library for building AI workflows, agents, and pipelines.

### 

### **LlamaIndex**

A tool for connecting your own documents to LLMs (for RAG: Retrieval-Augmented Generation).

### 

### **DSPy**

A toolkit for building more structured AI reasoning systems.

### 

### **AI Agents**

Programs that can think, plan, decide, and take actions (not just give text responses).

### 

### **CrewAI / LangGraph**

Libraries for building multi-agent systems where different AI agents collaborate.

# **SDKs & Developer Tools**

### 

### **SDK (Software Development Kit)**

A toolkit provided by a service (e.g., OpenAI, AWS) that makes coding easier.

SDKs can be used in:

* Frontend  
* Backend  
* Mobile  
* Desktop

They are NOT backend-specific.

### 

### **OpenAI SDK / Anthropic SDK**

Packages that help you call LLMs from Python or JavaScript.

### 

### **API Key**

A secret password your code uses to authenticate with external services.

# **Databases & Storage**

### 

### **Database**

Where structured data is stored (users, tasks, workflows).

### 

### **SQL (Structured Query Language)**

Language used to interact with databases.

### 

### **PostgreSQL**

A popular SQL database used in modern apps.

### 

### **Supabase**

A backend service providing:

* Database  
* Authentication  
* APIs  
* Storage

### **Vector Database**

Stores embeddings for semantic search and AI memory.

# **Cloud Infrastructure**

### 

### **AWS (Amazon Web Services)**

Largest cloud provider. Offers powerful but complex services.

### 

### **EC2**

Virtual machines (servers) running in the cloud.

### 

### **S3**

Cloud storage for files.

### 

### **Lambda**

Run small backend functions without managing servers.

### 

### **RDS**

Managed databases like PostgreSQL or MySQL.

### 

### **CloudFront**

Content delivery network (speeds up global access).

### 

### **Route 53**

Buy/manage domains and DNS.

### 

### **Cloudflare**

Global network used for:

* DNS  
* CDN  
* Security  
* Serverless functions

### **Cloudflare Workers**

Run backend code on Cloudflare’s global edge servers.

### 

### **Cloudflare R2**

Cheap file storage (similar to S3 but lower cost).

### **Railway**

User-friendly hosting for backend apps (great for FastAPI \+ Python).

### 

### **Render / Vercel**

Simple hosting solutions.  
Vercel specializes in frontend apps; Render handles both frontend \+ backend.

# **Automation Concepts**

### 

### **n8n Nodes**

Blocks or steps in a workflow (e.g., email → webhook → API call).

### 

### **Trigger**

What starts an automation flow (e.g., form submission).

### 

### **Webhook**

A URL your system exposes so other apps can send it data automatically.

# **Python & Coding Basics**

### 

### **Python**

A beginner-friendly language used for backend, AI, automation, and agents.

### 

### **Functions**

Blocks of reusable code.

### 

### **Variables**

Containers for storing values.

### 

### **Lists / Dictionaries**

Ways to store multiple values (similar to Excel columns & JSON objects).

### 

### **Packages / Modules**

Reusable code libraries.

### 

### **pip**

Tool to install Python packages.

# **Architecture & System Design (Zynkr.ai)**

### 

### **Frontend Layer**

User interface (built with Lovable).

### 

### **Backend Layer**

Python/FastAPI logic that processes requests.

### 

### **AI Layer**

Where LLM logic, workflows, and agents run.

### 

### **Database Layer**

Stores user data, workflows, results.

### 

### **Automation Layer**

n8n workflows connected to backend/AI.

### 

### **Knowledge Layer**

Your frameworks, templates, structured instructions.

### 

### **Infrastructure Layer**

Cloudflare (DNS), Railway (hosting), Supabase (auth \+ DB).  
