# Reactivities

Welcome to Reactivities, a web application for managing activities and events! This project utilizes a tech stack consisting of C#, ASP.NET Core, React with TypeScript, Entity Framework Core, Semantic UI, and Vite.

## Getting Started

### Prerequisites

- [.NET 7](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/en/download/)

### Installation

1. Navigate to the API directory:
```
cd reactivities/API
```

2. Install dependencies and run the API:
```
dotnet restore
dotnet watch --no-hot-reload
```

4. Open a new terminal and navigate to the Client App directory:
```
cd reactivities/client-app
```

5. Install dependencies and start the client app:
```
npm install
npm start
```

6. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to view the Reactivities website.
   
8. Login using the following credentials:
  + Username: bob@test.com (for any username in the format username@test.com)
  + Password: Pa$$w0rd

## Features

- **Activity Management**: Create, edit, and delete activities.
- **Real-time Updates**: Receive real-time updates on activities using SignalR.
- **User Authentication**: Sign up and log in with email and password authentication.
- **Profile Management**: Users can create and manage their profiles.
- **Photo Upload**: Users can upload and delete photos.
