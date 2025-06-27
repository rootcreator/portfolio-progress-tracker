# Year Progress & Goals Tracker

![Project Preview](https://i.imgur.com/example-image.png)

A clean, responsive web application that tracks your yearly progress and helps you manage your goals with deadline awareness and progress tracking.

## Features

- **Year Progress Visualization**: See what percentage of the year has passed with a beautiful progress bar
- **Goal Management**: Add, track, and complete your personal goals
- **Smart Status Indicators**: Goals are automatically categorized as:
  - Upcoming (within 30 days)
  - Due Today
  - Overdue
  - Completed
- **Data Persistence**: All goals are saved in your browser's localStorage
- **Import/Export**: Backup your goals or transfer them between devices
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean interface with smooth animations

## Technologies Used

- HTML5, CSS3 (with CSS Variables)
- Vanilla JavaScript (no frameworks)
- LocalStorage for data persistence
- SVG icons for a crisp interface

## How to Use

1. **Add a Goal**:
   - Enter a goal name (e.g., "Read 12 books")
   - Set a target (e.g., "12" or "Complete")
   - Optionally add a deadline

2. **Track Progress**:
   - Update your current progress in the input field
   - Goals automatically mark as completed when progress matches target

3. **Filter Goals**:
   - View all goals or filter by status (upcoming, today, overdue, completed)

4. **Backup Your Data**:
   - Export your goals to a JSON file
   - Import previously exported goals

## Installation

No installation required! Simply open `index.html` in your browser.

For development:
1. Clone this repository
2. Open `index.html` in your preferred browser

## Customization

You can easily customize the appearance by modifying the CSS variables in the `:root` selector:

```css
:root {
  --primary-color: #4361ee;
  --primary-hover: #3a56d4;
  --success-color: #4cc9f0;
  --warning-color: #f8961e;
  --danger-color: #f94144;
  --text-color: #2b2d42;
  /* ... */
}
