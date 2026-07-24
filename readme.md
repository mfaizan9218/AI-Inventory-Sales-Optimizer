# Ledger — BYOAI Inventory & Sales Optimizer



> A SaaS-style inventory and sales management dashboard built with **HTML, CSS, and JavaScript**. The application provides local inventory management, business analytics, and optional **Bring Your Own AI (BYOAI)** integration for business insights through multiple AI providers.



![Dashboard Overview](ss/01-dashboard-overview.png)



---







---



## 📸 Screenshots



### Dashboard Overview



![Dashboard Overview](ss/01-dashboard-overview.png)



### Inventory Management



![Inventory Management](ss/02-inventory-management.png)



### Sales Management



![Sales Management](ss/03-sales-management.png)



### AI Insights



![AI Insights](ss/04-ai-insights.png)



### Business Q&A



![Business Q&A](ss/05-business-qa.png)



### AI Providers



![AI Providers](ss/06-ai-providers.png)



---



# Project Overview



Ledger is a browser-based inventory and sales management dashboard designed as a modern SaaS-style frontend application. It enables users to manage products, record sales, monitor business performance, and optionally connect their preferred AI provider for deeper business insights.



The project demonstrates modern frontend development practices including responsive dashboard design, client-side state management, CRUD operations, CSV import workflows, reusable UI components, business analytics, and a provider-agnostic BYOAI integration layer.



Built as a portfolio project, Ledger focuses on technical honesty by clearly separating locally computed functionality from optional AI-powered features.



---



# Features



## Core Features (Runs Completely Locally)



### Dashboard



- Business KPI dashboard

- Inventory value tracking

- Retail value calculation

- Revenue tracking

- Gross margin calculation

- Fast movers

- Low stock alerts

- Overstock detection

- Dead stock detection

- Last updated timestamp

- Demo Data indicator



### Inventory Management



- Add products

- Edit products

- Delete products

- Product categories

- SKU management

- Quantity tracking

- Reorder point management



### Sales Management



- Record sales

- Edit sales

- Delete sales

- Revenue tracking

- Sales history



### Data Management



- CSV import

- Sample demo dataset

- Reset sample data

- Persistent browser storage



---



## Optional BYOAI Features



After connecting a supported AI provider, users can generate:



- Executive summaries

- Inventory analysis

- Sales analysis

- Demand forecasting

- Reorder recommendations

- Business question answering

- Inventory optimization suggestions



No AI functionality is available until the user connects their own AI provider.



---



# About This Demo



This project is intentionally transparent about what is handled locally versus what requires AI.



## Runs Entirely in the Browser



- No backend server

- No database

- No authentication

- No built-in API keys

- No hidden AI services



## Local Business Logic



The following metrics are computed entirely using client-side JavaScript:



- Inventory value

- Retail value

- Revenue

- Gross margin

- Low stock

- Overstock

- Dead stock

- Fast movers

- Dashboard statistics



These calculations use deterministic, rule-based business logic and do **not** rely on machine learning, predictive analytics, or optimization algorithms.



## Optional AI Integration



AI capabilities become available only after the user connects their own supported provider.



The application never ships with AI models or API keys.



---



# Supported AI Providers



Ledger supports Bring Your Own AI (BYOAI) integration with multiple providers, including:



- OpenAI

- Anthropic Claude

- Google Gemini

- xAI Grok

- DeepSeek

- Mistral

- Cohere

- OpenRouter

- Ollama

- LM Studio

- Azure OpenAI

- AWS Bedrock

- OpenAI-compatible custom endpoints



A shared adapter layer ensures a consistent experience regardless of the selected provider.



---



# Technology Stack



- HTML5

- CSS3

- JavaScript (ES6+)

- Local Storage

- Fetch API

- Responsive Design

- CSV Import

- Client-side State Management

- Modular UI Components

- Adapter Pattern

- Strategy Pattern

- BYOAI Integration



---



# Project Structure



```text

AI-Inventory-Sales-Optimizer/

│

├── index.html

├── README.md

├── LICENSE

└── ss/

    ├── 01-dashboard-overview.png

    ├── 02-inventory-management.png

    ├── 03-sales-management.png

    ├── 04-ai-insights.png

    ├── 05-business-qa.png

    └── 06-ai-providers.png

```



---





```



## Open the Project



Simply open **index.html** in any modern web browser.



No installation, build tools, or package managers are required.



---



# How It Works



1. Add or import inventory data.

2. Record sales transactions.

3. Dashboard metrics update automatically using local business logic.

4. Optionally connect an AI provider.

5. Generate AI-powered business insights from the **AI Insights** section.



---







---



# License



This project is licensed under the **MIT License**.



---



# Author



**M Faizan Sheikh** 







---



### Portfolio Purpose



This project was created as a frontend portfolio demonstration to showcase:



- Modern dashboard development

- Inventory and sales management workflows

- Client-side business analytics

- Responsive UI/UX design

- JavaScript architecture

- CRUD operations

- BYOAI integration

- Professional SaaS-inspired frontend development



It is intended for recruiters, internship opportunities, portfolio reviews, and frontend software engineering demonstrations.