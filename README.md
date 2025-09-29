# NewsMag - React News Magazine

A modern, responsive news magazine application built with React and Vite, featuring category-based news filtering powered by the News API.

## Features

- 📱 **Responsive Design** - Built with Bootstrap for mobile-first experience
- 🗂️ **Category Filtering** - Browse news by Technology, Business, Health, Sports, and Entertainment
- 🔄 **Real-time Updates** - Fetches latest news from News API
- ⚡ **Fast Performance** - Powered by Vite for lightning-fast development and builds
- 🎨 **Modern UI** - Clean, intuitive interface with Bootstrap styling

## Technologies Used

- **React** - Frontend framework
- **Vite** - Build tool and development server
- **Bootstrap** - CSS framework for responsive design
- **News API** - Real-time news data
- **ESLint** - Code linting and quality

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- News API key (get one from [newsapi.org](https://newsapi.org))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ifrahsayyada/NewsMAg.git
   cd NewsMAg
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your News API key:
   ```
   VITE_API_KEY=your_news_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── Components/
│   ├── Navbar.jsx      # Navigation with category filters
│   ├── NewsBoard.jsx   # Main news container
│   └── NewsItem.jsx    # Individual news card component
├── App.jsx             # Main application component
└── main.jsx           # Application entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).
