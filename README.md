# Pharmacy Platform — Arabic Web Prototype

An Arabic, right-to-left web application prototype presenting pharmacy-related workflows for customers, pharmacies, and administrators.

## Current Prototype Scope

- Customer-facing medicine browsing and order interface.
- Pharmacy-oriented inventory and order screens.
- Administrator-facing management screens.
- Arabic RTL layout and responsive web presentation.

## Current Repository Structure

The current prototype is delivered as a single `index.html` file. It references environment-specific SDK files at `/_sdk/element_sdk.js` and `/_sdk/data_sdk.js`; these dependencies are not included in this repository.

## Important Limitations

- Treat this repository as a frontend prototype, not a verified production pharmacy service.
- Some sample records in the interface are demonstration data.
- A production release requires a documented backend, database, authentication and authorization, pharmacy verification, secure order handling, audit logs, and privacy controls.
- Do not use the prototype to make medical or medication decisions.

## Suggested Engineering Steps

1. Separate HTML, styles, and application logic into maintainable modules.
2. Document the domain model and role permissions.
3. Define API contracts and database entities.
4. Replace environment-specific SDK calls with documented services.
5. Add tests for authentication, inventory, orders, and authorization.
