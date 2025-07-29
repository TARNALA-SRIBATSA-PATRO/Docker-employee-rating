# Employee Rating System

A Spring Boot application for employee performance rating and evaluation.

## Features

- Employee management
- Performance rating system
- Email notifications
- PDF and Excel report generation
- Docker support for deployment

## Technology Stack

- **Backend**: Spring Boot 2.7.18
- **Database**: PostgreSQL (Production), MySQL (Development)
- **Build Tool**: Maven
- **Container**: Docker
- **Deployment**: Render

## Environment Variables

For production deployment on Render:

```
SPRING_PROFILES_ACTIVE=prod
SPRING_DATASOURCE_URL=your_postgresql_url
SPRING_DATASOURCE_USERNAME=your_username
SPRING_DATASOURCE_PASSWORD=your_password
SPRING_JPA_HIBERNATE_DDL_AUTO=update
SPRING_JPA_PROPERTIES_HIBERNATE_DIALECT=org.hibernate.dialect.PostgreSQLDialect
```

## Local Development

1. Clone the repository
2. Run with MySQL database
3. Access at `http://localhost:8080`

## Production Deployment

1. Deploy to Render with Docker
2. Configure PostgreSQL database
3. Set environment variables
4. Access via Render URL 