# AJF Live Re-Wire

## Overview

AJF Live Re-Wire is a comprehensive project aimed at scraping music event information from various online sources, such as Livewire. It organizes this data by artist and presents it in a clean, user-friendly interface, allowing users to explore and discover upcoming music events.

The project consists of two major components:

- **Backend**: Scrapes event information from online sources and formats it.
- **Frontend**: Displays the event data in an intuitive interface, listing artists in alphabetical order.

## Purpose & Impact

This project provides a valuable tool for tracking and predicting trends in the music industry. By aggregating global event data, users can gain insights into which artists, genres, or regions are rising in popularity. This information can help predict cultural shifts in music and enable businesses, event organizers, and marketers to tap into future markets early.

## Project Structure

The project is organized into two submodules:

### 1. Backend (Event Scraper)

- Scrapes music event data from sources like [Livewire](https://www.wwoz.org/calendar/livewire-music).
- Handles error cases such as missing events, fetch errors, or parsing issues.
- Provides an API endpoint to retrieve the event data in a structured format.

### 2. Frontend (AJF-LIVE-RE-WIRE-Client)

- A React application that displays the scraped event data in a user-friendly manner.
- Lists artists in alphabetical order with event details.

## Navigation

To explore the project:

1. Clone the main repository, which includes both the backend and frontend:
   ```bash
   git clone https://github.com/aaronfeingold/ajf-live-re-wire.git
   ```
2. Navigate to the backend directory for scraping functionality:
   ```bash
   cd backend
   ```
3. Navigate to the frontend directory to view the client:
   ```bash
   cd client
   npm install
   npm start
   ```

## Impact of this Project

By analyzing global music event data, we can better understand cultural shifts and predict future trends in the music industry. This project can be instrumental for:

- **Marketers** looking to target emerging music markets.
- **Event Organizers** identifying trending genres or artists for concerts and festivals.
- **Artists and Labels** tracking their competition or expanding into new markets.

The ability to predict global music culture shifts gives stakeholders a strategic advantage in their respective industries.

## Deployment

The backend is deployed to AWS Lambda, and the frontend can be deployed using Netlify or similar services.

Backend:

- AWS Lambda for scraping and API delivery.
