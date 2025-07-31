# Fest Vibes AI

## Overview

The comprehensive project is aimed at scraping music event information from various online sources. It intends to organize this data by various properties: artist, venue, genre, location, etc, and presents it in a clean, user-friendly interface, allowing users to explore and discover upcoming music events. They can plan their nitelife days in advanced with friends, and even coordinate ride shares. Not only does the frontend provide data insights, but at the heart of the app is Boomy, the chat interface providing personalized insights into your local night life. Together, the app envisions allowing users to have their own music festival organized to fit their unique 'vibe' any night of the week.

The project consists of three major components:

- **ETL Pipeline**: Scrapes event information from online sources and loads it.
- **API**: User Registration, data analytics, and CMS.
- **Client**: Dashboards, schedules, and chat interface. (Current version is deprecated)
- **LangGraph RAG**: Retrieval-Augmented Generation system using LangChain for intelligent event recommendations and personalized insights. (Forthcoming)

## Purpose & Impact

This project provides a valuable tool for tracking and predicting trends in the music industry. By aggregating global event data, users can gain insights into which artists, genres, or regions are rising in popularity. This information can help predict cultural shifts in music and enable businesses, event organizers, and marketers to tap into future markets early.

## Deployment

The backend is deployed to AWS Lambda, and the frontend can be deployed using Netlify or similar services.
