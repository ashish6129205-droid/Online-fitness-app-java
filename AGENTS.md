You are working on a Java Programming academic project called Online Fitness Tracking Application.

Mandatory technology constraints:
- Java 17 or newer
- Maven
- Jakarta Servlets and a deployable servlet container or embedded server
- JDBC with PostgreSQL
- PostgreSQL database hosted on Neon
- No Node.js-only replacement
- No hard-coded production secrets

Functional requirements:
- Roles: ADMIN and USER
- Login/logout with session-based authorization
- Users can create, read, update, and delete their own workouts
- Users can update goals, view progress, and join challenges
- Admins can manage users, approve/reject content, view statistics, and update settings

Engineering requirements:
- Use prepared statements for all user input
- Keep SQL in repository/DAO classes, not in JSP pages
- Use a service layer where practical
- Validate form input server-side
- Use try-with-resources for JDBC resources
- Return useful error messages without exposing stack traces to users
- Include schema.sql and seed.sql
- Include tests for authentication and at least one workout operation
- Make the UI responsive for mobile and tablet screens
- Include a README with setup, database, deployment, demo accounts, and limitations.
```[span_71](start_span)[span_71](end_span)
