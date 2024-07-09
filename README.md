# dev-blog

Dev-blog is a blogging project built with Node.js (using Express) and MongoDB.

# Setup

Follow these steps to set up and run the DevBlog project on your local machine.

### Prerequisites

- Node.js (v19 or higher)
- MongoDB (Make sure it's installed and running)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nodeexcel/dev-blog.git
   ```

2. Navigate to the project directory:

   ```bash
   cd devblog
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. add `MONGO_URI` environment variable in `.env` file

5. Start the application:

   ```bash
   npm start
   #for debugging run:
   DEBUG=dev-blog:* npm start
   ```

6. Open your browser and visit `http://localhost:3000` to access the dev-blog application.

## Technologies Used

The dev-Blog project utilizes the following technologies and tools:

- Node.js
- Express
- MongoDB(mongoose)
- HTML
- CSS(tailwindcss)
- JavaScript
