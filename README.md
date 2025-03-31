# GreenBin

GreenBin is a full-stack application built with a **Node.js** backend and a **React** frontend, maintained as mini monorepo setup.

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repositories
#### 
```sh
git clone repo : https://github.com/Techpix-in/HT1-GREENBIN
cd greenbin-backend
```


### 2️⃣ Install Dependencies
#### Backend Setup
```sh
cd greenbin-be
pnpm install  # or npm install / yarn install
```
#### Frontend Setup
```sh
cd greenbin-frontend
pnpm install  # or npm install / yarn install
```

### 3️⃣ Environment Variables
Create `.env` files in both repositories.
#### Backend (`greenbin-be/.env`)
```
PORT=4000
DATABASE_URL=your_database_url_here
JWT_SECRET=your_jwt_secret
```
#### Frontend (`greenbin-frontend/.env`)
```
VITE_API_BASE_URL=http://localhost:4000
```

### 4️⃣ Running the Application
#### Start Backend
```sh
cd greenbin-backend
pnpm run dev  # or npm run dev / yarn dev
```
#### Start Frontend
```sh
cd greenbin-fe
pnpm run dev  # or npm run dev / yarn dev
```

### 5️⃣ Running with Docker
Ensure you have **Docker** installed.
#### Backend
```sh
cd greenbin-backend
docker build -t greenbin-be .
docker run -p 5000:5000 greenbin-be
```
#### Frontend
```sh
cd greenbin-frontend
docker build -t greenbin-fe .
docker run -p 3000:3000 greenbin-fe
```

---

## 🚀 Deployment
### Backend Deployment
- Use **Docker** or deploy on **Vercel, Railway, or Digital Ocean**

### Frontend Deployment
- Deploy using **Vercel, Netlify, or Cloudflare Pages**
  ```sh
  cd greenbin-fe
  npm run build  # Generate production build
  ```

---


## 🤝 Contributing
Feel free to submit pull requests and report issues.

---

## 🔗 Contact
For inquiries, reach out to [lokeshchowdary902@gmail.com](lokeshchowdary902@gmail.com).

