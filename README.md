# 📄 PaperFinder (Looker)

A full-stack research paper and patent discovery platform where researchers, students, and professionals can **publish** and **discover** academic papers across any domain.

## 🏗️ Architecture

| Layer | Technology |
|-------|-----------|
| **Frontend** | Next.js 14 (React) |
| **Backend** | Python FastAPI |
| **Database** | Supabase (PostgreSQL) |
| **Auth** | Supabase Auth (Email + Google OAuth) |
| **Storage** | Supabase Storage (PDF uploads) |
| **Frontend Hosting** | Vercel |
| **Backend Hosting** | Render |

## 📁 Project Structure

```
├── frontend/    # Next.js React application
├── backend/     # Python FastAPI server
└── README.md
```

## 🚀 Getting Started

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

## ✨ Features

- 🔍 Search papers across any academic domain
- 📝 Publish research papers and patents
- 📄 PDF upload and viewing
- 🔐 Authentication (Email + Google OAuth)
- 👤 User profiles and dashboards
- 🏷️ Domain/field categorization
- 📊 Paper analytics (view counts)

## 📄 License

MIT
