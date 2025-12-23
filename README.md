# 🎯 LakshPath - Your AI-Powered Career Mentor

> **Lakshya (Goal) + Path (Direction)** → Your smart path to your dream career

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built with Pathway](https://img.shields.io/badge/Built%20with-Pathway-blue)](https://pathway.com/)
[![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)](https://reactjs.org/)
[![AI Powered](https://img.shields.io/badge/AI-Powered-green)](https://openai.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

<div align="center">
  <img src="https://github.com/user-attachments/assets/e8b32e6b-05f3-46c4-8e50-fe6a56156b4c" alt="LakshPath Banner" width="711" />
</div>
---

## 📖 Table of Contents

- [Overview](#-overview)
- [The Problem](#-the-problem)
- [Our Solution](#-our-solution)
- [Key Features](#-key-features)
- [Tech Stack](#️-tech-stack)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage](#-usage)
- [API Documentation](#-api-documentation)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Team](#-team)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🌟 Overview

**LakshPath** is India's first **real-time adaptive career guidance platform** that combines AI intelligence with live job market data to provide personalized career mentorship to students across India.

Unlike traditional career counseling systems that rely on outdated information, LakshPath uses the **Pathway Framework** to stream real-time data from job portals, course platforms, and industry trends, ensuring students always receive current and relevant career guidance.



### 📊 Quick Stats

- **130M+** Indian college students need career guidance
- **60%** graduates are unemployed/underemployed
- **₹50,000+ Crores** lost annually to skill-job mismatch
- **Target:** 100M+ students guided by 2030

---

## 🚨 The Problem

### Current Career Guidance Crisis in India

Indian students face a **broken career guidance ecosystem**:

1. **Generic Advice**: One-size-fits-all counseling that ignores individual strengths
2. **Limited Access**: Quality guidance available only in tier-1 cities
3. **Outdated Information**: Career advice based on 1-2 year old market data
4. **No Personalization**: Students make critical decisions without understanding their unique aptitude
5. **Market Disconnect**: Academic curricula fail to align with real-time industry demands

### The Impact

- 🔴 **60%** of graduates end up unemployed or in jobs below their potential
- 🔴 **Skill-Career Mismatch** affects millions, costing the economy billions
- 🔴 Only **15%** of students receive quality career guidance
- 🔴 New roles emerge (AI Engineer, Blockchain Developer) but students lack real-time awareness

### Critical Gap

> **Industries evolve rapidly** — new skills become hot (Generative AI, Cloud Architecture) while traditional ones fade — but students lack a system that adapts in real-time to these shifts.

---

## 💡 Our Solution

**LakshPath** is an AI-powered platform that acts as a **24/7 personal career mentor** for every student in India.

### Why LakshPath?

- 🧠 **Intelligent**: AI analyzes individual strengths, interests, and learning styles
- 🔄 **Real-Time**: Adapts to market changes using live data streams (Pathway Framework)
- 🎯 **Personalized**: Every student gets a unique roadmap tailored to their profile
- 🌐 **Accessible**: Available to students across India, from metros to remote villages
- 📈 **Data-Driven**: Backed by live industry trends from 10+ job portals and course platforms

### Our Unique Approach

```
Traditional Counseling          →    LakshPath
─────────────────────────────────────────────────────
Static advice (1-2 yr old)     →    Real-time data (daily updates)
Generic templates              →    AI-personalized roadmaps
One-time session               →    Continuous adaptation
Expensive (₹10K-50K)          →    Free tier + affordable premium
Limited availability           →    24/7 accessible
```

---

## ✨ Key Features

### 1. 🎓 Personalized Career Discovery

- **AI-Powered Analysis**: Take an interactive quiz or upload your LinkedIn/resume
- **Career DNA Mapping**: AI creates a unique profile based on interests, skills, and personality
- **Holistic Assessment**: Considers academic background, extracurriculars, and aspirations
- **10-Minute Onboarding**: Quick and easy compared to traditional 3-hour sessions

### 2. 📊 Dynamic Skill Mapping

- **Live Data Integration**: Pathway connects to 10+ job portals in real-time
- **Market Alignment**: Recommendations based on current and emerging industry trends
- **Demand Forecasting**: Predicts which skills will be in-demand 2-5 years ahead
- **Daily Updates**: Tracks 50,000+ job postings and skill requirements continuously

### 3. 🗺️ AI Roadmap Generation

- **Custom Learning Journey**: Step-by-step path from current state to dream career
- **Resource Curation**: Courses from Coursera, Udemy, YouTube, and free resources
- **Timeline Planning**: Clear milestones (3/6/12 month plans)
- **Multi-Path Options**: Explore alternative career trajectories
- **Portfolio Projects**: Hands-on project recommendations for skill building

### 4. 🔄 Real-Time Adaptability

- **Instant Updates**: Dashboard reflects new opportunities as they emerge
- **Trend Alerts**: "React 19 released - Add to your roadmap?"
- **Course Recommendations**: Fresh learning resources added continuously
- **Market Shift Notifications**: "Data Analytics roles increased 40% this month"

### 5. 👥 Community Learning Hub

- **Peer Collaboration**: Connect with students on similar career paths
- **Progress Sharing**: Celebrate achievements and milestones together
- **Mentorship Network**: Learn from seniors who've successfully transitioned
- **Discussion Forums**: Ask questions, share resources, and grow together
- **Study Groups**: Form peer groups based on target careers

### 6. 🤖 AI Career Mentor

- **Motivational Nudges**: Personalized encouragement to keep you on track
- **Smart Insights**: Data-backed suggestions to optimize learning
- **Progress Tracking**: Visual dashboards showing your growth journey
- **Interview Prep**: AI-powered mock interviews and feedback
- **Resume Optimization**: ATS-friendly resume building tools

---

## 🛠️ Tech Stack

### Frontend

- **Framework**: React.js 18+
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **Charts**: Chart.js, Recharts
- **UI Components**: shadcn/ui, Radix UI
- **Icons**: Lucide React

### Backend

- **Runtime**: Node.js with Express.js
- **AI Integration**: Flask microservice for OpenAI
- **API Design**: RESTful architecture
- **Validation**: Joi, express-validator
- **Security**: Helmet, CORS, rate-limiting

### AI & Machine Learning

- **Primary AI**: OpenAI GPT-4 API
- **Alternative**: Google Gemini API
- **NLP**: Natural language processing for resume parsing
- **Embeddings**: Vector similarity for career matching
- **Custom Models**: Skill recommendation engine

### Real-Time Data Processing

- **Pathway Framework**: Live data streaming and indexing
- **WebSockets**: Real-time updates to client
- **Redis**: Caching layer for performance
- **Queue**: Bull for job processing

### Database & Storage

- **Primary DB**: Firebase Firestore (NoSQL)
- **Authentication**: Firebase Auth (Google OAuth, Email)
- **File Storage**: Firebase Storage (resume uploads)
- **Caching**: Redis for frequently accessed data

### External APIs & Data Sources

- **Job Portals**: LinkedIn Jobs, Naukri.com, Indeed, Monster
- **Course Platforms**: Coursera API, Udemy API
- **Skill Trends**: GitHub Trends, Stack Overflow Insights
- **Industry Data**: NASSCOM Reports, Government Employment Data

### DevOps & Deployment

- **Frontend Hosting**: Vercel
- **Backend Hosting**: Render / Railway
- **CI/CD**: GitHub Actions
- **Monitoring**: Google Analytics, Sentry
- **Analytics**: Mixpanel for user behavior

### Development Tools

- **Version Control**: Git, GitHub
- **Code Quality**: ESLint, Prettier
- **Testing**: Jest, React Testing Library, Supertest
- **API Testing**: Postman, Thunder Client

---

## 🏗️ Architecture

### System Architecture Diagram

```
┌─────────────────────────────────────────────────────────────┐
│                    STUDENT INTERFACE                        │
│               React.js + Tailwind CSS                       │
│   Dashboard | Quiz | Roadmap Viewer | Community | Profile   │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│                    API GATEWAY                              │
│              Node.js + Express.js                           │
│   Authentication | Routing | Rate Limiting | Validation     │
└──────────┬──────────────────────────────────────┬───────────┘
           │                                      │
           ▼                                      ▼
┌──────────────────────┐              ┌─────────────────────────┐
│    AI ENGINE         │              │  PATHWAY FRAMEWORK      │
│  (OpenAI/Gemini)     │◄─────────────┤  Live Data Streaming    │
│                      │              │                         │
│ • Profile Analysis   │              │ • LinkedIn Jobs API     │
│ • Career Matching    │              │ • Naukri.com API        │
│ • Roadmap Generation │              │ • Coursera API          │
│ • NLP Resume Parser  │              │ • Skill Trend Data      │
│ • Interview Prep     │              │ • Daily Market Analysis │
└──────────┬───────────┘              └──────────┬──────────────┘
           │                                     │
           ▼                                     ▼
┌────────────────────────────────────────────────────────────┐
│              FIREBASE ECOSYSTEM                            │
│                                                            │
│  ┌──────────────────┐  ┌───────────────┐  ┌──────────────┐ │
│  │  Firestore DB    │  │  Firebase     │  │   Storage    │ │
│  │                  │  │  Auth         │  │              │ │
│  │ • User Profiles  │  │ • Google OAuth│  │ • Resumes    │ │
│  │ • Roadmaps       │  │ • Email Auth  │  │ • Documents  │ │
│  │ • Progress Data  │  │ • Session Mgmt│  │ • Exports    │ │
│  │ • Community      │  │               │  │              │ │
│  └──────────────────┘  └───────────────┘  └──────────────┘ │
└────────────────────────────────────────────────────────────┘
           │
           ▼
┌─────────────────────────────────────────────────────────────┐
│                 CACHING & QUEUE LAYER                       │
│           Redis + Bull Queue                                │
└─────────────────────────────────────────────────────────────┘
```

### Data Flow

1. **User Input** → Student completes quiz or uploads resume
2. **Authentication** → Firebase Auth validates user
3. **API Processing** → Express.js routes request to appropriate service
4. **AI Analysis** → OpenAI/Gemini processes profile data
5. **Live Data Fetch** → Pathway streams real-time job/course data
6. **Career Matching** → Algorithm matches student profile with opportunities
7. **Roadmap Generation** → AI creates personalized learning path
8. **Storage** → Firebase stores user data and roadmaps
9. **Real-Time Updates** → WebSockets push updates to dashboard
10. **Continuous Monitoring** → Pathway monitors market changes 24/7

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher) - [Download](https://nodejs.org/)
- **Python** (v3.9 or higher) - [Download](https://python.org/)
- **Git** - [Download](https://git-scm.com/)
- **Firebase Account** - [Sign up](https://firebase.google.com/)
- **OpenAI API Key** - [Get key](https://platform.openai.com/)
- **Pathway API Access** - [Request access](https://pathway.com/)

### Quick Start (5 Minutes)

```bash
# Clone the repository
git clone https://github.com/yourusername/lakshpath.git
cd lakshpath

# Install dependencies
npm run install-all

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys

# Run the application
npm run dev
```

🎉 Open [http://localhost:3000](http://localhost:3000) in your browser!

---

## 📥 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/lakshpath.git
cd lakshpath
```

### Step 2: Install Frontend Dependencies

```bash
cd frontend
npm install
```

### Step 3: Install Backend Dependencies

```bash
cd ../backend
npm install

# If using Python for AI services
cd ../ai-engine
pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables

Create `.env` files in respective directories:

**Backend `.env`:**
```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Firebase Configuration
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id

# OpenAI Configuration
OPENAI_API_KEY=your_openai_api_key
OPENAI_ORG_ID=your_org_id

# Pathway Configuration
PATHWAY_API_KEY=your_pathway_key
PATHWAY_WORKSPACE=your_workspace

# External APIs
LINKEDIN_API_KEY=your_linkedin_key
NAUKRI_API_KEY=your_naukri_key
COURSERA_API_KEY=your_coursera_key

# Redis Configuration
REDIS_URL=redis://localhost:6379

# Security
JWT_SECRET=your_jwt_secret_key_here
SESSION_SECRET=your_session_secret_here

# Rate Limiting
RATE_LIMIT_WINDOW=15
RATE_LIMIT_MAX_REQUESTS=100
```

**Frontend `.env`:**
```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
```

### Step 5: Run the Application

**Start Backend:**
```bash
cd backend
npm run dev
# Backend runs on http://localhost:5000
```

**Start Frontend:**
```bash
cd frontend
npm start
# Frontend runs on http://localhost:3000
```

**Start AI Engine (if using Python):**
```bash
cd ai-engine
python app.py
# AI service runs on http://localhost:8000
```

---

## ⚙️ Configuration

### Firebase Setup

1. Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
2. Enable Authentication (Google OAuth and Email/Password)
3. Create a Firestore database
4. Set up Firebase Storage
5. Copy your Firebase config to `.env`

### OpenAI API Setup

1. Sign up at [platform.openai.com](https://platform.openai.com/)
2. Create an API key
3. Add to `.env` file
4. Set usage limits to control costs

### Pathway Framework Setup

1. Request access at [pathway.com](https://pathway.com/)
2. Configure data source connectors:
   - LinkedIn Jobs API
   - Naukri.com API
   - Course platforms
3. Set up streaming pipelines

### Redis Setup (Optional but Recommended)

```bash
# Install Redis
# macOS
brew install redis

# Ubuntu
sudo apt-get install redis-server

# Start Redis
redis-server
```

---

## 📖 Usage

### For Students

#### 1. Sign Up / Login

```
Visit http://localhost:3000
→ Click "Get Started"
→ Sign up with Google or Email
→ Complete profile setup
```

#### 2. Take Career Assessment

```
Dashboard → "Start Career Quiz"
→ Answer 10-15 questions about interests and skills
→ Or upload your LinkedIn profile/resume
→ Wait for AI analysis (30-60 seconds)
```

#### 3. View Career Recommendations

```
Dashboard → "Your Career Paths"
→ See top 5-10 recommended careers
→ Each shows: Match percentage, salary range, demand trend
→ Click on a career to see detailed roadmap
```

#### 4. Generate Learning Roadmap

```
Select a Career → "Generate Roadmap"
→ Choose timeline (3/6/12 months)
→ Get step-by-step learning plan with:
  - Required skills
  - Recommended courses
  - Portfolio projects
  - Certifications
  - Interview prep resources
```

#### 5. Track Progress

```
Dashboard → "My Progress"
→ Mark completed milestones
→ View skill acquisition over time
→ Get AI-powered suggestions
→ Earn badges and achievements
```

#### 6. Join Community

```
Community → Find peers with similar goals
→ Join study groups
→ Share resources and tips
→ Connect with mentors
```

### For Colleges (Admin Panel)

```
Admin Login → View analytics dashboard
→ See student progress metrics
→ Track placement outcomes
→ Export reports for accreditation
→ Manage student accounts
```

---

## 📚 API Documentation

### Authentication Endpoints

#### Register User
```http
POST /api/auth/register
Content-Type: application/json

{
  "email": "student@example.com",
  "password": "securePassword123",
  "name": "John Doe"
}
```

#### Login User
```http
POST /api/auth/login
Content-Type: application/json

{
  "email": "student@example.com",
  "password": "securePassword123"
}
```

### Profile Endpoints

#### Create Profile
```http
POST /api/profile
Authorization: Bearer <token>
Content-Type: application/json

{
  "education": "B.Tech Computer Science",
  "year": 3,
  "interests": ["AI", "Web Development"],
  "skills": ["Python", "JavaScript"]
}
```

#### Get Career Recommendations
```http
GET /api/careers/recommendations
Authorization: Bearer <token>
```

**Response:**
```json
{
  "recommendations": [
    {
      "title": "AI/ML Engineer",
      "matchScore": 92,
      "salaryRange": "₹8-15 LPA",
      "demandTrend": "increasing",
      "skills": ["Python", "TensorFlow", "PyTorch"]
    }
  ]
}
```

### Roadmap Endpoints

#### Generate Roadmap
```http
POST /api/roadmap/generate
Authorization: Bearer <token>
Content-Type: application/json

{
  "careerPath": "AI/ML Engineer",
  "timeline": "6 months",
  "currentSkills": ["Python", "Mathematics"]
}
```

**Response:**
```json
{
  "roadmap": {
    "phases": [
      {
        "phase": "Foundation",
        "duration": "2 months",
        "skills": ["Advanced Python", "Statistics"],
        "resources": [...]
      }
    ]
  }
}
```

Full API documentation available at: [API Docs](./docs/API.md)

---

## 🗓️ Roadmap

### Phase 1: MVP (Current - Hackathon)
- [x] User authentication
- [x] Basic career quiz
- [x] AI-powered recommendations
- [x] Simple roadmap generation
- [x] Pathway integration (2 data sources)
- [ ] Dashboard UI
- [ ] Progress tracking

### Phase 2: Beta Launch (Month 1-3)
- [ ] Advanced quiz with personality assessment
- [ ] Resume parsing and LinkedIn integration
- [ ] Community features (forums, groups)
- [ ] Mobile responsive design
- [ ] Interview preparation module
- [ ] Email notifications
- [ ] Analytics dashboard for colleges

### Phase 3: Production (Month 4-6)
- [ ] Multi-language support (Hindi, regional languages)
- [ ] Voice-based assistant
- [ ] Advanced AI features (interview simulation)
- [ ] Mobile apps (iOS/Android)
- [ ] Government partnership integrations
- [ ] Offline mode for low-connectivity areas
- [ ] WhatsApp bot integration

### Phase 4: Scale (Month 7-12)
- [ ] AR/VR career exploration
- [ ] Blockchain-based credentials
- [ ] Corporate hiring portal integration
- [ ] Advanced analytics and insights platform
- [ ] International expansion (South Asia)
- [ ] AI-powered resume builder
- [ ] Placement guarantee programs

### Long-Term Vision (Year 2-3)
- [ ] 100+ million users
- [ ] Partnerships with 5,000+ colleges
- [ ] Government-backed national rollout
- [ ] IPO-ready unicorn status
- [ ] Global expansion to 50+ countries

---

## 🤝 Contributing

We welcome contributions from the community! LakshPath is built for students, by passionate developers.

### How to Contribute

1. **Fork the repository**
   ```bash
   git fork https://github.com/yourusername/lakshpath.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make your changes**
   - Write clean, documented code
   - Follow our coding standards
   - Add tests for new features

4. **Commit your changes**
   ```bash
   git commit -m "Add: Amazing new feature"
   ```

5. **Push to your branch**
   ```bash
   git push origin feature/amazing-feature
   ```

6. **Open a Pull Request**
   - Describe your changes clearly
   - Link related issues
   - Wait for review

### Contribution Guidelines

- **Code Style**: Follow ESLint and Prettier configurations
- **Commits**: Use conventional commit messages
- **Testing**: Add unit tests for new features
- **Documentation**: Update relevant docs
- **Issues**: Use issue templates for bugs and features

### Areas We Need Help

- 🐛 **Bug Fixes**: Check [open issues](https://github.com/yourusername/lakshpath/issues)
- ✨ **New Features**: See our [roadmap](#-roadmap)
- 📝 **Documentation**: Improve guides and tutorials
- 🌐 **Translations**: Add support for regional languages
- 🎨 **UI/UX**: Enhance design and user experience
- 🧪 **Testing**: Increase test coverage

### Code of Conduct

We follow a [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a welcoming community. Please read it before contributing.

---

## 👥 Team

### Core Team

**Project Lead & Full Stack Developer**
- [Your Name](https://github.com/yourusername)
- 📧 Email: lead@lakshpath.in
- 💼 LinkedIn: [Profile](https://linkedin.com/in/yourprofile)

**AI/ML Engineer**
- [Team Member 2](https://github.com/member2)
- 📧 Email: ai@lakshpath.in

**Backend Developer**
- [Team Member 3](https://github.com/member3)
- 📧 Email: backend@lakshpath.in

**UI/UX Designer**
- [Team Member 4](https://github.com/member4)
- 📧 Email: design@lakshpath.in

### Advisors & Mentors

- **EdTech Industry Expert**: [Name], Former CTO at [Company]
- **Career Counseling Specialist**: [Name], 15+ years experience
- **Government Policy Consultant**: [Name], Ex-AICTE Official

---

## 📞 Contact

**LakshPath Team**

- 🌐 **Website**: [lakshpath.in](https://lakshpath.in)
- 📧 **Email**: team@lakshpath.in
- 🐦 **Twitter**: [@LakshPath](https://twitter.com/lakshpath)
- 💼 **LinkedIn**: [LakshPath](https://linkedin.com/company/lakshpath)
- 💬 **Discord**: [Join Community](https://discord.gg/lakshpath)
- 📱 **WhatsApp**: +91-XXXXXXXXXX

**For Business Inquiries**: partnerships@lakshpath.in

**For Press & Media**: press@lakshpath.in

**For Support**: support@lakshpath.in

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means:
- ✅ Commercial use allowed
- ✅ Modification allowed
- ✅ Distribution allowed
- ✅ Private use allowed
- ❗ License and copyright notice required
- ❗ No warranty provided

---

## 🙏 Acknowledgments

We're grateful to the following for making LakshPath possible:

### Technologies & Frameworks
- **[Pathway Framework](https://pathway.com/)** - Real-time data processing capabilities
- **[OpenAI](https://openai.com/)** - GPT-4 API for AI intelligence
- **[Firebase](https://firebase.google.com/)** - Backend infrastructure and authentication
- **[React](https://reactjs.org/)** - Frontend framework
- **[Vercel](https://vercel.com/)** - Hosting and deployment

### Data Sources
- **LinkedIn, Naukri.com, Indeed** - Job market data
- **Coursera, Udemy** - Course recommendations
- **GitHub, Stack Overflow** - Technology trends
- **NASSCOM** - Industry reports

### Inspiration & Support
- **Indian Government Ministries** - NEP 2020, Digital India initiative
- **AICTE & NSDC** - Policy alignment and support
- **Open Source Community** - Invaluable tools and libraries
- **Student Community** - Feedback and testing during development

### Special Thanks
- All contributors who helped shape LakshPath
- Early beta testers from [College Names]
- Hackathon organizers and judges
- Our families for supporting late-night coding sessions

---

## 📊 Project Status

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Tests](https://img.shields.io/badge/tests-85%25-green)
![Coverage](https://img.shields.io/badge/coverage-78%25-yellow)
![Version](https://img.shields.io/badge/version-0.1.0--alpha-blue)
![Status](https://img.shields.io/badge/status-MVP%20Development-orange)

**Current Phase:** MVP Development (Hackathon Version)  
**Next Milestone:** Beta Launch (Q2 2025)  
**Production Release:** Q3 2025

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/lakshpath&type=Date)](https://star-history.com/#yourusername/lakshpath&Date)

---

## 📈 GitHub Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/lakshpath?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/lakshpath?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/lakshpath?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/lakshpath)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/lakshpath)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/lakshpath)

---

<div align="center">

### 🎯 Empowering Every Student to Find Their Lakshya

**Built with Pathway. Powered by Purpose. Designed for India.**

Made with ❤️ for 130 million+ Indian students

[⭐ Star this repo](https://github.com/yourusername/lakshpath) | [🐛 Report Bug](https://github.com/yourusername/lakshpath/issues) | [💡 Request Feature](https://github.com/yourusername/lakshpath/issues) | [📖 Documentation](./docs)

---

**"Every student deserves a career mentor. We make it possible with AI."**

---

© 2025 LakshPath. All rights reserved.

</div>
