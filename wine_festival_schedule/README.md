# Wine Festival Schedule

## Project Overview
The Aguillar Family is hosting their annual wine festival and they have requested a web page to showcase the event schedule. This project demonstrates the use of HTML to create and structure a table for attendees to view the event times and activities.

## Table of Contents
- [Features](#features)
- [Preview](#preview)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Structure](#structure)
- [Tasks](#tasks)
- [License](#license)

## Features
- A fully structured HTML table to display the event schedule.
- Clear headings to label the table content.
- Organized rows and columns for times and events.
- User-friendly and visually appealing layout.

## Preview
To view the final version of the web page, click [here](#).

## Technologies Used
- HTML5
- CSS (Optional for styling)

## How to Use
1. Clone this repository to your local machine.
2. Open the `index.html` file in your preferred browser.
3. View the event schedule in a neatly organized table.

## Structure
The project is structured as follows:
```plaintext
.
├── index.html
└── README.md
```

### HTML Structure
- `<div class="container">`: Main container for the content.
- `<table>`: Table element to display the schedule.
  - `<thead>`: Contains the table headings.
    - `<tr>`: Defines table rows.
    - `<th>`: Defines table headers.
  - `<tbody>`: Contains the main schedule data.
    - `<tr>`: Defines rows for event times and details.
    - `<td>`: Contains individual cell data.

## Tasks
This project involves the following tasks:

1. **Create a Table**:
   - Add a `<table>` inside the `<div class="container">`.

2. **Add Table Headings**:
   - Use `<thead>` to add two rows:
     - First row: `<h1>` with "Wine Festival Schedule".
     - Second row: `<h2>` for "Time" and "Event".

3. **Adjust Column Span**:
   - Add `colspan="2"` to make "Wine Festival Schedule" span across two columns.

4. **Add Table Body**:
   - Use `<tbody>` to section off the table data.
   - Create five rows for event times and details.

5. **Add Event Times and Descriptions**:
   - In the first column, add event times using `<td class="left">`.
   - In the second column, add event names using `<td>`.

### Schedule Details
| Time       | Event                   |
|------------|-------------------------|
| 12:00 PM   | Welcome Reception       |
| 01:00 PM   | Storytelling & Tasting  |
| 02:00 PM   | Wine Luncheon           |
| 03:00 PM   | Aguillar Family Wines   |
| 04:00 PM   | Wine & Cheese Tasting   |

## License
This project is licensed under the [MIT License](LICENSE).

Cheers to creating an amazing Wine Festival Schedule!
