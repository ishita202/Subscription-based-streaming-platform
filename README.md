# Subscription-based-streaming-platform

Hey there! 👋  
Welcome to my podcast streaming platform — a simple, full-stack web application including some applications of data science where users can stream podcasts, subscribe to premium content, and explore recommended episodes.

This project was built with love using **Django**, **Django REST Framework**, **HTML/CSS/JS**, and a touch of FFmpeg magic for audio streaming.

PowerBI was used to showcase the insights of the user usage and the admin panel. Since the project was not fully completed and made public so a sample dataset was used to create the dashboards and gain insights.

---

## 🚀 Features

- 🎙️ Upload & stream podcast episodes
- 🧑‍💼 Admin panel to manage content
- 🔒 User authentication (Login/Signup)
- 💳 Subscription plans via Stripe
- 🔁 AI-based podcast recommendations
- 📊 Analytics dashboard for performance insights
- 📱 Fully responsive frontend (mobile-friendly)

---

## 🛠️ Tech Stack

| Area         | Tech Used                        |
|--------------|----------------------------------|
| Backend      | Python, Django, DRF              |
| Frontend     | HTML, CSS, JavaScript            |
| Database     | SQLite (locally)                 |
| Media        | FFmpeg for audio processing      |
| Payments     | Stripe API                       |
| Auth         | Django auth / JWT                |
| Hosting      | (Currently local, can deploy to Heroku/Vercel) |

---

## 🗂️ Project Structure

```bash
Podcast_Platform/
├── Podcast_Backend/
│   ├── ai_podcast_backend/      # Django project
│   ├── api/                     # All API endpoints
│   ├── authentication/          # User login/signup
│   ├── podcasts/                # Podcast models & views
│   ├── recommendations/         # AI-based content suggestions
│   ├── subscriptions/           # Stripe-based plans
│   ├── media/                   # Uploaded audio files
├── podcast-frontend/            # Frontend HTML/CSS/JS
