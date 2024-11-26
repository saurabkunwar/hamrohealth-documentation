Welcome to Hamro Health School's Documentation!
===============================================

.. note::

   This project is under active development.

Contents
--------

- API Endpoints
  - General Information
    - Get Recent Events

API Endpoints
=============

General Information
-------------------

### Get Recent Events

**Endpoint**: `/api/general-info/get-recent-events`  
**Method**: `GET`  

This endpoint retrieves a list of recent events based on the provided parameters.

#### Parameters

- `school_id` *(optional)*: The ID of the school.  
- `class_id` *(optional)*: The ID of the class.  
- `form_id` *(optional)*: The ID of the form.  

#### Example Request

```http
GET /api/general-info/get-recent-events?school_id=1&class_id=10&form_id=2 HTTP/1.1
Host: yourapi.example.com
Authorization: Bearer <your_token_here>
Content-Type: application/json
