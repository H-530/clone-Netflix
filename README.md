<p align="center">
  <img src="https://img.icons8.com/?size=100&id=OGorCfaq39bR&format=png&color=000000" alt="Netflix Clone Demo" width="100%">
</p>

# 🎬 Netflix Clone

<p align="center">
  <strong>A full-stack clone-Netflix streaming application built with modern web technologies.</strong>
</p>

---

## ✨ Features

- ⚛️ **Full-Stack Application** — React.js, Node.js, Express.js, MongoDB & Tailwind CSS
- 🔐 **JWT Authentication**
- 📱 **Fully Responsive Design**
- 🎬 **Browse Movies & TV Shows**
- 🔎 **Search Movies, TV Shows & Actors**
- 🎥 **Watch Movie & TV Show Trailers**
- 🔥 **Search History**
- 🎯 **Similar Movies & TV Shows**
- 💙 **Modern Netflix-Inspired Landing Page**
- 🌐 **Production Ready**
- 🚀 **Easy Deployment**

---

## 🛠️ Tech Stack

| Technology | Description |
| --- | --- |
| ⚛️ React.js | Frontend library |
| 🟢 Node.js | Backend runtime |
| 🚂 Express.js | Backend framework |
| 🍃 MongoDB | NoSQL database |
| 🎨 Tailwind CSS | Utility-first CSS framework |
| 🔐 JWT | Authentication |
| 🎬 TMDB API | Movies, TV shows & actor data |

---

## 📸 Preview

<p align="center">
  <img src="./frontend/public/screenshot-for-readme.png" alt="Netflix Clone Screenshot">
</p>

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

⚠️ Important: Never commit your .env file or expose your API keys and secrets publicly.

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-clone.git
```

2. Navigate to the project
```bash
cd netflix-clone
```

3. Install dependencies
```bash
npm install
```


## 📂 Project Structure

```text
netflix-clone/
│
├── frontend/
│   ├── public/
│   │   └── screenshot-for-readme.png
│   └── src/
│
├── backend/
│   └── src/
│
├── .env
├── package.json
└── README.md
```

## 🌐 Deployment

The application can be built for production using:
```bash
npm run build
```

Then start the production server with:
```bash
npm run start
```

## 🔐 Security

Make sure sensitive information is never committed to Git.
Add `.env` to your `.gitignore`:
```text
.env
node_modules/
```

## 📄 License

This project was created for educational and learning purposes.
