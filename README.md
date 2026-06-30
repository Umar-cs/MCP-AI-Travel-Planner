


https://github.com/user-attachments/assets/9881985a-4837-4634-a242-868c519210a3


# MCP AI Travel Planner

A Streamlit app that creates detailed travel itineraries using natural-language preferences, real-time tool integrations, and MCP servers.

Instead of planning a trip manually across multiple sites, you can enter a destination, budget, travel style, and trip length, and the app generates a structured itinerary with accommodation ideas, local activities, transportation guidance, and a downloadable calendar file.

The project combines LLM reasoning with MCP-connected tools for travel research, including Airbnb listings, Google Maps-based location support, and web search for current trip context.

## Why this project?

Trip planning usually means jumping between maps, booking platforms, activity guides, and notes. This project brings those steps into one workflow so a user can describe the kind of trip they want and receive a practical, organized itinerary faster.

## Features

- Natural-language travel planning
- Day-by-day itinerary generation
- Budget-aware recommendations
- Airbnb MCP integration for accommodation discovery
- Google Maps integration for distance and travel-time context
- Web-search support for current destination information
- Downloadable `.ics` calendar export
- Streamlit interface for easy local use
- OpenRouter model selection from the UI

## Tech Stack

- Python
- Streamlit
- Agno
- MCP
- OpenRouter
- Airbnb MCP Server
- Google Maps API
- iCalendar

## How It Works

1. The user enters a destination, trip duration, budget, start date, and preferences.
2. The app connects to MCP servers for Airbnb and travel-planning workflows.
3. The agent uses OpenRouter with the selected model to generate a complete itinerary.
4. Supporting tools help enrich the result with location-aware and current travel context.
5. The itinerary can be downloaded as an `.ics` calendar file.

## Installation

### Prerequisites

- Python 3.10+
- Node.js with `npx` or `pnpm`
- An OpenRouter API key
- A Google Maps API key

### Setup

```bash
pip install -r requirements.txt
streamlit run app.py
```

Then open the local Streamlit URL and provide:

- `OpenRouter API Key`
- `Google Maps API Key`
- Your trip details and preferences

## Example Use Cases

- Plan a multi-day city vacation
- Build a budget-conscious travel itinerary
- Create a food-focused or sightseeing-focused trip
- Generate a shareable itinerary with calendar export
- Explore MCP-powered travel planning workflows

## Demo Video

A demo recording is already included in this project folder:

- `Traveler_MCP.mp4`

For the best GitHub presentation, include the video in the repository or attach it to a release so visitors can preview the app easily.

## Project Description for GitHub

Use this as the short repository description:

**Plan complete trips with AI using Streamlit, MCP servers, Airbnb data, Google Maps, and OpenRouter.**

## Future Improvements

- Add hotel and flight integrations
- Show itinerary maps directly in the UI
- Save and reload past trips
- Improve fallback behavior when MCP tools are unavailable
- Add region-specific budgeting and travel alerts
