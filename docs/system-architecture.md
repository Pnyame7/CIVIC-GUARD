# System Architecture

CivicGuard follows a three-tier architecture:

## 1. User Layer (Mobile App)

- Report civic issues
- Upload images and descriptions
- Auto GPS location capture
- Track complaint status

## 2. Admin Layer (Web Application)

- Monitor and manage reports
- View maps of issue locations
- AI-assisted categorization
- Communicate with citizens

## 3. Backend Layer

- Node.js + Express server
- Handles API requests
- Manages authentication and data processing

## 4. AI Layer

- NLP for text analysis
- Image classification for issue detection
- Duplicate detection system

## 5. Database Layer

- SQLite with Drizzle ORM
- Stores users, reports, and system logs
