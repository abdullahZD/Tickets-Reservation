# Django Movie Ticket Booking Project

This is a Django project for a movie ticket booking system. It provides a RESTful API for managing guests, movies, and reservations.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

- Python 3.x
- Django 3.x
- Django Rest Framework

### Installation

1. Clone the repository:

```bash
2.git clone https://github.com/your-username/django-movie-ticket-booking.git
3.cd django-movie-ticket-booking
4.python3 -m venv venv
5.source venv/bin/activate
6.pip install -r requirements.txt
7.python manage.py makemigrations
8.python manage.py migrate
9.python manage.py runserver



###API Endpoints
/django/jsonresponsenomodel/ - Example of a Django view that returns a JSON response without using a model.
/django/jsonresponsefrommodel/ - Example of a Django view that returns a JSON response using a model.
/rest/fbvlist/ - Example of a Django REST Framework function-based view (FBV) for listing and creating records.
/rest/fbv/<int:pk>/ - Example of a Django REST Framework FBV for retrieving, updating, and deleting a specific record.
/rest/cbv/ - Example of a Django REST Framework class-based view (CBV) for listing and creating records.
/rest/cbv/<int:pk>/ - Example of a Django REST Framework CBV for retrieving, updating, and deleting a specific record.
/rest/mixins/ - Example of a Django REST Framework CBV using mixins for listing and creating records.
/rest/mixins/<int:pk>/ - Example of a Django REST Framework CBV using mixins for retrieving, updating, and deleting a specific record.
/rest/generics/ - Example of a Django REST Framework CBV using generics for listing and creating records.
/rest/generics/<int:pk>/ - Example of a Django REST Framework CBV using generics for retrieving, updating, and deleting a specific record.
/rest/viewsets/ - Example of Django REST Framework viewsets for managing guests, movies, and reservations.
/fbv/findmovie/ - Find a movie by its title using a Django function-based view.
/fbv/newreservation/ - Create a new reservation using a Django function-based view.
/api-token-auth/ - Obtain an authentication token for token-based authentication.

pip install -r requirements.txt
