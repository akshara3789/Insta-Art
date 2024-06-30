# AI Image Sharing Platform

## Overview

This project is a platform where users can generate AI images and share them with the community. The application leverages the OpenAI API to create unique and creative images, and uses Cloudinary for image storage. The project is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and utilizes Vite for a faster development build.

## Features

- **Image Generation**: Users can create images using AI technology.
- **Image Sharing**: Users can share generated images with the community.
- **Image Storage**: Images are stored on Cloudinary for efficient handling and delivery.
- **Responsive Design**: A mobile-friendly interface built with React.js and CSS.

## Technologies Used

- **Frontend**: React.js, Vite
- **Backend**: Node.js, Express.js
- **Database**: MongoDB,Cloudinary
- **API**: OpenAI API

## Installation

Follow these steps to set up the project on your local machine:

### Prerequisites

- **Node.js** and **npm** installed
- *A MongoDB Atlas account
- **Cloudinary** account for image storage
- **OpenAI** account for API

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/25-pranav-25/AIimageshare.git
cd AIimageshare
```

### Install Dependencies

Install the required dependencies for both frontend and backend:

```bash
npm install
```

### Environment Configuration

Create a `.env` file in the root directory and add the following environment variables:

```env
OPENAI_API_KEY=your_openai_api_key
MONGODB_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Replace `your_openai_api_key`, `your_mongodb_connection_string`, `your_cloudinary_cloud_name`, `your_cloudinary_api_key`, `your_cloudinary_api_secret` with your actual credentials.

## Run the Application

Follow these steps to start the development servers for both the frontend and backend:

1. **Navigate to the Client Directory**

   Change to the client directory where the frontend code is located and start the frontend development server:

   ```bash
   cd client
   npm run dev
   ```

2. **Open a New Terminal Window**

   To keep the backend server running in a separate terminal, open a new terminal window and navigate to the server directory.

3. **Navigate to the Server Directory**

   Change to the server directory where the backend code is located and start the backend server:

   ```bash
   cd ../server
   npm start
   ```

This will start the frontend server using Vite and the backend server using Node.js in separate terminals, allowing you to develop and test both parts of your application simultaneously.

Feel free to adjust the instructions according to your project’s specific setup or folder structure.

## Usage

1. **Generate Images**: Navigate to the Create image section, input your desired prompt, and generate images using the OpenAI API.
2. **Upload Images**: Use Cloudinary to upload generated images. The platform integrates Cloudinary for efficient image storage and delivery.
3. **Share Images**: Once images are generated and uploaded, you can share them with the community by uploading them through the platform’s sharing feature.

