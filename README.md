A full-stack gym management application that supports member, trainer, and admin workflows, plus AI-powered diet and workout recommendations.

### Functions
- Member onboarding, login, profile, membership selection, and dashboard
- Trainer scheduling, session management, workout planning, and progress tracking
- Admin modules for user management, membership management, equipment maintenance, promotions, and feedback handling
- AI service for generating diet plans and exercise recommendations based on user metrics
- File uploads and gym-related resource management

### Architecture
- frontend — React single-page application
- backend — Spring Boot REST API
- ai_service — Flask ML service for diet/exercise prediction
- `uploads/` — file storage for slips and media

### Main stacks and languages
- **Frontend**
  - Language: JavaScript / JSX
  - Framework: React
  - Tooling: Vite
  - Styling: Tailwind CSS
  - Routing: React Router
  - HTTP: Axios

- **Backend**
  - Language: Java
  - Framework: Spring Boot
  - Data access: Spring Data JPA
  - Security: Spring Security
  - Mail: Spring Boot Mail
  - Database driver: MySQL Connector/J

- **AI Service**
  - Language: Python
  - Framework: Flask
  - ML model handling: joblib
  - Data processing: pandas, numpy
  - CORS support: Flask-CORS

### Key components
- pages — UI pages for member, trainer, and admin flows
- backend — controllers, entities, repositories, services, security
- app.py — diet/exercise prediction endpoints and model loading
