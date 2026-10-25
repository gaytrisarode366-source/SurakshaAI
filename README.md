# SurakshaAI 🛡️
### Predictive Public Safety, Emergency Response and Beat Intelligence

**Tagline:** Predict Smart. Respond Fast. Protect Every Citizen.

## 1. About the Project

SurakshaAI is an AI-powered public safety prototype developed for the **Seva First Innovation Challenge** under the Law & Order sector. It aims to improve public access to legal awareness, support historical crime-pattern analysis, visualize police beat intelligence, and organize emergency incident information through a unified dashboard.

The project combines Artificial Intelligence, Machine Learning, data visualization, and database technologies to support informed decision-making and promote safer communities.

## 2. Problem Statement

Citizens may struggle to understand their legal rights and the appropriate steps to take after experiencing online fraud or other incidents. At the same time, analyzing historical crime patterns and visualizing police beat coverage can be challenging without accessible data tools.

There is a need for a user-friendly platform that brings together legal awareness, data-driven public safety insights, and incident tracking while maintaining privacy and human oversight.

## 3. Objectives

- Provide accessible legal information for citizens experiencing suspected fraud.
- Analyze historical crime data to identify patterns by area and time.
- Visualize police beat areas and potential coverage gaps.
- Record incident details and track their status within the prototype.
- Present useful insights through an interactive dashboard.
- Promote responsible AI, transparency, and data privacy.

## 4. Key Features

### A. AI Legal Awareness Assistant
- Accepts incident descriptions in simple language.
- Identifies possible incident categories, such as UPI fraud, phishing, fake job scams, and online shopping fraud.
- Retrieves potentially relevant legal information from a verified knowledge base.
- Provides source references, suggested next steps, and evidence checklists.
- Supports multilingual assistance as a planned enhancement.

### B. Predictive Crime Hotspot Analysis
- Processes historical or clearly labeled demonstration data.
- Analyzes patterns based on area, time, and incident category.
- Displays trends and potential hotspots through charts and maps.
- Supports model evaluation before any real-world use.

### C. Police Beat Intelligence
- Visualizes beat zones and available historical incident patterns.
- Helps identify potential coverage gaps.
- Presents planning insights for human review.

### D. Emergency Incident Management
- Records incident details through a structured form.
- Generates a reference ID for prototype tracking.
- Displays incident status, such as Submitted, Under Review, Referred, or Resolved.
- Helps organize incident information in a centralized dashboard.

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web interface and dashboard |
| Pandas | Data processing and analysis |
| NumPy | Numerical computations |
| Scikit-learn | Machine learning |
| Plotly | Interactive charts |
| Folium | Map visualization |
| SQLite | Local database |
| Pytest | Software testing |
| Git and GitHub | Version control and collaboration |

## 6. System Workflow

1. The user enters an incident description or the system receives historical data.
2. Input data is validated and processed.
3. The legal assistant retrieves relevant information, or the ML module analyzes available data.
4. The system generates visualizations, possible insights, and suggested next steps.
5. The dashboard displays the results for user understanding and human review.

**Workflow:**

User Input / Historical Data → Data Validation → AI/ML Analysis or Legal Retrieval → Dashboard → Human Review and Next Steps

## 7. Proposed System Architecture

- **Presentation Layer:** Streamlit interface.
- **Application Layer:** Python modules for legal assistance, incident management, and analytics.
- **AI/ML Layer:** Crime-pattern analysis and incident classification.
- **Knowledge Layer:** Curated legal information with official source references.
- **Data Layer:** SQLite database and structured datasets.
- **Visualization Layer:** Interactive charts, maps, and status dashboards.

## 8. Installation and Execution

### Prerequisites
- Python 3.10 or a compatible version.
- Visual Studio Code.
- Git (optional).

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd surakshaai
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL.

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run app.py
```

The application will provide a local URL in the terminal. Open that URL in your browser.

*Note: These commands assume the corresponding project files and dependencies have been created.*

## 9. Expected Impact

- Improves access to understandable legal information.
- Helps citizens organize incident details and identify official reporting options.
- Supports analysis of historical crime patterns.
- Provides visual insights for public safety planning.
- Encourages informed decision-making through accessible technology.
- Promotes privacy-conscious and responsible use of AI.

## 10. Responsible AI and Privacy

- Legal information must be based on verified sources and should include appropriate references.
- AI-generated outputs may be incomplete and must not be treated as definitive legal advice.
- The system must not predict whether a specific individual will commit a crime.
- Personal information should be minimized and protected.
- The application must never request passwords, OTPs, UPI PINs, or card security codes.
- Prototype incident tracking must not be represented as an official police complaint or emergency dispatch service.
- Human review is required for consequential decisions.

## 11. Future Scope

- Add English, Hindi, and Marathi language support.
- Integrate additional verified public datasets.
- Improve model performance through suitable validation and testing.
- Expand map-based public safety analytics.
- Add secure authentication and role-based access where needed.
- Explore authorized integrations with official services, subject to approval.

## 12. Project Status

**Project Stage:** Prototype development.

The proposed modules will be implemented and tested incrementally. Features, model performance, and integrations should be described as completed only after they have been implemented and verified.

## 13. Team

**Team Name:** SurakshaAI

**Project
