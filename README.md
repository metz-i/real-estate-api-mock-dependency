# Real Estate API

This application exposes endpoints for basic CRUD operations on a model and manages an in memory list of those objects.

## Startup

Open the RealEstateApplication file and use the green play button in the left gutter to start the application.

The server will start on `localhost:8085`

## JSON Body

Use the following as a JSON body for a POST. We do not supply an id on the POST, as that is the application's job to manage.
```
{
    "name": "Rental",
    "imageUrl": "http:www.rentals.com/Rental"
}
```