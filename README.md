# MovieScope

**MovieScope** is a movie discovery and information platform designed to help users explore movies, search titles, discover genres, and access detailed movie information.

## Project Vision

Build a premium, responsive movie discovery experience backed by a modular Java Servlet application and The Movie Database (TMDB) API.

## Technology Stack

### Backend
- Java 17
- Jakarta Servlets
- Apache Tomcat 10.1
- Maven
- Jackson
- JUnit 5
- Mockito

### Frontend
- HTML5
- CSS3
- JavaScript
- Fetch API

### Tools and Infrastructure
- Git and GitHub
- IntelliJ IDEA
- Docker

## Planned Features

### Release 1 — Movie Discovery
- Trending and popular movies
- Movie search
- Movie details
- Genre exploration
- Responsive interface
- External API integration

### Release 2 — Personalization
- User registration and login
- Favorites
- Watchlists
- Search history

### Release 3 — Advanced Discovery
- Advanced filtering
- Improved recommendations
- Enhanced discovery experience

### Release 4 — Production Readiness
- Automated testing
- Security review
- Docker deployment
- Cloud deployment
- Monitoring and documentation

## Architecture

MovieScope follows a modular monolith architecture.

The frontend communicates with the Java Servlet backend through versioned REST-style JSON endpoints. The backend integrates with TMDB through a dedicated API client.

## Project Structure

```text
moviescope/
├── frontend/
├── backend/
├── docs/
├── README.md
├── LICENSE
└── .gitignore
```

## Development Status

Currently establishing the repository and backend foundation.

## External API

Movie data will be provided by [TMDB](https://www.themoviedb.org/).

## License

This project is licensed under the MIT License. See the LICENSE file for details.