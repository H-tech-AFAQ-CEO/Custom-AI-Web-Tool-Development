# CliniqAI — Clinical Intelligence Assistant

**CliniqAI** is a sophisticated, single-page web application designed as a clinical decision support tool for healthcare professionals. Built with vanilla HTML, CSS, and JavaScript, it provides structured, evidence-based responses to clinical queries using OpenAI's GPT models. The application features a professional interface with specialized sections for differential diagnosis, investigations, management plans, and red flags.

## ✨ Features

### Core Clinical Intelligence
- **Structured Medical Responses** – AI-generated answers formatted with consistent sections:
  - Summary
  - Differential Diagnosis (ranked with rationale)
  - Recommended Investigations (labs, imaging, workup)
  - Management Plan (step-by-step treatment)
  - Red Flags (critical warning signs)
  - References (relevant guidelines)
- **Healthcare Professional Focus** – Clinical terminology, dosing information, and evidence-based recommendations
- **Safety Disclaimers** – Built-in warnings that the tool is for professional use only and not a substitute for clinical judgment

### User Interface & Experience
| Section | Description |
|---------|-------------|
| **Landing Page** | Professional hero section with feature highlights and clear value proposition |
| **Authentication** | Login/register system with role selection (Physician, Nurse, Pharmacist, Medical Student, Other) |
| **Clinical Chat** | Conversational interface with structured AI responses, typing indicators, and message actions |
| **Prompt Cards** | Pre-defined clinical scenarios for quick testing (Cardiology, Paediatrics, Neurology, Pharmacology, etc.) |
| **Dashboard** | Usage analytics, query logs, and user management table |
| **Settings Panel** | API key configuration, model selection, profile management, and preferences |

### AI Configuration
- **Multiple Model Support** – GPT-4o (recommended), GPT-4o Mini (faster), GPT-4 Turbo
- **Customizable System Prompts** – Dynamic prompt engineering based on user preferences
- **API Key Storage** – Secure localStorage storage of OpenAI API keys (client-side only)
- **Response Formatting** – Structured parsing of AI responses into visual sections

### Clinical Content Categories
- **Cardiology** – Chest pain, MI, ECG interpretation
- **Paediatrics** – Fever, rash, developmental concerns
- **Neurology** – Headache, stroke, seizure
- **Pharmacology** – Drug interactions, dosing, monitoring
- **Emergency Medicine** – Acute presentations, trauma, critical care
- **General Medicine** – Wide range of clinical scenarios

### User Management
- **Role-Based Profiles** – Customize display name and clinical role
- **Registration System** – Local storage-based user database
- **Session Persistence** – Stay logged in across browser sessions
- **User Table** – Admin view of registered healthcare professionals

### Analytics & Monitoring
- **Query Logging** – Track all clinical questions with timestamps
- **Conversation Counters** – Monitor usage statistics
- **Category Detection** – Automatic classification of query types
- **Performance Metrics** – Response time estimation

### Responsive Design
- **Collapsible Sidebar** – Optimized for desktop and tablet use
- **Mobile Support** – Touch-friendly interface with hamburger menu
- **Dark Theme** – Eye-friendly dark mode optimized for clinical environments

## 🖼️ Screenshots

> *Add your actual screenshots here to showcase the application.*

| Landing Page | Clinical Chat |
|--------------|---------------|
| *[Insert screenshot of landing page with hero section]* | *[Insert screenshot of structured AI response]* |

| Dashboard | Settings Panel |
|-----------|----------------|
| *[Insert screenshot of analytics dashboard]* | *[Insert screenshot of API configuration]* |

| Prompt Cards | Mobile View |
|--------------|-------------|
| *[Insert screenshot of clinical prompt grid]* | *[Insert screenshot of responsive mobile layout]* |

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- OpenAI API key (get one at [platform.openai.com/api-keys](https://platform.openai.com/api-keys))

### Installation & Usage
1. Clone or download the repository.
2. Open `index.html` directly in your browser.
   ```bash
   # Optional: use a local server
   npx serve
