# ALX Travel App 0x01

A Django REST Framework-based travel app for managing property listings and bookings.

## Features
- CRUD operations for Listings and Bookings via RESTful API endpoints
- Authenticated access for creating and modifying resources
- Swagger/OpenAPI documentation

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/stephtim/alx_travel_app_0x01.git
   cd alx_travel_app_0x01
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
4. **Create a superuser (optional):**
   ```bash
   python manage.py createsuperuser
   ```
5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

## API Endpoints
All endpoints are accessible under `/api/`:

### Listings
- `GET /api/listings/` — List all listings
- `POST /api/listings/` — Create a new listing
- `GET /api/listings/{id}/` — Retrieve a listing
- `PUT /api/listings/{id}/` — Update a listing
- `DELETE /api/listings/{id}/` — Delete a listing

### Bookings
- `GET /api/bookings/` — List all bookings
- `POST /api/bookings/` — Create a new booking
- `GET /api/bookings/{id}/` — Retrieve a booking
- `PUT /api/bookings/{id}/` — Update a booking
- `DELETE /api/bookings/{id}/` — Delete a booking

## API Documentation
- Swagger UI: `/swagger/`
- Redoc: `/redoc/`

## Testing Endpoints
Use [Postman](https://www.postman.com/) or similar tools to test GET, POST, PUT, DELETE requests for both listings and bookings endpoints.

## License
BSD License
