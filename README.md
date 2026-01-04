# Salary Counter

A real-time salary calculator that shows your earnings during work hours. Perfect for tracking your daily income every second!

## Features

- Real-time salary calculation
- Different rates for weekdays and weekends
- Customizable work hours (start/end time)
- Cross-browser compatibility (IE11+)
- Clean, dark-themed UI
- Single HTML file - no dependencies!

## Usage

1. Open `salary-counter.html` in any browser
2. The counter automatically starts tracking during work hours
3. Shows:
   - Current time
   - Today's earnings (green)
   - End of day total (blue)
   - Pre-work status (gray)

## Configuration

Edit these variables in the script section:

```javascript
var WORK_START_HOUR = 8; // Work start hour
var WORK_START_MINUTE = 15; // Work start minute
var WORK_END_HOUR = 17; // Work end hour
var WORK_END_MINUTE = 15; // Work end minute
var WEEKDAY_SALARY_PER_MINUTE = 2.7; // Weekday rate (per minute)
var WEEKEND_SALARY_PER_MINUTE = 3.3; // Weekend rate (per minute)
```

## Browser Support

- Chrome, Firefox, Edge, Safari
- Internet Explorer 11+
- Mobile browsers

## Project Structure

- `salary-counter.html` - Single file containing all HTML, CSS, and JS
- `README.md` - This file

## Technical Details

- Pure HTML/CSS/JavaScript (ES5 for IE11 compatibility)
- No frameworks or dependencies
- CSS with IE11 fallbacks
- Real-time updates using setTimeout with millisecond precision

## Contributing

- Feel free to fork and customize for your own work schedule!

## License

- MIT License - feel free to use this for any purpose.
