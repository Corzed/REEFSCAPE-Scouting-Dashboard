# REEFSCAPE Dashboard

A lightweight web dashboard for visualizing scoring data from The Blue Alliance (TBA). The dashboard displays two interactive stacked bar charts—one for Reef scoring and one for Algae & Endgame scoring—and an overall ranking table. It also includes a toggle button to switch between teleop and autonomous ("auto") scoring views.

## Features

- **Dynamic Data Loading:** Fetch match data from TBA using an Auth Key and Event Key.
- **Reef Stacked Bar Chart:** Visualizes Reef scoring (L1–L4) using teleop or auto data.
- **Algae + Endgame Chart:** Displays stacked bars for Processor, Net, and Endgame Barge points.
- **Overall Ranking Table:** Ranks teams based on aggregated average scores.
- **Toggle Scoring Mode:** Switch easily between teleop and auto scoring views.
- **Download JSON:** Download the raw JSON data for further analysis.

## Getting Started

### Prerequisites

- A valid TBA API key (TBA Auth Key) and Event Key from The Blue Alliance.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Corzed/REEFSCAPE-Scouting-Dashboard.git
   cd REEFSCAPE-Scouting-Dashboard
   ```
2. **Open the Dashboard**:
   
   Open index.html in your web browser.
