<h1 align="center">Messenger Clone</h1>

<div align="center">
  <img src="https://github.com/ayusshrathore/messenger-clone/raw/main/public/images/logo.png" height="50" width="50" />
</div>

## Introduction

Welcome to Messenger Clone! This is a full-stack web application built using Next.js, Prisma, Tailwind CSS, MongoDB, Pusher, and TypeScript. The project aims to provide a real-time messaging experience similar to popular messaging platforms. It enables users to send and receive messages in real-time, view their conversation history, and interact with other users seamlessly.

The Messenger Clone is designed to be a robust, scalable, and user-friendly platform for messaging and collaboration. Whether you want to build a private messaging app, a team collaboration tool, or simply explore the power of real-time communication, this project serves as a great starting point.

## Features

The Messenger Clone comes packed with a range of features to make messaging a delightful experience:

- **Real-Time Messaging**: Enjoy instant updates with real-time messaging powered by Pusher. When you send a message, it is delivered and displayed to the recipient without the need for page refresh.

- **User Authentication**: Ensure secure messaging by enabling user authentication and authorization. Only authenticated users can access the messaging platform.

- **Conversations**: Engage in one-on-one or group conversations with multiple participants. Conversations are threaded and easily navigable.

- **Message Status**: Know the status of your messages with delivery indicators. Check if your message is sent, delivered, or read by the recipient.

- **Conversation History**: Access and manage your conversation history easily. View past messages and revisit older conversations whenever needed.

- **Responsive Interface**: Enjoy a seamless messaging experience on any device. The platform is fully responsive, making it accessible from desktops, tablets, and smartphones.

## Installation

Follow these simple steps to set up the project on your local machine:

1. Clone the repository: `git clone https://github.com/ayusshrathore/messenger-clone.git`
2. Navigate to the project directory: `cd messenger-clone`
3. Install dependencies: `npm install`

## Usage

Getting started with Messenger Clone is easy! Just follow these steps:

1. Configure environment variables:

   Create a `.env.local` file in the root directory and add the following variables:

   ```
    DATABASE_URL=your_database_url
    NEXTAUTH_SECRET=your_nextauth_secret
    
    GITHUB_ID=your_github_id
    GITHUB_SECRET=your_github_secret
    
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    
    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   ```

2. Start the development server: `npm run dev`
3. Open your browser and visit `http://localhost:3000` to access the Messenger Clone.

## Technologies

The project leverages a powerful stack of technologies to deliver a high-quality messaging experience:

- **Next.js**: A React framework for server-side rendering and building modern web applications. Next.js provides excellent performance and SEO optimization out of the box.

- **Prisma**: A sophisticated ORM (Object-Relational Mapping) tool for database interactions. Prisma simplifies database management and offers a type-safe query builder.

- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs. Tailwind CSS enables quick and efficient styling, resulting in a visually stunning UI.

- **MongoDB**: A popular NoSQL database for storing and retrieving message data. MongoDB's flexible document-based approach facilitates easy data management.

- **Pusher**: A real-time messaging service for instant message updates. Pusher powers real-time events and notifications, making messaging feel instantaneous.

- **TypeScript**: A typed superset of JavaScript, providing enhanced code quality and better developer experience. TypeScript brings static type checking and code predictability to the project.

## Contributing

Contributions to this project are welcome! If you find any bugs, have additional features in mind, or want to optimize the codebase, feel free to open an issue or submit a pull request. Please read the [Contributing Guidelines](CONTRIBUTING.md) for more information.

## License

This project is licensed under the [MIT License](LICENSE).
