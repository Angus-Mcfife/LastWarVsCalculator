# Last War VS Calculator

A PyQt6-based desktop application to help players of *Last War* calculate resource requirements to achieve point goals for daily tasks, factoring in tech tree bonuses. The app features a user-friendly interface with real-time updates, a dark teal theme, and support for both quantity-based and points-based calculations.

## Features
- **Daily Task Tabs**: Six tabs for each day, with customizable tasks (e.g., Stamina, Radar Tasks, Hero XP).
- **Point Goal Calculation**: Set a point goal per day and allocate percentages to tasks to calculate required resources.
- **Tech Tree Bonuses**: Input tech tree levels to apply bonuses (e.g., Radar, Speed-ups) to calculations.
- **Real-Time Updates**: Scores and resource requirements update instantly with a 50ms debounce timer.
- **User-Friendly UI**:
  - Dark teal theme with white text for readability.
  - Comma-separated number formatting for large values (e.g., `1,000,000.00`).
  - Clear labels ("Calculate from Points (%)") and tooltips for percentage inputs.
- **Validation**: Ensures percentages sum to 100% when using points-based calculations.
- **Cross-Platform**: Built with PyQt6, compatible with Windows, macOS, and Linux.
