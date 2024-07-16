# project_learnflow
A full-stack web application utilizing the MERN (MongoDB, Express.js, React.js, Node.js) stack with robust features for online learning.

## Features

### Secure Authentication
- Integrated OAuth 2.0 authentication for secure Google account sign-in.

### Role-Based Access Control
- Differentiates between "Creator" and "Student" roles.
  - **Creators**: Upload and post learning videos.
  - **Students**: View posted videos.

### Hierarchical Comments
- Supports infinite threaded comments for organized discussions on videos.

### Efficient Media Handling
- Utilized AWS S3 bucket and CDN for storage and delivery.
- Implemented Pre-Signed URLs for direct uploads to S3, ensuring optimal performance without backend involvement.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CyrusClasher/project_learnflow.git
   ```
2. Navigate to the project directory:
   ```bash
   cd learning-platform
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables for MongoDB, OAuth 2.0, and AWS.

## Usage

1. Start the application:
   ```bash
   npm start
   ```
2. Open your browser and go to `http://localhost:3000`.

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss the changes.


---

For more details, you can visit the [GitHub repository](https://github.com/CyrusClasher/project_learnflow).
