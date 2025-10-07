# Campus Social Network Web Application

A modern, feature-rich social networking platform built with Next.js and Node.js, designed specifically for campus communities.

[![Next.js](https://img.shields.io/badge/Next.js-13.0+-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.0+-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4.4+-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

##  Features

- **Authentication & Authorization**
  - Secure user registration and login
  - JWT-based authentication
  - Role-based access control

- **Profile Management**
  - Customizable user profiles
  - Profile picture upload with Cloudinary integration
  - Cover photo customization
  - Bio and personal information management

- **Social Interactions**
  - Friend requests system
  - Real-time notifications
  - Post creation and sharing
  - Comments and reactions
  - Story sharing feature

- **Content Management**
  - Post creation with rich text and media
  - Story sharing with 24-hour visibility
  - Bookmark favorite posts
  - Hashtag support
  - Media upload capabilities

- **Explore & Discover**
  - Trending posts section
  - User discovery
  - Hashtag exploration
  - Advanced search functionality

##  Tech Stack

### Frontend
- Next.js 13+
- Redux for state management
- Tailwind CSS for styling
- Axios for API requests

### Backend
- Node.js & Express.js
- MongoDB with Mongoose
- JWT for authentication
- Cloudinary for media storage

##  Installation & Setup

### Prerequisites
- Node.js 18.0 or higher
- MongoDB
- Cloudinary account
- Git

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file based on envsample.txt with your configurations:
   ```env
   PORT=8000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_key
   CLOUDINARY_API_SECRET=your_cloudinary_secret
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file based on envsample.txt:
   ```env
   NEXT_PUBLIC_BACKEND_API=http://localhost:8000
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

##  API Documentation

The API is organized around REST. All requests should be made to endpoints beginning with `/api/`.

### Main Endpoints:

- **Authentication**
  - POST `/api/auth/register`
  - POST `/api/auth/login`
  - POST `/api/auth/logout`

- **Users**
  - GET `/api/user/profile`
  - PUT `/api/user/update`
  - PUT `/api/user/update/avatar`

- **Posts**
  - GET `/api/posts`
  - POST `/api/posts/create`
  - PUT `/api/posts/:id`
  - DELETE `/api/posts/:id`

- **Stories**
  - GET `/api/stories`
  - POST `/api/stories/create`
  - DELETE `/api/stories/:id`

##  Contributing

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m "Add some AmazingFeature"`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

##  License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

##  Authors

- Deneth0077

##  Acknowledgments

- Thanks to all contributors who have helped this project grow
- Special thanks to the open-source community

---

Made with  for campus communities
