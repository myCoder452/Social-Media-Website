# LinkUp - Modern News Aggregation Platform - Social Media Website
Social Media Website Project.

## 🌟 Project Overview
A full-stack Django-powered news aggregator combining real-time content curation with social networking features. Designed for readers who want personalized news experiences with community interaction.

## 🚀 Key Features
- **Multi-Source News Aggregation**  
  Curate articles from RSS feeds & APIs with automatic categorization
- **Social Engagement**  
  - Like/Save articles with AJAX interactions
  - Nested comment system with real-time updates
  - User profiles with follower relationships
- **AI-Powered Moderation**  
  Integrated Perspective API for toxic comment detection
- **Responsive Design**  
  Bootstrap-powered interface with custom CSS animations
- **Advanced Search**  
  Full-text search across articles and user-generated content

## 🛠 Tech Stack
**Core Framework**  
- Django 4.2
- Python 3.10
- Bootstrap 5.3
- PostgreSQL

**Key Components**
- **Authentication**: Django Allauth with social login
- **Async Tasks**: Celery for feed updates & notifications
- **Storage**: AWS S3 for media management
- **Security**: CSRF protection, XSS safeguards
- **API Integration**: NewsAPI | Perspective API
