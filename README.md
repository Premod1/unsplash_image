# Unsplash Image Viewer

A React application that allows users to browse and view images from Unsplash using the Unsplash API.

## Demo

Add a link to your live demo or include screenshots of your application.

![Demo Screenshot](link-to-screenshot.png)

## Features

- Browse images from Unsplash
- Search for images
- View image details
- Responsive design

## Installation

Follow these steps to get the application up and running on your local machine.

### Prerequisites

- Node.js (version 14.x or higher)
- npm (version 6.x or higher) or yarn

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/Premod1/unsplash_image.git
    cd unsplash-image-viewer
    ```

2. Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

3. Create a `.env` file in the root directory and add your Unsplash API key:
    ```env
    REACT_APP_UNSPLASH_ACCESS_KEY=your_unsplash_access_key
    ```

4. Start the development server:
    ```bash
    npm start
    # or
    yarn start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

### Searching for Images

Enter a keyword in the search bar and press Enter. The application will fetch and display images related to the keyword from Unsplash.

### Viewing Image Details

Click on an image to view its details, including the photographer's name, description, and a link to the image on Unsplash.

## Configuration

The application uses environment variables for configuration. Ensure you have a `.env` file in your project's root directory with the following content:

```env
REACT_APP_UNSPLASH_ACCESS_KEY=your_unsplash_access_key
