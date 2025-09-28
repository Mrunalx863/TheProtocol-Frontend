# TheProtocol - Frontend

A modern, real-time chat application frontend. 
This project allows users to chat, send images, and see who’s online in real-time with a sleek, dark-themed interface.

---

## 🚀 Features

- **Real-time Messaging:** Instant messaging with Socket.IO  
- **User Authentication:** Secure login and registration  
- **Profile Management:** Update profile pictures with Cloudinary  
- **Online Status:** See who's online in real-time  
- **Responsive Design:** Mobile-first responsive UI  
- **Image Messaging:** Send and receive images  
- **Modern UI:** Clean, dark-themed interface with smooth animations  

---

## 🛠️ Languages & Technologies

### Core Languages

- **JavaScript (ES6+):** Primary programming language with modern syntax  
- **HTML5:** Semantic markup language  
- **CSS3:** Styling with modern features  
- **JSX:** JavaScript XML for React components  

### Frontend Framework & Library

- **React 18:** Modern UI library with hooks and concurrent features  
- **Vite:** Next-generation frontend build tool  
- **React Router DOM:** Declarative routing for React applications  

### Styling & UI

- **Tailwind CSS:** Utility-first CSS framework  
- **DaisyUI:** Component library built on Tailwind CSS  
- **PostCSS:** CSS post-processor  
- **Autoprefixer:** CSS vendor prefixing  

### State Management

- **Zustand:** Lightweight state management solution  
- **React Hooks:** Built-in state management (useState, useEffect, etc.)  

### HTTP & Real-time Communication

- **Axios:** Promise-based HTTP client  
- **Socket.IO Client:** Real-time bidirectional communication  

---

## 📋 Prerequisites

- Node.js (v14 or higher)  
- npm or yarn package manager  

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/theprotocol-frontend.git
cd theprotocol-frontend
````

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Setup

Create a `.env` file in the root directory:

```env
# API Configuration (Development)
VITE_API_BASE_URL=http://localhost:5000/api
VITE_SOCKET_URL=http://localhost:5000

# API Configuration (Production)
# VITE_API_BASE_URL=https://your-backend-domain.railway.app/api
# VITE_SOCKET_URL=https://your-backend-domain.railway.app
```

### 4. Start the development server

```bash
npm run dev
# or
yarn dev
```

The application will be available at [http://localhost:5173](http://localhost:5173)

---

## 🏗️ Build for Production

```bash
npm run build
# or
yarn build
```

---

## 📁 Project Structure

```
├── src/
│   ├── components/
│   │   ├── ChatContainer.jsx      # Main chat interface
│   │   ├── MessageInput.jsx       # Message input component
│   │   ├── MessageSkeleton.jsx    # Loading skeleton
│   │   ├── Navbar.jsx             # Navigation bar
│   │   └── Sidebar.jsx            # User list sidebar
│   ├── lib/
│   │   ├── axios.js               # Axios configuration
│   │   └── utils.js               # Utility functions
│   ├── pages/
│   │   ├── HomePage.jsx           # Main chat page
│   │   ├── LoginPage.jsx          # Login form
│   │   ├── ProfilePage.jsx        # Profile management
│   │   ├── SettingsPage.jsx       # User settings
│   │   └── SignUpPage.jsx         # Registration form
│   ├── store/
│   │   ├── useAuthStore.js        # Authentication state
│   │   ├── useChatStore.js        # Chat state
│   │   └── useThemeStore.js       # Theme management
│   ├── App.jsx                    # Main app component
│   ├── index.css                  # Global styles
│   └── main.jsx                   # App entry point
├── public/
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 📞 Support

If you encounter any issues, please create an issue on GitHub.

---

Built with ❤️ by **Mrunal Mehar**

```
