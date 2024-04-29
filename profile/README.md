<img src="https://i.imgur.com/ILwAUY8.png" alt="STUBU" width="300" />

[Documentation]() • [Report a Bug](https://github.com/STUBU-AI/STUBU-CLIENT/issues)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Typscript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

## 📜 **Overview**
An innovative educational platform designed to revolutionize the way people learn. It offers personalized learning experiences tailored to individual needs, making education more engaging and effective.

A platform that allows learners to maximize the existing Artificial Intelligence (AI) through the provision and generation of learning materials; allowing users to have a personalized learning experience based on their goals and interests.

<details>
<summary><b>Table of Contents</b></summary>

1. [About the Project](#overview)

   - [Resources Used](#resources-used)

2. [Getting Started](#-getting-started)

   - [Prerequisites](#-prerequisites)
   - [Installation](#-installation-and-Usage)

3. [Features](#-features)

4. [Contributors](#-contributors)
</details>

####  **Resources Used**

[![Skills](https://skillicons.dev/icons?i=git,github,figma,vite,vscode)](https://skillicons.dev)


## ⚙ **Setting Up**

#### Prerequisites

Before running the application, make sure to install the following:

1. **NodeJS (NPM).**

   Download through their official [docs](https://nodejs.org/en/download).

   ```bash
   npm install npm@latest -g
   ```

2. **Mongo DB**

	Download through their official [docs](https://www.mongodb.com/try/download/community).

## ⚙ **Installation and Usage**

### **Presentation Layer/Frontend:**
#### 1. **Installation**

```bash
# Clone this repository
git clone https://github.com/STUBU-AI/STUBU-CLIENT.git
Upon cloning, navigate to the repo.

# Install NPM packages
npm install
 ```
 
#### 2. Usage:

```bash
# Start the application
npm run dev
 ```

### **API:**
#### 1. **Installation:**

```bash
# Clone this repository
git clone  https://github.com/STUBU-AI/STUBU-API.git
# Upon cloning, navigate to the repo.
# Install NVM packages
nvm install
# Install NPM packages
npm install
# Create a copy of sample .env file
cp .sample.env .env
 ```

#### 2. **Usage:**

```bash
# Run the server
npm start
# Restarts the server on any changes made in the project 
npm run dev
# Run the unit test
npm run test
```

### **RAG Service**
#### 1. **Installation:**

```bash
# Go to OpenAI and create a new API key. Create a .env file and add your OPENAI_API_KEY.
sudo pip3 install -r requirements.txt
```

#### 2. **Usage:**
```bash
#Locally
chroma run
uvicorn app.app:app --port 8001
#Using Docker
docker-compose up -d
```

## ✨ **Features**

| Number | Feature                      | Definition                                                             |
|--------|------------------------------|------------------------------------------------------------------------|
| 1      | Landing Page                 | The initial page users see when they visit the platform.               |
| 2      | Onboarding Page              | A page or series of pages designed to familiarize new users with the platform. |
| 3      | Authentication: Login and Sign-up | The process of verifying the identity of users and allowing them to access the platform by logging in or signing up. |
| 4      | Learner's Personalization    | Customization of the learning experience based on individual user preferences and behavior. |
| 5      | Content Course Generation    | The process of creating/generating custom personalized course content.  |
| 6      | Bookmark Course              | Allowing users to save or bookmark public courses for easy access later. |
| 7      | Upvote Course                | Allowing users to express their approval or appreciation for public courses by voting them up. |
| 8      | Quiz Generation              | The process of generating quizzes or assessments for courses on the platform. |
| 9      | Course Assessment            | Assessments designed to evaluate a learner's understanding and knowledge of course material. |
| 10     | Material Submissing          | The process of submitting materials or resources for a course.          |


## 💪 **Contributors**

We greatly appreciate contributions to this project. Special thanks to the following contributors for their valuable input and efforts:

#### **Backend Team**
- [**Angeline Basbas**](https://github.com/StrayMarimo)
- [**Jiankarlo Belarmino**](https://github.com/CSjianbel)
- [**Albert Perez**](https://github.com/bibookss)

#### **Frontend Team**
- [**Martin Atole**](https://github.com/CS-Martin)
- [**Johcel Gene Bitara**](https://github.com/genebit)
- [**Miguel Damien Garcera**](https://github.com/MD-Garcera)
- [**Noel Emaas**](https://github.com/NoelEmaas)

#### **Mentors**
- Kevin Vega
- Jobb Rodriguez
