
# VideoTube 📺

## Introduction

Welcome to the `VideoTube` project! 🌐
This project seamlessly integrates the functionalities of YouTube
with the tweeting capabilities of Twitter.
Explore more about this exciting project in the detailed documentation below.

### Important links
<!--toc:start-->

- [Features](#features)
  - [User Management:](#user-management)
  - [Video Management:](#video-management)
  - [Tweet Management:](#tweet-management)
  - [Subscription Management:](#subscription-management)
  - [Playlist Management:](#playlist-management)
  - [Like Management:](#like-management)
  - [Comment Management:](#comment-management)
  - [Dashboard:](#dashboard)
  - [Health Check:](#health-check)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Contributing](#contributing)
- [License](#license)

<!--toc:end-->

## Models

![Models](https://github.com/user-attachments/assets/db9885c1-cd2e-424e-9e10-73f868d46861)

## Features

### User Management

  - Registration, login, logout, password reset
  - Profile management (avatar, cover image, details)
  - Watch history tracking

### Video Management

  - Video upload and publishing
  - Video search, sorting, and pagination
  - Video editing and deletion
  - Visibility control (publish/unpublish)

### Tweet Management

  - Tweet creation and publishing
  - Viewing user tweets
  - Updating and deleting tweets

### Subscription Management

  - Subscribing to channels
  - Viewing subscriber and subscribed channel lists

### Playlist Management

  - Creating, updating, and deleting playlists
  - Adding and removing videos from playlists
  - Viewing user playlists

### Like Management

  - Liking and unliking videos, comments, and tweets
  - Viewing liked videos

### Comment Management

  - Adding, updating, and deleting comments on videos

### Dashboard

  - Viewing channel statistics (views, subscribers, videos, likes)
  - Accessing uploaded videos

### Health Check

  - Endpoint to verify the backend's health

## Technologies Used

  - Node.js
  - Express.js
  - MongoDB
  - Cloudinary (must have an account)

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone git@github.com:Theyashsawarkar/VideoTube-BackEnd.git
   ```

2. **Install dependencies:**

   ```bash
   cd VideoTube-BackEnd
   npm install
   ```

3. **Set up environment variables:**
   Create a .env in the root of the project and fill in the
   required values using .env.sample file.

4. **Start the server:**

   ```bash
   npm run dev
   ```

## Deployment Note

  For the deployment of the backend application, it is crucial to deploy it on [Render](https://render.com/). Render maintains the state of the file system between builds and redeployments, which is essential for using disk storage with Multer.

  If you choose to deploy the app using other services, consider these options:

  - **Serverless Deployment**: Use Multer's memory storage since serverless platforms don't retain file system state between deployments.
  - **Serverful Deployment**: Render is recommended to ensure the file system state is preserved, but other platforms might work if they support persistent storage.

## Contributing

  If you wish to contribute to this project,
  feel free to join in and make it even better!

