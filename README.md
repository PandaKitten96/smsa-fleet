# SMSA Fleet Management System

A comprehensive fleet management system for SMSA Express, featuring a Spring Boot backend and multiple frontend modules.

## Project Structure

- `src/`: Spring Boot backend source code.
- `frontend/`: Primary web frontend.
- `finance-ui/`: Finance-specific user interface.
- `pom.xml`: Maven configuration for the backend.
- `deploy.sh`: Deployment script.

## Getting Started

### Prerequisites

- Java 17 or higher
- Node.js and npm
- Maven

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PandaKitten96/smsa-fleet.git
   ```
2. Build the backend:
   ```bash
   ./mvnw clean install
   ```
3. Set up the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## Contributing

Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
