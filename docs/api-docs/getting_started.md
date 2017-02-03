---
layout: default
title: API Basics
nav: basics
---

### Getting Started

The current version of the API is version 0, which is a prototype.

It is a GET API with two endpoints. Both return an array of Airfares based on the parameters sent.


#### Endpoints

| Endpoint | What it does |
| ------------- | -------------|
| ```/citypairs/airfares``` | Returns an array of Airfares based on query parameters
| ```/citypairs/airfares/{id}``` | Returns an array of Airfares based on unique identifier. Array will contain one airfare. (This is just for demonstration purpose. For City Pairs, the ID does not have meaning.)

#### Versions

| Version | Date | Changes
| ------------- | -------------|
| ```version 0``` | 1/10/2017 | Initial deployment of prototype



##### Usage Notes

 *  All fares are listed one-way and valid in either direction. Domestic fares include all existing Federal, State, and local taxes, as well as airport maintenance fees and other administrative fees. Domestic fares do not include fees such as passenger facility charges, segment fees, and passenger security service fees. For FY10 and beyond, international fares are exclusive of taxes and fees, but inclusive of fuel surcharge fees.
 *  Fuel surcharge fees may be different in a particular market depending on the origin and destination city.
 *  For domestic routes, please use the airport code. City codes (e.g., Washington(WAS)) are for use with international routes.

#### Disclaimer
The fuel surcharge and baggage fees are an estimate and may change prior to the date of travel. These estimates are provided based on current data and are updated regularly, to provide travelers an estimate of total airline travel costs.






<body id="basics"></body>
