# React Live Editor 🚀

A powerful, interactive React code editor with live preview capabilities, built with React and Tailwind CSS. This editor allows you to write and preview React components in real-time, with support for dark/light themes and package management.

## ✨ Features

- **Live Preview**: See your React components come to life in real-time
- **Dark/Light Theme**: Switch between comfortable viewing modes
- **Package Management**: Add and manage external dependencies
- **Error Handling**: Clear error reporting with proper error boundaries
- **Code Export**: Save your components directly to your machine
- **Responsive Design**: Works seamlessly on different screen sizes
- **Syntax Highlighting**: Makes your code more readable
- **Auto-refresh**: Preview updates as you type

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jagruthip2004/react-live-editor.git
   cd react-live-editor
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Install required peer dependencies:
   ```bash
   npm install react react-dom lucide-react
   # or
   yarn add react react-dom lucide-react
   ```

## 📦 Required Dependencies

- React 18.x
- Tailwind CSS 3.x
- lucide-react
- @/components/ui/alert (from your components library)

## 🚀 Usage

1. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Import and use the component:
   ```jsx
   import LiveCodeEditor from './components/LiveCodeEditor';

   function App() {
     return <LiveCodeEditor />;
   }
   ```

## 💡 Example

The editor comes with a default example demonstrating:
- React Hooks (useState, useEffect)
- Theme switching
- Interactive counter
- Dynamic updates
- Tailwind CSS styling

```jsx
import React, { useState, useEffect } from 'react';

export default function App() {
  const [count, setCount] = useState(0);
  const [theme, setTheme] = useState('light');
  
  // More example code available in the editor...
}
```

## 🎨 Customization

### Themes
The editor supports both light and dark themes. Theme colors can be customized in the code:

```jsx
// Example theme customization
const themes = {
  light: {
    background: 'bg-white',
    text: 'text-gray-800',
    // ...
  },
  dark: {
    background: 'bg-gray-900',
    text: 'text-gray-200',
    // ...
  }
};
```

### Package Management
Add external packages through the UI:
1. Enter package name in the input field
2. Click "Install" or press Enter
3. Package will be added to the list of available packages

## 🔧 API Reference

### Props

The `LiveCodeEditor` component currently doesn't accept any props, but you can modify the code to add customization options:

- `initialCode`: Initial code to display
- `customTheme`: Custom theme configuration
- `onSave`: Callback function when saving code
- `availablePackages`: Pre-defined list of available packages

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- Built with React and Tailwind CSS
- Icons from Lucide React
- Inspired by CodeSandbox and CodePen

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainers.

---

Made with ❤️ by Jagruthi Pentapati
