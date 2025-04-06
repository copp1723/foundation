# NeoAutomotive Platform

A modern, interactive web application foundation for an automotive dealership intelligence platform. This foundation supports future integration of AI-powered tools for lead management, customer communication, and dealership operations.

## Technology Stack

- **Frontend Framework**: React.js
- **CSS Framework**: Tailwind CSS
- **State Management**: React Context API (with architecture ready for Redux)
- **Build System**: Vite.js
- **Animation**: Framer Motion
- **Package Manager**: npm
- **Language**: TypeScript

## Project Structure

```
src/
├── assets/           # Static assets
├── components/       # Component library
│   ├── atoms/        # Basic UI elements
│   ├── molecules/    # Combinations of atoms
│   ├── organisms/    # More complex components
│   └── templates/    # Page layouts
├── context/          # React Context providers
├── hooks/            # Custom React hooks
├── layouts/          # Layout components
├── pages/            # Page components
├── services/         # API service structure
├── styles/           # Global styles
└── utils/            # Utility functions
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```
4. Build for production:
   ```
   npm run build
   ```

## Features

- Responsive dashboard layout with collapsible sidebar
- Dark/light mode theme support
- Reusable component library (buttons, cards, etc.)
- Page routing and lazy loading
- State management pattern using React Context

## Future Enhancements

- Integration with authentication services
- API service implementation
- Real-time data visualization
- AI-powered lead management tools
- Customer communication system
- Advanced analytics dashboard
