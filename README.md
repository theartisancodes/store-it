# StoreIt: A Modern File Storage Solution

**StoreIt** is a cutting-edge file storage application designed to simplify how users upload, manage, and organize their files securely. Built with modern technologies like React, Next.js, and TailwindCSS, StoreIt provides an intuitive user experience while maintaining robust backend capabilities using Appwrite for storage and user authentication.

---

## Features

### 🌟 **Core Functionality**
- **Secure File Upload**: Users can upload files with drag-and-drop functionality for ease of use.
- **Real-Time Feedback**: Built-in validation using `react-hook-form` and `zod` ensures users receive instant feedback on uploads.
- **User-Friendly UI**: Designed with a responsive, minimalist interface powered by TailwindCSS and Radix UI components.
- **File Previews**: Easily preview uploaded files before confirmation.

### 🔒 **Security and Performance**
- **Secure Authentication**: Integration with Appwrite provides secure user authentication and data management.
- **Efficient File Handling**: Leverages `react-dropzone` for seamless file drag-and-drop capabilities.
- **Debounced Search**: Real-time search powered by `use-debounce` for managing large file repositories without performance issues.

### 📊 **Data Visualization**
- **Interactive Charts**: Visualize storage usage and file statistics using Recharts.
- **Customizable Views**: Sort and filter files for better organization.

### 🔔 **Advanced Notifications**
- **Alerts and Toasts**: Real-time alerts powered by Radix Toast for upload success or failure.
- **Error Management**: Friendly error messages ensure users understand any issues during file uploads.

---

## Getting Started

### Prerequisites
Before getting started, ensure you have the following installed:
- Node.js (>= 20.x)
- Yarn or npm (for package management)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/store_it.git
   cd store_it
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## Tech Stack

### 🛠 **Frontend**
- **React**: Modern UI library for building dynamic user interfaces.
- **Next.js**: Framework for server-side rendering and static site generation.
- **TailwindCSS**: Utility-first CSS framework for styling.

### ⚙️ **Backend**
- **Appwrite**: Open-source backend server for authentication and file storage.

### 📦 **Key Libraries**
- `react-dropzone`: Drag-and-drop file uploader.
- `react-hook-form`: Forms with validation.
- `zod`: Schema validation for form inputs.
- `recharts`: For data visualization.

### 🌟 **Developer Tools**
- **Linting**: ESLint with Prettier for code formatting.
- **Typescript**: Strongly-typed JavaScript for maintainable code.
- **Turbopack**: Optimized Next.js bundler for faster builds.

---

## Scripts

| Script       | Description                             |
|--------------|-----------------------------------------|
| `dev`        | Runs the development server.            |
| `build`      | Builds the application for production.  |
| `start`      | Starts the production server.           |
| `lint`       | Lints the code using ESLint.            |
| `deploy`     | Deploys the application to Vercel.      |

---

## Folder Structure

```
store_it/
├── public/             # Static assets
├── app/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Next.js pages
│   ├── styles/         # TailwindCSS styles
│   ├── utils/          # Utility functions
│   └── hooks/          # Custom React hooks
├── package.json        # Project metadata
├── tailwind.config.js  # TailwindCSS configuration
└── tsconfig.json       # TypeScript configuration
```

---

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments

- **Appwrite**: For providing a reliable backend solution.
- **Radix UI**: For offering high-quality UI primitives.
- **Recharts**: For the stunning data visualization tools.

> **Start storing your files smarter, faster, and more securely with StoreIt! 🚀**
