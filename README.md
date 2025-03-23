# Case Pilot - Legal Case Management System

Case Pilot is a comprehensive legal case management system designed to streamline the workflow of legal professionals and provide easy access to case information for clients.

## Project Structure

This repository is organized as a monorepo containing three main components:

- `frontend/` - Next.js based web interface ([WeHack-TeamAmigos-Frontend](https://github.com/Jasharaj/WeHack-TeamAmigos-Frontend))
- `backend/` - Backend API server ([WeHack-TeamAmigos-Backend](https://github.com/Jasharaj/WeHack-TeamAmigos-Backend))
- `APP/` - Mobile application ([weHack](https://github.com/shadan1234/weHack))

## Getting Started

### Prerequisites

- Git
- Node.js (for Frontend and Backend)
- Flutter (for Mobile APP)

### Clone the Repository

```bash
# Clone the main repository
git clone https://github.com/Swayam-code/Case-Pilot-Amigos.git

# Initialize and update submodules
cd Case-Pilot-Amigos
git submodule init
git submodule update
```

### Setting Up Components

#### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

#### Backend Setup
```bash
cd backend
npm install
npm start
```

#### Mobile App Setup
```bash
cd APP
flutter pub get
flutter run
```

## Features

- **User Dashboard**: Manage and track legal cases
- **Document Management**: Store and organize legal documents
- **Case Timeline**: Track case progress and important dates
- **Client Portal**: Allow clients to view their case status
- **Mobile Access**: Access case information on the go

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Team

- Frontend Development: [Jasharaj](https://github.com/Jasharaj)
- Backend Development: [Jasharaj](https://github.com/Jasharaj)
- Mobile App Development: [Shadan](https://github.com/shadan1234)
- Project Lead: [Swayam](https://github.com/Swayam-code)
