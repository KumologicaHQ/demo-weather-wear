# Kumologica Weather Recommendation API

This repository contains the implementation of a weather recommendation API using **Kumologica**. The flow integrates a weather service API and OpenAI to provide personalized clothing suggestions based on real-time weather data.

## Features

- Accepts a city as input to determine the weather.
- Retrieves weather data from a third-party Weather API.
- Generates personalized recommendations using OpenAI.

---

## Prerequisites

1. Install the Kumologica Designer. Follow the [Kumologica installation guide](https://docs.kumologica.com/docs/guide/GettingStarted.html#installation).
2. Create a **free account** with [Weatherstack](https://weatherstack.com) and obtain your API key.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install the dependencies

`npm install`

### 3. Set Environment Variables

Create a .env file in the root directory and configure the following variables:

```
OPENAI_API_KEY=<Your OpenAI API Key>
WEATHERSTACK_API=<Your Weatherstack API Key>
```

### 4. Running Locally

To test the API locally, use a tool like Postman or CURL to make a request:

`GET http://127.0.0.1:1880/wear?city=sydney`
