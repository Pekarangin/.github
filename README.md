# 🌱 Pekarang.in

**Smart Urban Farming Recommendation Platform**

Pekarang.in is an intelligent urban farming platform designed to help households optimize their limited outdoor spaces into productive food gardens.

We believe that growing food at home should be accessible to everyone, regardless of land availability or agricultural experience. By combining land condition analysis, AI-powered plant recommendations, and cultivation management, Pekarang.in helps users make informed decisions about what to grow, how to grow it, and the potential economic benefits of their harvest.

---

## 🎯 About The Project

Limited land availability, lack of agricultural knowledge, and fluctuating food prices are some of the challenges faced by urban households who want to grow their own food.

Many people have unused yards or small outdoor spaces but do not know which crops are suitable for their land conditions or how to manage cultivation effectively.

**Pekarang.in aims to bridge this gap** by providing a data-driven urban farming solution that connects land characteristics, household needs, plant suitability, and food commodity prices into one integrated platform.

The platform is designed for urban and semi-urban households, including beginners who have little to no experience in gardening.

## ✨ Key Features

### 1. Land Management
- Register and manage personal gardening areas.
- Upload land photos to support light condition analysis.
- Create a manual grid-based layout to organize planting areas.
- Manage available planting space efficiently.

### 2. AI-Powered Plant Recommendations
- Analyze sunlight exposure using AI-powered image analysis.
- Classify land conditions into Full Sun, Partial Sun, and Shade.
- Generate plant recommendations based on land characteristics and cultivation suitability.
- Provide contextual information to help users understand why certain plants are recommended.

### 3. Cultivation Planning
- Select recommended plants for cultivation.
- Organize planting plans based on available land.
- Access cultivation guidelines and plant information.
- Track planting activities through a structured cultivation schedule.

### 4. Cultivation Monitoring
- Monitor cultivation progress through interactive checklists.
- Track essential activities such as watering, fertilizing, and harvesting.
- Receive reminders for scheduled cultivation activities.

### 5. Food Price & Savings Estimation
- Access food commodity price information.
- View estimated harvest value and potential household savings.
- Understand the potential economic benefits of growing food independently.

### 6. Dashboard
- View an overview of managed gardening areas.
- Monitor ongoing cultivation activities.
- Track harvest records and estimated savings.

---

## 🔄 How It Works

Pekarang.in provides an integrated workflow that guides users from identifying available land to monitoring their cultivation activities.

1. **Create an Account** — Users register and provide basic information about their household and gardening needs.
2. **Register Your Land** — Users add their available gardening space and upload land photos.
3. **Analyze Land Conditions** — AI analyzes sunlight exposure to identify suitable growing conditions.
4. **Get Plant Recommendations** — The system recommends suitable crops based on available land conditions and relevant cultivation data.
5. **Plan Your Garden** — Users select plants and organize their planting areas using a grid-based layout.
6. **Monitor Cultivation** — Users track watering, fertilizing, and harvesting activities through checklists and reminders.
7. **Track Your Benefits** — Users view harvest information and estimated potential household savings.

---

## 🛠️ Technology & Architecture

Pekarang.in integrates a backend API, relational database, and AI services to support its core functionality.

| Component | Technology |
|---|---|
| Database | PostgreSQL |
| AI Integration | Google Gemini API |
| Backend Communication | REST API |
| AI Image Analysis | Gemini Vision |

### System Architecture

The platform follows a backend-centered architecture:

```text
          User Interface
                |
                v
          Backend API
                |
       +--------+--------+
       |                 |
       v                 v
   PostgreSQL        Gemini API
       |                 |
       +--------+--------+
                |
                v
        Processed Results
                |
                v
          User Interface
```

**Architecture Principles:**
- PostgreSQL serves as the primary source of truth for application data.
- The backend handles business logic, data validation, and AI service orchestration.
- Gemini API supports image analysis and AI-powered recommendations.
- AI API credentials are securely managed on the backend and are never exposed to the client.

---

## 🌾 Initial Product Scope

The initial implementation focuses on supporting 15 food commodities:

- Chili
- Shallots
- Tomatoes
- Spinach
- Water Spinach
- Lettuce
- Mustard Greens
- Carrots
- Eggplants
- Long Beans
- Cucumbers
- Bitter Melons
- Basil
- Spring Onions
- And other supported food crops.

The initial target implementation focuses on households in urban and semi-urban environments, starting with the Special Region of Yogyakarta (DIY).

---

## 🎯 Our Mission

To make urban food cultivation more accessible, practical, and economically meaningful by helping households transform underutilized land into productive food sources.

We envision a future where even the smallest yard can contribute to household food resilience.

---

## 👥 Project Information

**Project Name:** Pekarang.in  
**Category:** Agriculture Technology / Urban Farming  
**Program:** MAGE 12  
**Focus:** AI-Powered Urban Farming Recommendation Platform

---

<p align="center">
  🌱 <strong>Grow Smarter, Harvest Better.</strong>
  <br/>
  <i>Making every yard a productive space.</i>
</p>
