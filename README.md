# Amp Usage Growth Model for Canva

A predictive forecasting tool designed for Canva to model and budget Amp spend as AI adoption scales across teams.

## Features

- **Interactive Dashboard**: Real-time growth projections with adjustable parameters
- **Configurable Baseline**: Set custom starting metrics (users, spend, lines changed)
- **Multiple Scenarios**: Conservative, moderate, and aggressive growth predictions
- **Live Charts**: Dynamic visualization of usage growth and cost distribution
- **Confidence Intervals**: Statistical projections with variance margins

## Screenshots

### Growth Model Dashboard
The main dashboard shows current metrics and growth projections across three scenarios.

### Configure Baseline
Easily adjust starting parameters to see how different baselines affect projections.

## Usage

1. Open `amp_growth_model (1).html` in your browser
2. Use the "Growth Model" tab to view projections
3. Switch to "Configure Baseline" to adjust starting metrics:
   - Active Users
   - Total Spend ($)
   - Lines Changed
4. Click "Apply & Return" to see updated projections
5. Adjust growth parameters using the sliders:
   - Target Users (100-1000)
   - Growth Period (3-24 months)
   - Usage Intensity Factor (0.5x-2.0x)

## Technical Details

- **Single HTML File**: No external dependencies required
- **Dark Theme**: Matches Amp's design system
- **Responsive Design**: Works on desktop and mobile
- **Real-time Calculations**: All metrics update instantly
- **Chart.js Integration**: Dynamic charts and visualizations

## Scenarios

### 🐌 Conservative Scenario
- Assumes gradual adoption with 70% of current usage intensity
- Lower risk projections for budget planning

### 🚀 Moderate Scenario  
- Balanced growth with current usage patterns maintained
- Most likely scenario based on current trends

### 🔥 Aggressive Scenario
- High adoption with 130% usage intensity (power users)
- Upper bound projections for capacity planning

## Methodology

- **Baseline Metrics**: Current active users, total spend, and lines changed
- **Growth Distribution**: Based on Pareto principle (20% of users generate 80% of usage)
- **Usage Patterns**: Maintains correlation between lines changed and spend
- **Confidence Intervals**: ±20% margin based on observed usage variance
- **Scaling Factor**: Linear scaling with adjustments for usage intensity

## Deployment

This tool runs entirely in the browser - simply open the HTML file or deploy to any web server.

---

Built with ❤️ by Amp for Canva's growth planning needs.
