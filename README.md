# Near Miss Finder

![Python](https://img.shields.io/badge/python-3.8%2B-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Status](https://img.shields.io/badge/status-active-brightgreen)

**Near Miss Finder** is a Python tool that analyzes Google Maps Location History data for two individuals to uncover "near misses"—moments when they were close to each other in space and time before meeting. Built with data processing, geospatial analysis, and interactive visualization, this project demonstrates skills in Python, pandas, geopy, and Folium.

Imagine discovering you and your partner were at the same coffee shop years ago, just hours apart! This tool maps those hidden connections using real location data.

---

## Features
- **Data Processing**: Parses Google Maps Timeline JSON files into a clean, usable format.
- **Geospatial Analysis**: Calculates distances between coordinates to find near misses within a customizable threshold (e.g., 500 meters, 1 hour).
- **Interactive Visualization**: Generates an HTML map with Folium, plotting near misses with timestamps and distances.
- **Command-Line Interface**: Easy-to-use script with configurable parameters.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Git (optional, for cloning)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/paultekofficial/near_miss_finder.git
   cd near_miss_finder

2. **Set Up a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
