# Trial Task - Ionic Angular Mobile Application

A mobile application built with Ionic Framework and Angular, implementing a three-tab navigation system for managing challenges, viewing results, and accessing information.

## Design System

### Colors
- Primary Color: `#008080` (Teal)
- Secondary Color: `#cee7e7` (Light Teal)
- Tertiary Color: `#ff33a1`

### Typography
- Base Font Family: `'Open Sans', sans-serif`
- Title Font Family (INFOS): `'Amatic SC', sans-serif`
- Font Imports:
  ```css
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&display=swap');
  ```

## Major Features

### 1. Challenges Tab
- Access and view available challenges (Image at the bottom & top and background-image : base.jpg)

### 2. Results Tab
- View statistics and performance metrics (Image at the bottom and background-image : base.jpg)

### 3. Info Tab
- Access important information and details (Title H1 and description P)

## Trial Task Requirements

### Design Implementation
- Strict adherence to provided mockups
- Consistent UI/UX across all screens
- Proper implementation of custom icons and assets
- Responsive design for various screen sizes
- Implementation of specified color scheme and typography

### Navigation
- Seamless tab-based navigation system
- Smooth transitions between screens
- Bottom tab bar with custom icons
- Intuitive user flow between Challenges, Results, and Info sections

### Code Quality
- Clean and maintainable code structure
- Comprehensive code documentation
- Modular component architecture
- Following Angular/Ionic best practices
- Efficient state management
- Proper error handling

### Cross-Platform Compatibility
- Consistent functionality across Android and iOS
- Platform-specific UI adaptations
- Responsive layouts for different devices
- Native-like performance on both platforms

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (Latest LTS version)
- npm (Latest version)
- Ionic CLI: `npm install -g @ionic/cli`
- Angular CLI: `npm install -g @angular/cli`

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

## Development

To start the development server:
```bash
npm start
```
This will launch the application at `http://localhost:4200/`

## Project Structure

```
src/
├── app/
│   ├── tab1/                # Challenges tab
│   ├── tab2/                # Results tab
│   ├── tab3/                # Info tab
│   └── tabs/                # Tab navigation
├── assets/
│   └── images/              
│       ├── event.png        # Challenges icon
│       ├── statistics.png   # Results icon
│       └── info.png         # Info icon
└── theme/
    └── variables.scss       # Global styling and theme variables
```

## Technologies Used

- Ionic Framework 8
- Angular 18
- Capacitor 6
- TypeScript
- SCSS

## Building and Testing

### Development Build
```bash
npm run build
```

### Production Build
```bash
npm run build --prod
```

### Running Tests
```bash
npm run test
```

### Linting
```bash
npm run lint
```

## Mobile Platform Support

### iOS Build
```bash
ionic capacitor add ios
ionic capacitor build ios
```

### Android Build
```bash
ionic capacitor add android
ionic capacitor build android
```

## Version

Current version: 0.0.1

## License

This project is private and confidential.
