𓂃🖊 QUICKBLOG ✍️ ᯓ➤
AI-Powered Blogging Platform with Intelligent Content Generation

Last Commit Languages License Version

Powered by cutting-edge AI and modern technologies:

React Google Gemini Express MongoDB ImageKit Tailwind CSS

LIVE - DEMO 🌐


QuickBlog/
├── client/                 # React Frontend
│   ├── src/
│   │   ├── assets/        # Static assets
│   │   ├── components/    # Reusable components
│   │   │   ├── BlogCard.jsx      # Blog post preview
│   │   │   ├── CommentSection.jsx # Comments and replies
│   │   │   ├── RichTextEditor.jsx # Quill.js editor
│   │   │   ├── SearchBar.jsx     # Blog search functionality
│   │   │   ├── Sidebar.jsx       # Navigation and categories
│   │   │   └── ...               # Other components
│   │   ├── pages/         # Route pages
│   │   │   ├── Admin/           # Admin dashboard pages
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── BlogManagement.jsx
│   │   │   │   ├── Comments.jsx
│   │   │   │   └── Analytics.jsx
│   │   │   ├── Blog/            # Blog-related pages
│   │   │   │   ├── BlogPost.jsx
│   │   │   │   ├── CreateBlog.jsx
│   │   │   │   ├── EditBlog.jsx
│   │   │   │   └── BlogList.jsx
│   │   │   ├── Home.jsx         # Landing page
│   │   │   ├── Login.jsx        # Authentication
│   │   │   └── Profile.jsx      # User profile
│   │   ├── context/       # React context
│   │   │   └── AppContext.jsx   # Global state management
│   │   ├── hooks/         # Custom React hooks
│   │   ├── utils/         # Utility functions
│   │   ├── index.css      # Global styles
│   │   └── main.jsx       # Application entry point
│   ├── package.json       # Dependencies and scripts
│   └── vite.config.js     # Vite configuration
│
├── server/                # Express Backend
│   ├── config/           # Configuration files
│   ├── controllers/      # Business logic
│   │   ├── blogController.js    # Blog CRUD operations
│   │   ├── aiController.js      # Gemini AI integration
│   │   ├── commentController.js # Comment management
│   │   ├── userController.js    # User authentication
│   │   └── adminController.js   # Admin operations
│   ├── middleware/       # Custom middlewares
│   │   ├── auth.js              # JWT authentication
│   │   ├── upload.js            # File upload handling
│   │   └── admin.js             # Admin role verification
│   ├── models/          # Database models
│   │   ├── Blog.js              # Blog post schema
│   │   ├── Comment.js           # Comment schema
│   │   ├── User.js              # User schema
│   │   └── Category.js          # Category schema
│   ├── routes/          # API routes
│   │   ├── blogRoutes.js        # Blog endpoints
│   │   ├── aiRoutes.js          # AI generation endpoints
│   │   ├── commentRoutes.js     # Comment endpoints
│   │   ├── userRoutes.js        # User endpoints
│   │   └── adminRoutes.js       # Admin endpoints
│   ├── package.json     # Dependencies and scripts
│   └── server.js        # Server entry point
└── README.md            # Project documentation
