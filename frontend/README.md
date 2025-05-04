# Fitness Management System Frontend

A modern web application for fitness management, built with Vue.js 3 and Vite.

## Features

- User authentication and authorization
- Real-time chat and notifications using SignalR
- Rich text editing with WangEditor
- Markdown support with v-md-editor
- Interactive charts with ECharts
- Modern UI components from Element Plus and Ant Design Vue
- Responsive design for all devices

## Tech Stack

- **Framework**: Vue.js 3
- **Build Tool**: Vite
- **State Management**: Vuex 4
- **Routing**: Vue Router 4
- **UI Libraries**:
  - Element Plus
  - Ant Design Vue
  - Arco Design
- **Real-time Communication**: SignalR
- **HTTP Client**: Axios
- **Rich Text Editor**: WangEditor
- **Markdown Editor**: v-md-editor
- **Charts**: ECharts
- **Styling**: Stylus

## Project Structure

```
src/
├── assets/        # Static assets
├── components/    # Reusable Vue components
├── mixins/        # Vue mixins
├── router/        # Vue Router configuration
├── store/         # Vuex store modules
├── views/         # Page components
├── App.vue        # Root component
└── main.js        # Application entry point
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Development

Run the development server:
```bash
npm run dev
# or
yarn dev
```

### Building for Production

Build the project for production:
```bash
npm run build
# or
yarn build
```

Preview the production build:
```bash
npm run preview
# or
yarn preview
```

## API Integration

The application integrates with a backend API running at `http://localhost:8080`. Key endpoints include:

- User authentication
- Post management
- Recipe updates
- Coach comments
- Real-time notifications

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is private and proprietary.

## Support

For support, please contact the development team.
