# Trans-European Digital Backbone Room

## One-sentence benefit
Helps connectivity planners coordinate strategic backbone projects, resilience evidence and European investment gaps.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![trans-European digital backbone workspace](docs/screenshot.png)

## Main features
Search backbone projects, create an investment case, progress readiness actions and monitor approval and high-priority gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Connectivity planners, cable operators, public investors and resilience teams need shared evidence for topology, capacity and funding decisions.

## Key workflows
Teams can find a backbone project, add a validated investment case and advance corrective work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable storage, GIS topology and funding-system integrations.

## Roadmap
Add cable maps, capacity forecasts, ownership controls, funding scenarios and audit-ready persistence.
