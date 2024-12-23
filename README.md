# LLM-Based Meeting Scheduling Assistant

## Overview

The LLM-Based Meeting Scheduling Assistant is a sophisticated tool designed to streamline the process of scheduling meetings. 
Powered by a Large Language Model (LLM), this assistant automates scheduling tasks by understanding natural language requests, analyzing your calendar, and suggesting suitable meeting slots. 

## Features

1. **Natural Language Understanding**:  
   The assistant takes natural language requests as input, such as:  
   *"Schedule a meeting with Mohamed next week."*

2. **Calendar Integration**:  
   It integrates seamlessly with your calendar to check your availability and identify possible meeting slots.

3. **Smart Slot Suggestions**:  
   Based on the request constraints, the assistant suggests three possible time slots that work for you.

4. **Interactive Confirmation**:  
   You can select your preferred time slot from the suggestions.

5. **Automated Event Creation**:  
   The assistant creates a calendar event with a clear and descriptive title, e.g., *"Meeting with Mohamed"*, ensuring your calendar stays organized.

## Getting Started

### Prerequisites

- Python 3.10
- Access to the Google Calendar API

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/llm-meeting-scheduler.git
   cd llm-meeting-scheduler
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up the Google Calendar API**:
   - Follow the instructions in the `docs/GoogleCalendarAPI_Setup.md` file.
   - Place your credentials file (e.g., `calendar_credentials.json`) in a safe place.
   - Modify the `file_path` variable that indicates the path to your credentials in the relevant notebooks.

### Usage

1. **Run the Assistant** (not yet available):
   ```bash
   python main.py
   ```

2. **Input Meeting Request**:
   - Enter a meeting scheduling request, such as "schedule a meeting with Mohamed next week."

3. **Choose a Time Slot**:
   - The assistant will suggest three time slots based on your calendar. Choose one of them.

4. **Event Creation**:
   - The assistant will create a calendar event with a suitable title, such as "Meeting with Mohamed."

## Configuration

- **Time Zone**:  
  Set your time zone in the `config.json` file to ensure proper slot suggestions.

- **Meeting time slots**:
  By default, the assistant suggests meeting slots between 8:00 AM and 6:00 PM. You can customize this range in the `config.json` file.

- **Default Event Duration**:  
  The assistant defaults to a 30-minute meeting duration. You can adjust this in the `config.json` file.

- **LLM Model Configuration**:
  - Update the `config.json` file with your LLM model configuration.

