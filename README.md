# Hotel Reservation System API

## Overview

This is a simple hotel reservation API built with Django REST Framework.

## Features

- List all hotels (`GET /api/hotels/`)
- Add a new hotel (`POST /api/hotels/`)

## Setup

```bash
git clone <repo-url>
cd hotel_api
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
