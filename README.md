Watchlog 🎬
Watchlog is a robust web application designed for a user to build a personal catalog of a movie or a TV series. It integrates with the TMDB API to fetch data and allows for detailed progress tracking of a specific season or an episode.

🎯 Key FeatureUser:
* User Authentication: Secure access using ASP.NET Core Identity
* External API Integration: Seamless import of a title from the TMDB database via HTTP.
* Personal Catalog: A dedicated space for a user to manage a personal movie or a series list.
* Progress Tracking: Mark a title as watched and update a viewing status for each specific season.
* Automated Testing: Comprehensive Unit Test coverage using xUnit and NSubstitute.

🛠️ Tech Stack:
* Framework: ASP.NET Core MVC (.NET 7).
* Database: MS SQL Server with Entity Framework Core.
* Security: Identity Framework with authorization policy and handler.
* Testing: xUnit, NSubstitute, and MockQueryable.

🏗️ Architecture - The project follows a clean, Layered Architecture to ensure maintainability:
* Web Layer: Handles a controller, a view, and DI configuration.
* Business Layer: Contains a service, a generic repository, and logic for an authorization requirement.
* Data Layer: Manages the database context, a configuration, and a migration.
* Model Layer: Defines a domain entity, a DTO, and a view model.
