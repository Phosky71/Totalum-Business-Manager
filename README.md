# Totalum Business Manager

A full-stack business management application built with Angular 19 and integrated with Totalum SDK. This responsive web application provides comprehensive CRUD operations for managing clients, orders, and products in a business environment.

## 🚀 Features

- **Client Management**: Complete CRUD operations for managing customer information
- **Order Management**: Track and manage orders with full lifecycle support
- **Product Management**: Maintain product catalog with detailed information
- **Material Design UI**: Modern and responsive interface using Angular Material
- **Search & Pagination**: Efficient data browsing with search capabilities
- **Confirmation Dialogs**: User-friendly confirmation prompts for critical operations
- **State Management**: Reactive state management using RxJS
- **REST API Integration**: Seamless communication with Totalum backend services

## 🛠️ Technologies

- **Angular 19**: Latest version of the Angular framework
- **TypeScript**: Type-safe development
- **Angular Material**: UI component library
- **RxJS**: Reactive programming for state management
- **Totalum SDK**: Backend integration services
- **CSS**: Custom styling and responsive design

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v18 or higher)
- npm or yarn package manager
- Angular CLI (`npm install -g @angular/cli`)

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/Phosky71/Totalum-Business-Manager.git
cd Totalum-Business-Manager
```

2. Install dependencies:

```bash
npm install
```

## 🚦 Development Server

To start a local development server:

```bash
ng serve
```

Once the server is running, navigate to `http://localhost:4200/` in your browser. The application will automatically reload whenever you modify source files.

## 🏗️ Building

To build the project for production:

```bash
ng build
```

The build artifacts will be stored in the `dist/` directory. The production build is optimized for performance and speed.

## 🧪 Testing

### Running Unit Tests

Execute unit tests with the Karma test runner:

```bash
ng test
```

### Running End-to-End Tests

For end-to-end testing:

```bash
ng e2e
```

Note: Angular CLI does not include an e2e testing framework by default. Choose one that suits your needs.

## 📁 Project Structure

```
src/
├── app/
│   ├── components/      # Shared components
│   ├── pages/           # Feature modules
│   │   ├── clientes/    # Client management
│   │   ├── pedidos/     # Order management
│   │   └── productos/   # Product management
│   └── totalum/         # Totalum SDK services
├── assets/              # Static assets
└── styles/              # Global styles
```

## 🔌 API Integration

The application integrates with Totalum SDK for backend operations:

- **Client Service**: `src/totalum/service.clientes.ts`
- **Order Service**: `src/totalum/service.pedidos.ts`
- **Product Service**: `src/totalum/service.productos.ts`
- **Core Service**: `src/totalum/totalum.service.ts`

## 📝 Code Scaffolding

Generate new components using Angular CLI:

```bash
# Generate a component
ng generate component component-name

# Generate a service
ng generate service service-name

# See all available schematics
ng generate --help
```

## 🎨 Styling

The application uses a combination of:

- Angular Material for UI components
- Custom CSS for specific styling needs
- Responsive design principles for mobile compatibility

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is part of a technical assessment and is provided as-is for demonstration purposes.

## 📚 Additional Resources

- [Angular Documentation](https://angular.dev)
- [Angular CLI Documentation](https://angular.dev/tools/cli)
- [Angular Material](https://material.angular.io)
- [RxJS Documentation](https://rxjs.dev)

## 👤 Author

**Antonio Juan** (Phosky71)

---

*Built with ❤️ using Angular 19*
