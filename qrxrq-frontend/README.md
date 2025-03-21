# QRXRQ URL Shortener (Frontend)

## Overview
QRXRQ URL Shortener (Frontend) is a web application that provides a fast and efficient way to shorten URLs. Built with modern technologies, it ensures performance, scalability, and ease of use. The application allows users to generate short URLs using an incrementing ID approach while leveraging caching for optimized performance.

## Features
- URL shortening with incrementing ID approach
- Fast and efficient retrieval with Redis caching
- Dark and light mode support
- RESTful API for URL management
- Responsive UI using Tailwind CSS
- Secure and scalable backend

## Technologies Used
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![ShadCN UI](https://img.shields.io/badge/shadcn%2Fui-%23000000.svg?style=for-the-badge&logo=shadcnui&logoColor=white)
![Axios](https://img.shields.io/badge/axios.js-854195?style=for-the-badge&logo=axios&logoColor=5A29E4)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)


## Installation
### Prerequisites
- Node.js (Latest LTS version recommended)
- MongoDB
- Redis
- QRXRQ Server Side (check /qrxrq-backend folder)

### Steps
1. Clone the repository (if not yet. backend and frontend share the same repo):
   ```sh
   git clone https://github.com/landofcash/qrxrq.git
   
   cd qrxrq-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Access the application in your browser at `http://localhost:3000`

## Demo
Live version: [https://qrxrq.com](https://qrxrq.com)

## Roadmap
- Implement user authentication
- Add analytics for URL tracking
- Enhance UI with more features
- Support custom short URLs

## License
This project is licensed under the MIT License.

