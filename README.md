# Clash of Clans XP Calculator

A simple web-based calculator to help Clash of Clans players determine how much XP they need to reach their target level and estimate the time required.

## Features

- Calculate total XP needed between two levels
- View detailed breakdown of XP requirements for each level
- Estimate time to reach target level based on XP per hour rate
- Clean, responsive web interface
- Works offline - no internet connection required

## How to Use

1. Enter your current level
2. Enter your target level
3. Optionally enter your estimated XP per hour rate
4. Click "Calculate" to see results
5. Use "Show Level Breakdown" to see XP requirements for each individual level

## XP Formula

The calculator uses the official Clash of Clans XP formula:
- Level 1: 30 XP
- Levels 2-200: 50 × (level - 1) XP
- Levels 201-299: 500 × (level - 200) + 9,500 XP
- Levels 300+: 1,000 × (level - 300) + 60,000 XP

## Usage

Simply open `index.html` in any modern web browser to use the calculator.

## License

This project is open source and available under the MIT License.
