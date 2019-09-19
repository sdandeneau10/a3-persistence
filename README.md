## Football Stats Tracker

http://a3-spdandeneau.glitch.me

My project is an extension of a2 but redesigned in a more user friendly manner. Users have the ability to enter information for a play and this information is then written to lowdb. Multiple plays can be entered and displayed in real-time on the client.

- The goal of this application was to provide the end user with a clear and simple way to log data collected from a football game.
- One of the challenges I faced was navigating the server-client communication.
- I used lowdb to track all logged plays because it was easiest to implement.
- CSS Framework: Bootstrap
  - I did not make any changes to the css template.
- Express Middleware: body-parser, errorhandler, serve-favicon, serve-static.
  - Passport: I struggled to use passport and was not able to successfully implement it.

## Technical Achievements
- **Tech Achievement 1**: No limit to the number of entries. lowdb holds everything and the page has no limit of display.
- **Tech Achievement 2**: Form inputs are specified to ensure proper data entry by the user.

### Design/Evaluation Achievements
- **Design Achievement 1**: Added alternate text for images to ensure readability on text-only browsers.
- **Design Achievement 2**: Tested my application with 5 people to ensure ease/clarity of use and every user was able to utilize the app without guidance.
