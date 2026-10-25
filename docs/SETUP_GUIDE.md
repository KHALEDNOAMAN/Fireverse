# Fireverse - Setup Guide

## Overview
Real-time chat application built with React, TypeScript, Firebase, and Tailwind.

## Features
| Feature | Description |
|---------|-------------|
| Real-time Chat | Instant messaging with Firestore |
| Authentication | Google/Email sign-in via Firebase Auth |
| Responsive | Mobile-first design with Tailwind |
| TypeScript | Full type safety |

## Setup
```bash
git clone https://github.com/grwth404/Fireverse.git
cd Fireverse
npm install
```

## Firebase Configuration
1. Create project at [console.firebase.google.com](https://console.firebase.google.com)
2. Enable Authentication (Google provider)
3. Create Firestore database
4. Copy config to `.env`:

| Variable | Description |
|----------|-------------|
| VITE_API_KEY | Firebase API key |
| VITE_AUTH_DOMAIN | Auth domain |
| VITE_PROJECT_ID | Project ID |
| VITE_STORAGE_BUCKET | Storage bucket |

```bash
npm run dev
```