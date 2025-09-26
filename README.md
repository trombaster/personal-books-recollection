# Personal Book Recollection - Social Reading Tracker

*A Flask-based web application that transforms reading from a solitary activity into a shared journey*

## Overview

Personal Book Recollection helps readers document their literary journey while connecting with fellow book lovers. More than just a reading log - it's a space where books become shared experiences and reading becomes a collective adventure.

## MVP Features

### Personal Reading Management
- Digital Library Builder: Easily add books using Google Books API integration
- Smart Book Details: Automatic cover images, descriptions, and author information
- Reading Journal: Capture personal reflections with reviews and ratings
- Progress Tracking: Visualize your reading accomplishments

### Social Discovery
- Friend Libraries: Explore what others are reading and discover new books
- Reading Path Sharing: Follow friends' literary journeys and get inspired
- Community Insights: See popular books and ratings within your network

### Accessibility 
- Mobile-First Design: Optimized for seamless use on any device
- Instant Setup: Simple registration and intuitive interface
- Always Available: Cloud-deployed and accessible anywhere

## Tech Stack

- Backend: Python, Flask, Flask-Login, Flask-SQLAlchemy
- Frontend: Jinja2, Bootstrap 5, Responsive CSS
- Database: PostgreSQL (production), SQLite (development)
- APIs: Google Books API for book data
- Deployment: Render.com with gunicorn
- Authentication: Secure session-based login system

## Quick Start

```bash
# Clone and setup
git clone https://github.com/yourusername/personal-book-recollection
cd personal-book-recollection
pip install -r requirements.txt

# Run locally
python app.py
```
