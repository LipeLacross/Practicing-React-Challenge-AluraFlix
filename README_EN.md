## 🌐 [Versão em Português do README](README.md)

# AluraFlix

AluraFlix is a platform inspired by Netflix, developed as part of an educational project. The goal is to create a web application for sharing and categorizing educational videos, offering an intuitive and responsive interface.

## 🔨 Project Features

- **Video Registration**: Allows adding new videos with custom categories.
- **Video Listing**: Displays categorized videos in a user-friendly interface.
- **Confirmation Modal**: Interface for confirming item deletion or editing.
- **Category Filter**: View videos segmented by categories such as Front-End, Back-End, and Mobile.

### Visual Example of the Project

![chrome-capture-2024-12-22](https://github.com/user-attachments/assets/0c5501ab-70e8-4c0e-a559-9b10c6e08eac)

## ✔️ Techniques and Technologies Used

- **React.js**: Framework for building the user interface.
- **Vite**: Tool for fast project development and build.
- **CSS Modules**: For modular styling and component scoping.
- **Context API**: To manage global states.
- **Custom Hooks**: Reusable logic across components.

## 📁 Project Structure

- **public/**
    - `images/`: Contains logos and icons used in the project.
    - `index.html`: Main HTML file, which is the entry point of the application.

- **src/**
    - **components/**: Reusable components like Banner, Footer, and Header.
    - **pages/**: Project-specific pages such as Home and NewVideo.
    - **context/**: Definitions of global states using Context API.
    - **hooks/**: Custom hooks for managing states and reusable logic.
    - **index.css**: Global styling.
    - **main.jsx**: Application initialization file.
    - **routes.jsx**: Application routing configuration.

## 🛠️ Open and Run the Project

To start the project locally, follow the steps below:

1. **Ensure Node.js is installed**:
    - [Node.js](https://nodejs.org/) is required to run the project. Verify the installed version with the command:

      ```bash
      node -v
      ```
    - If not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and execute the command below in the terminal:

      ```bash
      git clone <REPOSITORY_URL>
      ```

3. **Install Dependencies**:
    - Navigate to the cloned project folder and run the command:

      ```bash
      npm install
      ```

4. **Start the Project**:
    - Run the command below to start the development server:

      ```bash
      npm run dev
      ```
    - Access the project in your browser at: `http://localhost:5173`.

## 🌐 Deploy

To deploy the project:

1. **Generate the production build**:
    - Run the command:

      ```bash
      npm run build
      ```

2. **Set up the deployment environment**:
    - Use platforms like [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/) to host the project.

3. **Upload files to the server**:
    - Upload the build files to the server or directly connect the repository to the chosen deployment service.
