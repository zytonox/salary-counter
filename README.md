# Salary Counter

A real-time salary calculator that shows your earnings during work hours. Perfect for tracking your daily income every second!

## Features

- Real-time salary calculation with second precision
- Different rates for weekdays and weekends
- Customizable work hours (start/end time)
- Lunch break support (paid/unpaid, adjustable duration)
- Cross-browser compatibility (IE11+)
- Clean, dark-themed UI
- Single HTML file - no dependencies!

## Usage

1. Open `salary-counter.html` in any browser
2. The counter automatically starts tracking during work hours
3. Shows:
   - Current time
   - Pre-work status (gray):

   <p align="center">
     <img alt="before-work" src="https://github.com/user-attachments/assets/ef686d0b-3701-4855-8725-922540adf392" />
   </p>

   - Today's earnings (green during work):

   <p align="center">
     <img alt="during-work" src="https://github.com/user-attachments/assets/7a7bc68c-9499-437f-9adc-ba1ac9f05273" />
   </p>

   - Lunch break status (orange with countdown):

   <p align="center">
     <img alt="lunch-break" src="https://github.com/user-attachments/assets/32472f6d-3990-4813-aec3-b04c4c9bace0" />
   </p>

   - End of day total (blue):

   <p align="center">
     <img alt="after-work" src="https://github.com/user-attachments/assets/f77b977b-51b5-4f36-9a23-ca99eac7e2d9" />
   </p>

## Configuration

Edit these variables in the script section:

```javascript
/* === SETTINGS === */
// 1. Working hours
var WORK_START_HOUR = 8; // Work start hour
var WORK_START_MINUTE = 15; // Work start minute
var WORK_END_HOUR = 17; // Work end hour
var WORK_END_MINUTE = 15; // Work end minute

// 2. Lunch break
var HAS_LUNCH_BREAK = true; // true - with lunch, false - without lunch
var IS_LUNCH_PAID = false; // true - lunch is paid, false - unpaid (ignored if no lunch)
var LUNCH_START_HOUR = 12; // Lunch start hour
var LUNCH_START_MINUTE = 15; // Lunch start minute
var LUNCH_END_HOUR = 13; // Lunch end hour
var LUNCH_END_MINUTE = 15; // Lunch end minute

// 3. Pay
var WEEKDAY_SALARY_PER_MINUTE = 2.7; // Weekday rate (per minute)
var WEEKEND_SALARY_PER_MINUTE = 3.3; // Weekend rate (per minute)
/* === SETTINGS === */
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
- CSS with IE11 compatibility
- Real-time updates using setTimeout with millisecond precision

## Contributing

- Feel free to fork and customize for your own work schedule!

## License

- MIT License - feel free to use this for any purpose.
