# Wine-Festival-Schedule

Welcome to the Annual Aguillar Family Wine Festival! This GitHub project showcases the HTML code for building a web page that displays the schedule of events for the wine festival. The page utilizes a clean and organized table layout to provide attendees with a quick and easy-to-read overview of the day's activities.

**Features**

Responsive Design: The web page is designed to be responsive, ensuring a seamless viewing experience across various devices.
Custom Styling: The schedule is styled using an external CSS file, "WineFestivalSchedule.css," for easy customization and maintenance.
Google Fonts Integration: The page incorporates the "Oswald" font from Google Fonts to enhance the visual appeal of the festival schedule.

**Schedule Details**

The festival schedule is presented in a structured table format, consisting of time slots and corresponding events. Here's a snapshot of the schedule:

Time	Event
12:00 PM	Welcome Reception
01:00 PM	Storytelling & Tasting
02:00 PM	Wine Luncheon
03:00 PM	Aguillar Family Wines
04:00 PM	Wine & Cheese Tasting

<img width="523" alt="Screenshot 2024-02-03 at 1 44 08 AM" src="https://github.com/Christian-Hernandez-Box/Wine-Festival-Schedule/assets/118034327/ea037402-945d-48d7-9535-4a36b1dfb090">

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Aguillar Family Wine Festival</title>
    <link rel="stylesheet" type="text/css" href="WineFestivalSchedule.css" />
    <link
      href="https://fonts.googleapis.com/css?family=Oswald"
      rel="stylesheet"
    />
  </head>

  <body>
    <header>
      <h1>Annual Aguillar Family Wine Festival</h1>
    </header>

    <div class="container">
      <table>
        <thead>
          <tr>
            <th colspan="2">
              <h1>Wine Festival Schedule</h1>
            </th>
          </tr>
          <tr>
            <th>
              <h2>Time</h2>
            </th>
            <th>
              <h2>Event</h2>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="left">
              <h3>12:00 PM</h3>
            </td>
            <td>
              <h3>Welcome Reception</h3>
            </td>
          </tr>
          <tr>
            <td class="left">
              <h3>01:00 PM</h3>
            </td>
            <td>
              <h3>Storytelling & Tasting</h3>
            </td>
          </tr>
          <tr>
            <td class="left">
              <h3>02:00 PM</h3>
            </td>
            <td>
              <h3>Wine Luncheon</h3>
            </td>
          </tr>
          <tr>
            <td class="left">
              <h3>03:00 PM</h3>
            </td>
            <td>
              <h3>Aguillar Family Wines</h3>
            </td>
          </tr>
          <tr>
            <td class="left">
              <h3>04:00 PM</h3>
            </td>
            <td>
              <h3>Wine & Cheese Tasting</h3>
            </td>
          </tr>
        </tbody>
      </table>
    </div>

    <footer>
      <h3>Contact</h3>
      <h3>Location</h3>
      <h3>Privacy Policy</h3>
    </footer>
  </body>
</html>

```
