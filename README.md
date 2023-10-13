# Currency Converter App

A simple Spring Boot application for currency conversion using real-time exchange rates from the CurrencyApi.com API.


## Introduction

This Spring Boot application allows users to convert currencies with real-time exchange rates provided by the CurrencyApi API. Users can input the source currency, target currency, and the amount to convert, and the application will provide the converted amount.

## Features

- Real-time currency conversion using the CurrencyApi API.
- Simple and user-friendly web interface.
- Easy-to-configure API key for real-time exchange rates.
- Any historical data related to currency exchange can be checked.
- All logs history gets stored in the Database, and can be seen on UI.
- Multiple language Support.
- Testing with JUnit and the Spring testing framework.

## Prerequisites

Before getting started, make sure you have the following prerequisites:

- Java Development Kit (JDK)
- Apache Maven
- Git
- Your CurrencyApi API key (sign up at https://CurrencyApi/)

## Installation

1. Clone the repository:

   

2. Build the project using Maven:

Maven clean install

3.Configuration
Open the src/main/resources/application.properties file.

Set your CurrencyApi API key:
CurrencyApi key=YOUR_API_KEY_HERE
You can buy your API key from https://currencyapi.com/. 
You can have upto 300 free API hits for one month.



4.Usage
Run the Spring Boot application:
mvn spring-boot:run
Access the application in your web browser at http://localhost:8080.
Use the currency converter by entering the source currency, target currency, and amount.
Click "Convert" to see the conversion result.






