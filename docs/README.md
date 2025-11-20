---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e21-co227-PeraVerse-Event-List-Page
title: Event List Page of PeraVerse's Dynamic Schedule Board
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Event List Page of PeraVerse




<!-- 
This is a sample image, to show how to add images to your page. To learn more options, please refer [this](https://projects.ce.pdn.ac.lk/docs/faq/how-to-add-an-image/)

![Sample Image](./images/sample.png)
 -->

## Team
-  E/21/442, Wijenayaka D.L.P.A., e21442@eng.pdn.ac.lk
-  E/21/289, Perera I.S.A, e21289@eng.pdn.ac.lk
-  E/21/068, Chandrasiri E.M.D.D.V., e21068@eng.pdn.ac.lk
-  E/21/328, Rathnayaka R.M.P.M., e21328@eng.pdn.ac.lk

## Supervisors
-  Ms. Yasodha Vimukthi, yasodhav@eng.pdn.ac.lk

## Table of Contents
1. [Introduction](#introduction)
2. [Solution & Impact](#solution--impact)
3. [Features & Architecture](#Features--Architecture)
4. [How to Run / Development Notes](#how-to-run--development-notes)
5. [Links](#links)

---

## Introduction

 This is a full-stack event management web application developed as a comprehensive platform for browsing and interacting with events.

Our team was responsible for building the Events Dashboard with interactive features, which serves as the user's main interaction point for viewing detailed event information, marking attendance, rating events, commenting, and filtering by categories. This application is fully responsive, cloud-ready, and connected to a real backend API with Supabase database integration.

## Solution & Impact

The Event List Page provides:

- Clear interface for exploring event information
- Dynamic attendance system
- Real-time updates for attendance counts and attendee lists
- Interactive rating system with 1-5 stars and averages
- Comprehensive comment system for feedback
- Category-based filtering for event discovery
- Direct Supabase integration for instant synchronization
- Modern, cloud-hosted full-stack experience

## Features & Architecture

Key Features:
- Event Cards with title, time, venue, categories
- Category filters + real-time search
- Attendance: mark/unmark, live count, attendee list
- Ratings: 1–5 stars, average rating, prevent duplicates
- Comments: add, edit, delete, real-time sync

Architecture Overview:
- **Frontend:** React + Vite, Tailwind CSS + Bulma, reusable components, Supabase client
- **Backend:** Node.js + Express, routes for events, categories, attendance, ratings, comments
- **Database:** Supabase PostgreSQL (events, categories, attendance, comments, ratings)
- **Deployment:** Cloud-ready frontend & backend, Supabase database, .env-based config

## How to Run / Development Notes

1.Clone Repository

```bash
git clone https://github.com/cepdnaclk/e21-co227-PeraVerse-Event-List-Page.git
cd e21-co227-PeraVerse-Event-List-Page
```
2.Install Dependencies

Frontend

```bash
cd frontend/dashboard
npm install
npm run dev
```
Backend

```bash
cd backend
npm install
npm start
```
Environment Variables Edit .env file inside the backend:
```bash
SUPABASE_URL="Your Supabase URL"
SUPABASE_ANON_KEY="Your Supabase Anon Key"
SUPABASE_SERVICE_KEY="Your Supabase Service Key"
NODE_ENV=development
PORT=3000
```

Deployment:
- Start backend on http://localhost:3000
- Start frontend on http://localhost:5173
- Navigate to the Event List Page
## Links

- [Project Repository](https://github.com/cepdnaclk/e21-co227-PeraVerse-Event-List-Page)
- [Project Page](https://cepdnaclk.github.io/page.e21-co227-PeraVerse-Event-List-Page)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
