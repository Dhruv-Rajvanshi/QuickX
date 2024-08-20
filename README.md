
# QuickX

🚀 **QuickX** is an AI-powered platform that delivers precise answers to all your questions. This platform is designed with a modern and efficient technology stack, combining the power of a responsive frontend and a robust backend to ensure fast, accurate, and reliable responses for any inquiry.


## Features 🌟

- **AI-Powered Answers**: Quickly receive precise answers across a wide range of topics.
- **Frontend Powered by AngularJS**: Enjoy a modern and responsive user interface that enhances user experience.
- **Backend Using Node.js**: Leverage robust server-side logic for handling requests efficiently.
- **MongoDB Integration**: A scalable NoSQL database solution for managing data effectively.
- **Dockerized Deployment**: Easily deploy QuickX in any environment using Docker.

## Technologies Used 🛠️

- **AngularJS**: For building dynamic and responsive user interfaces.
- **Node.js**: For managing the backend with efficient server-side logic.
- **MongoDB**: As the database to store and manage application data.
- **Docker**: For containerizing the application to ensure consistent deployment across environments.
- **Gemini 3.0 API**: For leveraging powerful AI capabilities.
  
## Getting Started 🚀

### Prerequisites ✅

Ensure you have the following installed:

- Node.js (version 16.x recommended)
- MongoDB (for database)
- Docker (optional, but recommended for deployment)

### Installation ⚙️

1. Clone the repository:

   ```bash
   git clone https://github.com/Dhruv-Rajvanshi/QuickX.git
   cd QuickX
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start MongoDB:

   Make sure your MongoDB service is running locally or provide the connection string in the environment variables.


### ▶️ Running the Application

To start the application, run:

```bash
npm start
```



### 🐳 Docker Deployment 

1. Build the Docker image:

   ```bash
   docker build -t quickx-app .
   ```

2. Run the Docker container:

   ```bash
   docker run -d -p 5000:5000 --name QuickX -e MONGO_URI="URI" quickx:latest
   ```

## 📂 Project Structure

```
QuickX/
├── Dockerfile
├── package-lock.json
├── package.json
├── public/
│   ├── dashboard.html
│   ├── index.html
│   ├── login.html
│   └── register.html
└── server.js
```

- **Dockerfile**: Contains the instructions for building the Docker image.
- **public/**: Contains the HTML files for the front-end interface.
- **server.js**: Main server file where the Express app and MongoDB connection are configured.

## Contributing 🤝

 Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to submit a pull request or open an issue.


---

✨ **QuickX** - Delivering fast and efficient solutions for a better tomorrow.
