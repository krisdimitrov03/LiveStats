
# LiveStats

LiveStats is a full-stack web application dedicated to providing real-time sports statistics and results, with a current focus on football. Inspired by platforms like SofaScore and FlashScore, LiveStats aims to deliver comprehensive, up-to-date sports data through a user-friendly interface.

## Features

- **Real-Time Updates:** Live scores, player statistics, and game events updated as they happen.
- **User Accounts:** Personalized experiences with favorite teams and notifications.
- **Historical Data:** Access to past match stats and outcomes.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies

- **Frontend:** React
- **Backend:** ASP.NET Core Web API
- **Database:** MS SQL Server
- **Deployment:** Docker, Docker Compose

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Docker
- Docker Compose

Ensure Docker and Docker Compose are installed on your system. For installation instructions, see [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/install/).

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/LiveStats.git
   cd LiveStats
   ```

2. **Environment Setup**

   Before running the application, ensure all environment variables are set correctly in a `.env` file at the root of the project. Sample variables include:

   ```plaintext
   DB_CONNECTION_STRING="YourConnectionString"
   API_KEY="SecretAPIKeyForThirdPartyServices"
   ```

3. **Running the Application**

   Use Docker Compose to build and run the containers for the application:

   ```bash
   docker-compose up --build
   ```

   This command will start all services specified in your `docker-compose.yml` file.

### Accessing the Application

Once the application is running, it can be accessed at: `http://localhost:3000`

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc.
