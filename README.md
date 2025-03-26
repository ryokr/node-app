NodeJS Application -  Final Project

/node-ecom
├── /backend
│   ├── /config        # Configuration files (e.g., DB, env)
│   ├── /controllers   # API controllers (e.g., user, product, order)
│   ├── /models        # Mongoose models
│   ├── /routes        # Express routes
│   ├── /middlewares   # Middleware (e.g., auth, error handling)
│   ├── /utils         # Utility functions (e.g., token generation)
│   ├── server.js      # Entry point for Node.js server
│   └── package.json   # Dependencies and scripts
├── /frontend
│   ├── /src
│   │   ├── /components   # Reusable React components
│   │   ├── /pages        # Pages (e.g., Home, Login, Admin Dashboard)
│   │   ├── /context      # Context API (e.g., auth, cart state)
│   │   ├── /styles       # Global and page-specific styles
│   │   ├── App.js        # Root component
│   │   └── index.js      # Entry point for React app
│   └── package.json      # Dependencies for React
├── /docker
│   ├── docker-compose.yml   # Docker Compose config
│   ├── Dockerfile.backend   # Dockerfile for backend
│   └── Dockerfile.frontend  # Dockerfile for frontend

