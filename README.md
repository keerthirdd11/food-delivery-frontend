# Food Delivery Application

A modern food delivery platform built with React and Vite.

## Features(frontend)
- Browse food items by category
- Real-time cart updates
- User authentication
- Order placement and tracking
- Responsive design

## Technology Stack
- React 18
- Vite
- React Router
- Context API for state management
- CSS Modules for styling

## Getting Started

### Prerequisites
- Node.js (v20.19+ or v22.12+)
- npm/yarn

### Installation
1. Clone the repository

git clone [repository-url]

2.Install dependencies

npm install

3. Start development server

npm run dev

4. Build for Production

npm run build

## folder structure:

frontend/
├── public/                    # Static public assets
│   ├── header_img.png
│   └── vite.svg
│
├── src/                       # Source code
│   ├── assets/               # Images and static resources
│   │   ├── icons/           # UI icons
│   │   ├── food/            # Food images
│   │   ├── menu/            # Menu category images
│   │   └── assets.js        # Asset exports
│   │
│   ├── components/          # Reusable components
│   │   ├── AppDownload/     # App download section
│   │   ├── ExploreMenu/     # Menu categories
│   │   ├── FoodDisplay/     # Food items grid
│   │   ├── FoodItem/        # Individual food card
│   │   ├── Footer/          # Site footer
│   │   ├── Header/          # Hero section
│   │   ├── LoginPopup/      # Auth modal
│   │   └── Navbar/          # Navigation bar
│   │
│   ├── context/             # Global state management
│   │   └── StoreContext.jsx # App-wide state
│   │
│   ├── pages/               # Route components
│   │   ├── Cart/           # Shopping cart
│   │   ├── Home/           # Landing page
│   │   └── PlaceOrder/     # Checkout process
│   │
│   ├── App.jsx             # Root component
│   ├── App.css             # Root styles
│   ├── main.jsx            # Entry point
│   └── index.css           # Global styles
│
├── .gitignore              # Git ignore rules
├── eslint.config.js        # ESLint configuration
├── index.html             # HTML entry point
├── package.json           # Dependencies and scripts
├── README.md             # Project documentation
└── vite.config.js        # Vite configuration