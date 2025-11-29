# API Design - Hackathon Project

## Authentication Routes
- POST /api/auth/signup
- POST /api/auth/login
- POST /api/auth/logout

## Admin Routes
- GET /api/admin/webinars
- POST /api/admin/webinars
- PUT /api/admin/webinars/:id
- DELETE /api/admin/webinars/:id

## Student Routes
- GET /api/student/webinars
- POST /api/student/register/:webinarId
- GET /api/student/my-registrations
- GET /api/student/resources

## Database Models
- User (email, password, name, role)
- Webinar (title, description, date, maxCapacity)
- Registration (userId, webinarId, registrationDate)
- Resource (webinarId, fileName, url)

Detailed endpoint documentation to be added during development.
