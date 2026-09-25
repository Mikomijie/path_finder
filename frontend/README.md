# Pathfinder AI

> Adaptive learning for neurodivergent students in Nigeria

## What is Pathfinder

Pathfinder is an AI powered adaptive learning platform built specifically for secondary school and university students in Nigeria who have ADHD, dyslexia, or slow processing speed. Instead of delivering lessons one way and expecting every student to keep up, Pathfinder explains every concept four different ways and lets each student learn at their own pace with no timers and no pressure.

## The Problem

One in six students in Nigeria is neurodivergent. These students sit in classrooms built for one type of brain. When they struggle, they are labelled lazy or unintelligent. No affordable adaptive learning tool exists in Nigeria designed for how their brain actually works.

## The Solution

Pathfinder gives every student a patient, personalised learning experience. Every lesson is explained through four levels. First a plain simple explanation. Then a real world Nigerian analogy. Then a dynamic visual diagram. Then a reflective question. Students move through levels at their own pace by clicking Explain Differently.

Voice support reads every lesson aloud for dyslexic learners. Teachers upload PDF notes and AI converts them into adaptive micro lessons for every student in their class within seconds.

## Features

- Four level adaptive lesson system tailored for neurodivergent learners
- Full voice support on every lesson, flashcard, and quiz question
- Teacher dashboard with class management and PDF upload
- AI powered lesson generation from any PDF or pasted text
- Student progress tracking with visual journey map
- Quiz system with AI generated questions
- Flashcard system with spaced repetition
- Skills Hub for university students covering time management, focus, and executive function
- Real time student progress visible to teachers
- Works on low bandwidth connections including 2G
- Free for all students

## Tech Stack

- Frontend: React, Tailwind CSS
- Backend: Supabase (authentication, database, edge functions)
- AI: OpenRouter (free tier models)
- Voice: Web Speech API
- Deployment: Vercel

## Live Demo

https://pathfinder-chi-seven.vercel.app

## Getting Started

```bash
git clone https://github.com/Mikomijie/path_finder.git
cd path_finder/frontend
npm install
npm start
```

Create a .env file in the frontend folder with the following:
REACT_APP_SUPABASE_URL=your_supabase_url
REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
REACT_APP_OPENROUTER_KEY=your_openrouter_key

## Target Users

- Secondary school students in Nigeria with ADHD, dyslexia, or slow processing speed
- University students with ADHD who need executive function support
- Teachers who want to create adaptive lessons from their existing materials

## Team

Built by Team Pathfinder for neurodivergent students across Nigeria.