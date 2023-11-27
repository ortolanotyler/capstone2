Project Overview: 
- Stock market application that allows users to make/track their own “paper” portfolios, do research on stock tickers. 

Technologies: 

“PERN”

- Postgres 
- Express 
- React 
- Node 

Libraries
- redux
- axios 
- react/router
- sequelize
- jwt 
- dotenv
- babel
-eslint
-nodemon
- jest (testing)
- git

API: 

AlphaVantage 



Planned file heirarchy: 

stock-market-app/
│
├── client/                  # React front-end
│   ├── public/              # Public files like index.html
│   ├── src/
│   │   ├── components/      # Reusable React components
│   │   │   ├── Chart.js     # Component for displaying stock charts
│   │   │   ├── Research.js  # Component for stock research functionality
│   │   │   └── Portfolio.js # Component for managing a fake portfolio
│   │   │
│   │   ├── App.js           # Main React application component
│   │   ├── index.js         # Entry point for React application
│   │   └── ...
│   │
│   └── package.json         # Front-end dependencies
│
├── server/                  # Express back-end
│   ├── db/                  # Database-related files
│   │   └── index.js         # PostgreSQL connection and queries
│   │
│   ├── routes/              # Express routes
│   │   ├── stocks.js        # Routes for stock-related requests
│   │   └── users.js         # Routes for user/portfolio management
│   │
│   ├── app.js               # Express application setup
│   ├── server.js            # Node.js/Express server entry point
│   └── package.json         # Back-end dependencies
│
├── .env                     # Environment variables
├── .gitignore               # Specifies intentionally untracked files to ignore
├── README.md                # Project overview and documentation
└── package.json             # Root-level package.json for scripts
