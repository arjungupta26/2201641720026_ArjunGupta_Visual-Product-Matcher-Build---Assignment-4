### 🖼️ Visual Product Search App

A sleek web application that lets users upload an image and instantly explore similar products.
Designed for a technical challenge, it demonstrates problem-solving ability, clear structure, and practical usability.

# ✨ Key Features
📤 Flexible Image Input

Upload images via drag-and-drop or file picker

Directly paste image URLs for instant checks

Compatible formats: .png, .jpg, .webp

# 🔎 Intelligent Matching

Compare uploaded image with product matches side-by-side

AI-based scoring ensures ranking & accuracy

Sort results by category or relevance score

Mobile and desktop friendly

# 📚 Product Dataset

Includes 50+ preloaded products with detailed metadata

Fields: title, brand, tags, category, description, color palette

Enhanced with AI-driven product insights (Google Gemini AI)

 # 🌟 Smooth UX

Animated loaders while analyzing

Clear and actionable error messages

Clean TailwindCSS-powered design

Simple layout for fast exploration

# 🛠️ Technology
# Frontend

⚛️ Next.js 13 (App Router) + TypeScript

🎨 TailwindCSS styling

🎬 Framer Motion animations

🧩 Radix UI components

## Backend & DB

*🍃 MongoDB with Mongoose ORM*

*⚡ Serverless Next.js API routes*

Optimized lookups using compound + text indexes

# AI Layer

🤖 Google Gemini AI for multi-modal analysis (image + text)

Matching algorithm considers tags, colors, brand, and category relevance

# 🏗️ System Overview

→ A high-level architecture diagram can be presented during discussion
(showing flow: Image Upload → AI Analysis → MongoDB Retrieval → UI Results).

# 🚀 Getting Started
📌 *Requirements*

Node.js ≥ 18

A running MongoDB database (local or Atlas cloud instance)

Google Gemini API Key

# ⚡ Setup

# Clone the project
git clone https://XYZ
cd Image-Analyzing-Tool

# Install dependencies
npm install

⚙️ Environment Variables
# Create .env.local
cp .env.example .env.local


# Add credentials in .env.local:

*MONGODB_URI=your_mongo_connection*
*GEMINI_API_KEY=your_gemini_key*

# 🗄️ Seed Database
node scripts/migrate-products.js

▶️ Run in Development
npm run dev


→ App available at: http://localhost:3000

# 🏭 Production Build
npm run build
npm start