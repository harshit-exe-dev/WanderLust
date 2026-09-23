# WanderLust 🌍

A full-stack travel listing web application with secure authentication, interactive maps, image uploads, and reviews.

## ✨ Features
- 🔐 User authentication & authorization
- 🗺️ Interactive maps with Mapbox
- 📸 Image uploads with Cloudinary
- ⭐ Review system with ratings
- 🛠️ Full CRUD functionality for listings
- 📱 Responsive design

## 🛠️ Tech Stack
- **Frontend:** EJS, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Services:** Cloudinary, Mapbox

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- MongoDB running locally or Atlas URI
- Cloudinary & Mapbox API keys

### Installation
1. Clone the repo
   ```bash
   git clone https://github.com/harshit-exe-dev/WanderLust.git
   cd WanderLust
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Create `.env` file with your credentials
   ```
   CLOUDINARY_CLOUD_NAME=your_name
   CLOUDINARY_KEY=your_key
   CLOUDINARY_SECRET=your_secret
   MAPBOX_TOKEN=your_token
   DB_URL=your_mongodb_url
   SECRET=your_session_secret
   ```
4. Run the app
   ```bash
   node app.js
   ```
   Visit `http://localhost:8080`

## 📝 License
This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author
**Harshit Bharti** - [@harshit-exe-dev](https://github.com/harshit-exe-dev)
