# Chatosphere - Real-Time Chat Application

Check it out - https://chatosphere.vercel.app

A real-time chat application built using Next.js 13 with App Router, Redis as a database, and Pusher.js for real-time updates. This project showcases the power of modern web technologies to create a seamless and responsive chat experience with user authentication provided by NextAuth.js using Google as the identity provider. The App is done with strict typing using typescript and zod validators to follow the best practices in writing maintainable and scalable code.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)


## Features

- **Real-Time Messaging**: Enjoy a real-time chat experience, where messages are instantly delivered to all connected users.
- **User Authentication**: Securely authenticate users using NextAuth.js with Google as the identity provider.
- **Message History**: Access chat history to view past conversations.
- **View Recent Chats**: Have a quick look on the recent chat with all our friends.
- **Add Friends**: Send request to friends with the email id and get accepted.
- **Responsive Design**: A responsive user interface that adapts to various screen sizes and devices.

## Technologies Used

- [Next.js 13](https://nextjs.org/): A powerful React framework for building server-rendered web applications.
- [Redis](https://redis.io/): A blazing fast, in-memory data store for real-time data fetching and storage.
- [Pusher.js](https://pusher.com/): A pub/sub mechanism for real-time updates and event-driven communication.
- [NextAuth.js](https://next-auth.js.org/): An authentication library for Next.js applications.
- [Google Identity Provider](https://developers.google.com/identity/protocols/oauth2): Use Google as the identity provider for user authentication.
- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for creating stylish and responsive designs.
- [Zod](https://zod.dev//): A powerful and versatile TypeScript schema validation library for ensuring data integrity.
- [Vercel](https://vercel.com/home//): Cloud platform that streamlines the deployment process and faciltates deployment of scalable applications.
  

## Getting Started

Follow these steps to get the chat application up and running on your local machine:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/iavinash73/Chatosphere.git

2. Add these env variables:

   env variable:
   ```bash
   UPSTASH_REDIS_REST_URL = ,
   UPSTASH_REDIS_REST_TOKEN = ,
   NEXTAUTH_SECRET = ,
   GOOGLE_CLIENT_ID = ,
   GOOGLE_CLIENT_SECRET = ,
   PUSHER_APP_ID = ,
   NEXT_PUBLIC_PUSHER_APP_KEY = ,
   PUSHER_APP_SECRET = 

4. Install dependencies:
    
   ```bash
   npm i

5. Run Chatosphere in your local machine:

   ```bash
   npm run dev

6. Access the application in your web browser at `http://localhost:3000`


