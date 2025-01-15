# Portfolio Tracker

Portfolio Tracker is a web application for managing a stock portfolio. The application allows users to:
- Add, edit, and delete stocks in their portfolio
- View the total portfolio value
- See the top-performing stock
- Visualize portfolio distribution

## Tech Stack

- **Frontend**: React.js
- **Backend**: Spring Boot
- **Database**: H2 Database (or any other supported database)
- **Deployment**: Vercel (frontend), Railway (backend)

---

## How to Run the Project Locally

### Prerequisites

- Node.js (v14 or later)
- Java JDK (v11 or later)
- Maven
- Git

### Setup Instructions

#### Clone the Repository
```bash
$ git clone https://github.com/Rawan969/Assignment-Full.git
$ cd Assignment-Full
```

---

### Backend Setup (Spring Boot)

1. Navigate to the backend directory:
```bash
$ cd springBoot
```

2. Build and run the application:
```bash
$ mvn spring-boot:run
```

3. The backend server will start at: [http://localhost:8080](http://localhost:8080)

4. (Optional) Change the database settings in `application.properties` if needed.

---

### Frontend Setup (React.js)

1. Navigate to the frontend directory:
```bash
$ cd portfolio-tracker
```

2. Install dependencies:
```bash
$ npm install
```

3. Start the development server:
```bash
$ npm start
```
