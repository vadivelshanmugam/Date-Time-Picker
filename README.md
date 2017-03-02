# Date and Time Picker
This is plugin about date and time picker, it has lots of custome options, like language selection, color theme, meridiem, date format.

### Language Selection
This option based on R.js and its supporting language files, ex: You want English as language, You need to add month and week translated string in one Javascript file, in the form of key and value pairs.

```javascript
$(selector).dateTimePicker({lang: 'en-US'});
```

### Language example file
```javascript
R.registerLocale("en-US", {
  January: "January",
  February: "February",
  March: "March",
  April: "April",
  May: "May",
  June: "June",
  July: "July",
  August: "August",
  September: "September",
  October: "October",
  November: "November",
  December: "December",
  Monday: "Monday",
  Tuesday: "Tuesday",
  Wednesday: "Wednesday",
  Thursday: "Thursday",
  Friday: "Friday",
  Saturday: "Saturday",
  Sunday: "Sunday",
});
```

### Color Theme
This option rendered all icons color, selection cell, today cell and mouse over colors based on user given color. The Theme color should darker and should not be Black and White colors. 

```javascript
$(selector).dateTimePicker({baseColor: '#ff0000'});
```

### Meridiem
This option used for showing time in 12hr format or 24hr format.

```javascript
$(selector).dateTimePicker({meridiem: true});
```

### Date Format
This plugin supports DMY, MDY, YMD date formats.

```javascript
$(selector).dateTimePicker({dateFormat: 'DDMMYYYY'});
```

## Library
  >Javascript
  1. jQuery
  2. R.js
  
  >Icons
  1. Font Awesome  
