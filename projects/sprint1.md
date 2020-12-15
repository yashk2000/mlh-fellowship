---
title: Sprint 1 Project
layout: page
---

# Mentored

## 🙋 What is Mentored?
Mentored intends to be a single, unified platform for people new to the technology and software development to find curated, high-quality resources for their topics of interest from industry experts and real software developers. 👨‍💻

But that's not all, this platform is built to facilitate real learning with mentorship, allowing mentees to find mentors to learn skills and build up their portfolio. ✨

## 💡 Why did we build it?
Remember the first time you started off with tech? The vast internet at your fingertips but it's the first step that's always the hardest. 😓

With Mentored, anyone (even you!) can easily find free resources curated in a single place from industry experts instead of crawling the internet. What's better? You can contact real mentors, software developers and engineers, and contact them to seek guidance. Sounds good? Of course, it is. 🌟

In fact, it doesn't stop there. Mentored allows real people to mentor the future generation of developers and point them to right direction, making sure they can (to take words from our friends at MLH) truly level up. 🆙

## 🌐 Where can you find it?
Find us on [mentored-space.herokuapp.com](https://mentored-space.herokuapp.com)! Too long to type, fret not, we are moving soon to [mentored.space](https://mentored.space)! 🌠

## 💻 What did we use?
Mentored has a ReactJS frontend ⚛️ hosted with Heroku, and a Django backend 🐍 backed by PostgreSQL hosted on Google Cloud Platform. The UI is based on React Bootstrap, while the Cloud Run backend uses `psycopg2` for communicating with Cloud SQL. 💽

## ➕ Features
### 🐳 Containerized
All our deployments  are containerized using Docker and images are used to deploy revisions, allowing for easy traffic management and A/B testing.
### ☁️ Scalable
Cloud SQL and Cloud Run instances on GCP are configured to handle multitudes of requests when required and be highly fail-safe.
### 🔒 Secure
All data is stored on the cloud and sensitive data like passwords are additionally hashed and salted with PBKDF2-SHA256.
### ⚡ Seamless
The project is deployed automatically from our codebase on GitHub to GCP Cloud Build seamlessly.


## Link to project

[https://github.com/yashk2000/Mentored](https://github.com/yashk2000/Mentored)