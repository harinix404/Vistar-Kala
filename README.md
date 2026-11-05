# Vistar Kala – Heritage Commerce AI Marketplace

**Bridging Traditional Indian Craftsmanship with Digital Commerce**

Vistar Kala is an AI-powered digital marketplace designed to empower traditional Indian artisans and micro-entrepreneurs by connecting them with buyers and B2B businesses. The platform combines artificial intelligence, digital commerce, and heritage storytelling to help artisans showcase their products, improve their market reach, and access new business opportunities.

---

## 1. Project Overview

Traditional artisans often face challenges such as limited market access, lack of digital visibility, pricing difficulties, and language barriers.

Vistar Kala aims to address these challenges through an integrated digital platform that provides:

- AI-powered assistance for artisans.
- Digital product cataloguing and marketplace listings.
- Direct B2B connections between artisans and buyers.
- Heritage storytelling and product discovery.
- Multilingual accessibility.

## 2. Key Features

### Artisan Portal
A dedicated workspace for artisans to manage their products and digital presence.

- Artisan registration and login.
- Product listing and management.
- AI-assisted product descriptions.
- Product image processing and enhancement.
- Pricing suggestions.
- Product catalogue management.

### AI Artisan Studio
AI-powered tools designed to simplify product creation and marketing.

- Image-to-description generation.
- Product information extraction.
- Description translation.
- AI-assisted pricing suggestions.
- Improved product presentation.

### B2B Marketplace
A dedicated portal connecting artisans with wholesale buyers and businesses.

- Categorized product sourcing.
- B2B product catalogue.
- AI-enhanced product information.
- Heritage stories.
- GI certification information.
- Direct artisan-buyer communication.

### Sahayak AI
An AI assistant designed to help users navigate the platform and access relevant information.

### Multilingual Support
The platform supports:
- English
- Telugu

### Additional Features
- User authentication.
- Product discovery.
- Orders interface.
- Guest mode.
- Online synchronization indicator.

## 3. Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML, JavaScript |
| Styling | Tailwind CSS |
| Backend | Node.js |
| Backend Framework | Express.js |
| Database | SQLite |
| Authentication | JWT, bcrypt |
| Image Management | Cloudinary |
| API Communication | REST APIs |
| Development Environment | Antigravity IDE |

## 4. Project Structure

```text
Vistar-Kala-main/
│
├── vistar-kala-backend/
│   ├── data/
│   ├── uploads/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── app.js
│   │   ├── seed.js
│   │   └── server.js
│   │
│   ├── .env.example
│   ├── package.json
│   └── README.md
│
└── vistar-kala-frontend/
    ├── js/
    │   ├── api.js
    │   ├── chat.js
    │   ├── extract_safe.js
    │   ├── extract.js
    │   ├── main.js
    │   ├── product.js
    │   └── ui.js
    │
    ├── index.html
    └── warli.png
```

## 5. Installation and Setup

Follow these instructions to run Vistar Kala locally.

### Prerequisites

Install the following:

- Node.js (LTS version)
- npm
- Antigravity IDE or VS Code
- Five Server extension (for frontend development)

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate into the project:

```bash
cd Vistar-Kala-main
```

### Step 2: Configure the Backend

Navigate to the backend directory:

```bash
cd vistar-kala-backend
```

Install dependencies:

```bash
npm install
```

Configure environment variables using the provided `.env.example` file.

Create a `.env` file and configure the required values according to your project setup.

### Step 3: Initialize Demo Data

Run the seed command:

```bash
npm run seed
```

This initializes the database with demo data.

### Step 4: Start the Backend Server

```bash
npm start
```

The backend server runs on:

```text
http://localhost:4000
```

Successful startup should display:

```text
Database connected (sqlite) and synced.
Vistar Kala backend listening on port 4000
```

### Step 5: Start the Frontend

1. Open `vistar-kala-frontend` in Antigravity.
2. Open `index.html`.
3. Right-click the file.
4. Select **Open with Five Server**.

The frontend will be accessible at an address similar to:

```text
http://127.0.0.1:5500/vistar-kala-frontend/index.html
```

**Important:** Keep the backend terminal running while using the application.

## 6. Demo Login Credentials

The following demo accounts are created by the seed script.

| Account | Phone Number | Password |
|---|---|---|
| Artisan | 9999999999 | artisan123 |
| B2B Buyer | 8888888888 | buyer1234 |

These credentials are intended for local testing and demonstration only.

## 7. Database

Vistar Kala uses SQLite for data storage.

The backend automatically connects to and synchronizes the database when the server starts.

Demo products and initial records can be populated using:

```bash
npm run seed
```

## 8. API Documentation

The backend API documentation is available in:

```text
vistar-kala-backend/API_DOCUMENTATION.md
```

The repository also includes a Postman collection for API testing:

```text
Vistar-Kala-API.postman_collection.json
```

## 9. Project Objectives

- Empower traditional Indian artisans through digital technology.
- Improve market accessibility for micro-entrepreneurs.
- Simplify product marketing using AI.
- Connect artisans with wholesale buyers.
- Preserve and promote India's traditional craftsmanship.
- Build an inclusive and accessible digital commerce ecosystem.

## 10. Future Scope

- Advanced AI-based product recommendations.
- More regional language support.
- Expanded artisan and buyer analytics.
- Improved digital payment integration.
- Enhanced logistics and order tracking.
- Wider integration with artisan communities and marketplaces.

## 11. Contributors

Developed as a project focused on **Cybersecurity, Digital Trust, AI, and Digital Commerce**.

---

**Vistar Kala – Preserving Heritage, Empowering Artisans, Connecting Markets.**
