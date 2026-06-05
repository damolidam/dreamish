# dreamish
A Progressive Web App for AI-supported dream journaling and interpretation.
## What it does
Users describe their dreams in free text (Turkish or English). The app analyzes the dream through a Jungian archetypal framework using LLaMA-3.3-70B, returns an archetype, emotional tone, interpretation, affirmation, and mindfulness suggestion, and generates a dream visual. Dreams are saved to a personal diary with calendar view. Therapists can connect with users via a code-based system and review emotional and archetypal patterns over time.
## Tech stack
Vanilla JS + HTML/CSS (single-file PWA), Supabase for auth and database, Groq API with LLaMA-3.3-70B-versatile, Pollinations.ai Flux model for image generation, Netlify for deployment and serverless functions.
## ML pipeline
BERT-based semantic clustering (all-MiniLM-L6-v2, K=5) and LLM-based Jungian archetypal analysis on the Sleep and Dream Database, validated in the academic report.
## Live demo
[dreamish.netlify.app](https://dreamish.netlify.app)
## Academic context
ISL 492E Management Engineering Design Project, Istanbul Technical University, 2025–2026. Damla Baklacı & Dilan Kaplan.
