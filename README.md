# MacBook Promotional App

## Project Overview

The **MacBook Promotional App** is a modern, interactive web application designed to showcase the features and highlights of MacBook models. Built with cutting-edge technologies, the app provides an immersive experience for users to explore the product's design, performance, and features.

## Features

- **3D Product Viewer**: Interactive 3D models of MacBook devices using `three.js` and `@react-three/fiber`.
- **Responsive Design**: Optimized for various screen sizes using `tailwindcss`.
- **Dynamic Highlights**: Engaging animations powered by `gsap`.
- **State Management**: Efficient state handling with `zustand`.
- **Reusable Components**: Modular and reusable React components for scalability.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **Vite**: Fast development environment and build tool.
- **Three.js**: 3D rendering library for creating interactive models.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **GSAP**: Animation library for smooth transitions and effects.
- **Zustand**: Lightweight state management library.

## Project Structure

The project is organized as follows:

```
public/
  fonts/       # Custom fonts
  models/      # 3D models
  videos/      # Video assets
src/
  assets/      # Static assets
  components/  # React components
    models/    # 3D model components
    three/     # Three.js utilities
  constants/   # Application constants
  store/       # State management
```

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd macbook_promotionnal_app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:

```bash
npm run dev
```

### Build

Build the project for production:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
