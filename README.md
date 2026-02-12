# IADAI204-2405426-hemer-Pandya

📘 README.md

Interactive Analytics Dashboard — Airbnb Urban Insights

⸻

🔷 Project Overview

This project presents an interactive analytics dashboard that transforms Airbnb listing data into actionable insights about pricing, neighborhood popularity, traveler behavior, and housing availability in U.S. cities.

The dashboard was designed to simulate real-world consulting analytics used by Airbnb strategists, city planners, and tourism analysts. It applies principles of data storytelling to reveal how short-term rentals influence urban markets and traveler decisions.

The primary objective is to enable stakeholders to explore patterns dynamically and make informed strategic decisions based on data-driven evidence.

Figma Prototype:
https://www.figma.com/make/eoyuPW1ltE6VRLvvVLrA00/Design-Analytics-Dashboard-UI?t=6Evyz2J6wrtKbvXx-1

⸻

🔷 Purpose & Target Audience

Purpose

To convert raw Airbnb listing data into a visual storytelling dashboard that supports strategic decisions about tourism, pricing, and housing availability.

Audience
	•	Airbnb executives evaluating listing performance
	•	City planners assessing tourism pressure
	•	Housing policy researchers
	•	Business analysts and consultants

The dashboard answers:
	•	Where is Airbnb activity concentrated?
	•	How does pricing vary across markets?
	•	What accommodation types dominate?
	•	How does availability impact housing?

⸻

🔷 Dataset Summary

Dataset: Airbnb US Listings 2023
Source: Public Airbnb dataset

The dataset contains listing-level information including:
	•	price
	•	city
	•	neighborhood
	•	room_type
	•	availability_365
	•	number_of_reviews
	•	reviews_per_month
	•	latitude & longitude

Each row represents a unique Airbnb listing.

⸻

🔷 Data Cleaning & Preparation

To ensure accuracy and usability, the dataset underwent the following preprocessing:
	•	Removed duplicate listings
	•	Converted price field to numeric format
	•	Filled missing review activity with zero
	•	Removed unrealistic price outliers
	•	Removed extreme minimum-night values
	•	Standardized categorical fields
	•	Verified geographic coordinates
	•	Ensured consistent city labels

These steps ensured the dashboard reflects realistic market behavior.

⸻

🔷 Exploratory Data Analysis

The analysis focused on answering key strategic questions:
	•	Which cities have the highest pricing tiers?
	•	Where are tourism hotspots concentrated?
	•	Which room types dominate each market?
	•	How does availability signal housing pressure?
	•	Is engagement correlated with price?

EDA revealed clustering patterns, accommodation dominance, and mid-range pricing advantages.

⸻

🔷 Dashboard Features

The dashboard contains five major visual components:

1. Price Comparison by City

Bar chart showing average listing prices and engagement levels.

2. Neighborhood Popularity Heatmap

Geographic visualization of tourism concentration.

3. Room Type Distribution

Stacked bar chart comparing accommodation types.

4. Availability Analysis

Neighborhood availability patterns across the calendar year.

5. Price vs Reviews Scatter Plot

Correlation analysis between cost and engagement.

⸻

🔷 Interactive Controls

Users can dynamically explore the dashboard using:
	•	City filter
	•	Room type selector
	•	Price range slider
	•	Review count slider
	•	Hover tooltips
	•	Legend highlighting

All visuals update in real-time, enabling multi-angle exploration.

⸻

🔷 Key Insights
	•	Pricing varies significantly between cities
	•	Tourism demand clusters around specific neighborhoods
	•	Entire homes dominate the Airbnb supply
	•	Some areas show housing availability pressure
	•	Mid-priced listings generate strongest engagement

These insights inform pricing strategy, tourism policy, and housing planning.

⸻

🔷 Context & Annotations

The dashboard includes embedded annotations that highlight major findings directly within visuals. These callouts guide users toward meaningful conclusions rather than forcing them to interpret charts independently.

Examples:

“Tourism is heavily concentrated in high-review neighborhoods.”

“Mid-priced listings attract the highest engagement.”

Annotations transform visuals into a narrative experience.

⸻

🔷 Testing & Validation

The dashboard was tested for:
	•	filter responsiveness
	•	tooltip clarity
	•	chart accuracy
	•	data consistency
	•	usability flow

Peer testing confirmed that users can identify key insights within seconds.

⸻

🔷 Dashboard Navigation

Users begin with city-level overview, drill into neighborhood patterns, compare accommodation types, and finally explore pricing relationships.

The layout is designed to guide storytelling logically from macro trends to micro insights.


🔷 Conclusion

This dashboard demonstrates how interactive data storytelling can reveal complex urban tourism dynamics in an accessible format. By combining analytics with visualization, stakeholders can explore patterns that influence pricing, traveler behavior, and housing markets.

The project highlights the importance of clean data, structured analysis, and intentional dashboard design.

⸻

🔷 Future Improvements
	•	Incorporate time-series seasonal trends
	•	Add host-level performance metrics
	•	Integrate external housing market datasets
	•	Include predictive demand modeling
	•	Expand geographic coverage
