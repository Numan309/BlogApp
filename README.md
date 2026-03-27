# 🚀 AI-Powered Blog Platform (MERN Stack)

An intelligent full-stack blog platform built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**, enhanced with **Google Gemini AI** for content generation and **Image.io (ImageKit/Cloudinary-like service)** for seamless image handling.

This platform allows users to:

* ✍️ Write blogs manually
* 🤖 Generate blogs using AI
* 🔐 Securely authenticate and manage their accounts
* 🖼️ Upload and manage blog images

---

# 🌟 Features

## 👤 User Authentication

* Secure login and registration system
* JWT-based authentication
* Protected routes for authorized actions

## 📝 Blog Management

* Create, edit, and delete blog posts
* Rich content support
* View all blogs or individual blog details

## 🤖 AI Blog Generation

* Integrated **Google Gemini API**
* Users can generate blog content automatically
* Helps in idea generation, drafts, and full blog creation

## 🖼️ Image Upload

* Integrated **Image.io / ImageKit / Cloudinary**
* Upload images for blog posts
* Optimized delivery and storage

## 📱 Responsive UI

* Clean and modern UI built with React
* Mobile-friendly design

---

# 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* React Router DOM

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

### APIs & Services

* Google Gemini API (AI content generation)
* Image.io / ImageKit / Cloudinary (image hosting)

---

# 📁 Project Structure

```
project-root/
│
├── client/              # Frontend (React)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/              # Backend (Node + Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── app.js
│
├── .env
└── README.md
```

---

# ⚙️ Environment Variables

Create a `.env` file in the **server** directory and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

GEMINI_API_KEY=your_google_gemini_api_key

IMAGE_API_KEY=your_image_service_key
IMAGE_API_SECRET=your_image_service_secret
IMAGE_CLOUD_NAME=your_cloud_name
```

---

# 🚀 Installation & Setup

## 1️⃣ Clone the repository

```
git clone https://github.com/your-username/ai-blog-platform.git
cd ai-blog-platform
```

---

## 2️⃣ Install dependencies

### Backend

```
cd server
npm install
```

### Frontend

```
cd client
npm install
```

---

## 3️⃣ Run the application

### Start backend

```
cd server
npm run dev
```

### Start frontend

```
cd client
npm start
```

---

# 🔐 Authentication Flow

1. User registers/login
2. Server generates JWT token
3. Token stored in client (localStorage/cookies)
4. Protected routes validate token

---

# 🤖 AI Integration (Gemini)

* User clicks **"Generate with AI"**
* Prompt is sent to backend
* Backend calls Gemini API
* AI-generated content is returned and auto-filled in editor

---

# 🖼️ Image Upload Flow

1. User selects image
2. Image is uploaded to Image.io service
3. URL is returned
4. URL stored in database and used in blog

---

# 📌 API Endpoints (Sample)

### Auth

* `POST /api/auth/register`
* `POST /api/auth/login`

### Blogs

* `GET /api/blogs`
* `GET /api/blog/:id`
* `POST /api/blog`
* `PUT /api/blog/:id`
* `DELETE /api/blog/:id`

### AI

* `POST /api/ai/generate`

---

# 📸 Screenshots (Optional)

*Add screenshots of your UI here*

---

# 🚀 Future Improvements

* 🧠 AI-based blog summarization
* ❤️ Like & comment system
* 🔎 Search & filter blogs
* 📊 User dashboard & analytics
* 🌐 SEO optimization

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 🙌 Acknowledgements

* Google Gemini API
* MongoDB Atlas
* Image hosting services (ImageKit/Cloudinary)

---

# 👨‍💻 Author

**Numan Akhtar**

* 💻 MERN Stack Developer
* 🧠 Competitive Programmer (Codeforces Pupil)
* 🚀 Passionate about building scalable applications

---

⭐ If you like this project, give it a star on GitHub!
