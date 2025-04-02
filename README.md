
# MERN-AI-Imagen

A full-stack application that leverages the MERN stack (MongoDB, Express, React, Node.js) and advanced AI models for image generation. This project allows users to create unique images from textual descriptions through an intuitive web interface.

## Overview

**MERN-AI-Imagen** combines the robustness of the MERN stack with the creativity of AI-powered image generation. The application offers a seamless experience where users can input text prompts and receive generated images, making it ideal for creative projects, design inspiration, and more.

## Features

- **AI-Powered Image Generation:** Generate unique images using state-of-the-art AI models.
- **Modern Frontend:** Responsive and dynamic user interface built with React.
- **Robust Backend:** Node.js and Express server handling API requests and integration with AI services.
- **Scalable Database:** MongoDB for storing user data, generated images, and application settings.
- **Modular Design:** Easily extendable architecture for adding new features and improvements.

## Installation

Follow these steps to set up the project locally.

### Prerequisites

- **Node.js** 
- **npm** 
- **MongoDB** (local or remote instance)

### Clone the Repository

```bash
git clone https://github.com/sumits234/MERN-AI-Imagen.git
cd MERN-AI-Imagen
```

### Server Setup

1. Navigate to the server directory:

   ```bash
   cd server
   ```

2. Install server dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the `server` folder with the following variables:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string

   ```

4. Start the server:

   ```bash
   npm start
   ```

### Client Setup

1. Open a new terminal window and navigate to the client directory:

   ```bash
   cd client
   ```

2. Install client dependencies:

   ```bash
   npm install
   ```

3. Start the client application:

   ```bash
   npm start
   ```

The client should open automatically in your default browser at [http://localhost:3000](http://localhost:3000).

## Usage

1. **Enter a Prompt:** On the main page, type a description for the image you want to generate.
2. **Generate Image:** Click on the "Generate" button to start the image generation process.
3. **View Results:** The generated image will be displayed on the page once processing is complete.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Open a pull request with a detailed description of your changes.

 Enjoy coding!
