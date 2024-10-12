# **AirTravelScheduler Using CouchBase**

## **Project Overview**:

This project leverages Couchbase as the database for a Trip Planner application. The database stores key travel-related entities such as airlines, airports, routes, and hotels, facilitating a structured and efficient travel management solution. Couchbase's N1QL query language is used to perform basic CRUD operations on the travel data stored as JSON documents.

## **Technologies Used**:

- Couchbase:
A NoSQL database used to manage and store travel-related documents (e.g., airlines, routes, hotels).
- Docker:
 Used to run the Couchbase server locally, accessible via localhost:8091.
- N1QL:
Couchbase's query language, used for performing CRUD operations on the database.

## **Data Entities**:

- Airlines:
Stores details about airline companies, including information like name, fleet size, headquarters, and destinations.
- Routes:
Contains information about flight routes, including departure and arrival airports, distance, and flight time.
- Airports:
Holds details about airports, such as name and location (city and country).
- Hotels:
Stores data about hotels, including the name and location of each property.
