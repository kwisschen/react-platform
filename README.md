# Business Platform
#### Video Demo:  <https://youtu.be/dU2SZpLG0MA>
#### Description:
Web application written in JavaScript using React with the following libraries:
- Material UI
- React Pro Sidebar
- Nivo Charts
- Formik
- Yup
- FullCalendar

Homepage:
This project has a Homepage displaying a dashboard which provides a user with a clear and comprehensive view of business data using data grids, some of which are imported from the sidebar pages.

Sidebar pages:
At the very top is where the User Info resides, including a profile picture and the name and title of the current user.

Under the People Management heading is a Personal Profile page where the user can login through Formik and Yup validation. The Team Management and Connections Management pages allow the user to manage team members (including their access levels) and their connections (including pending communications) through Material UI styling and functions.

Under the Flow Control heading is first an Invoice page where the user can view incomes and expenditures from their employees or other organizations. Income amounts are marked in green, while expenditures are marked in red. The Events page will allow the user to schedule events by virtue of FullCalendar(as soon as debugging thereof is successful). The SOP page will allow the user to post standard workflow procedures for different business areas.

Under the Data Charts heading is first a Bar Chart page illustrating yearly cases from different engineering fields. The Pie Chart page displays the proportions of cases that are delayed by different degrees, as well as those that were delivered on time. The Quality Tracking page tracks the quality of cases that are written in three different languages, being English, Japanese, and Other, respectively. Finally, the Country Distribution page allows the user to keep track of case density for different countries, which may help them determine where to focus more effort. These charts are all implemented using Nivo Charts.

Looking to use this app at my company to facilitate business management.

In my **components** folder I imported and used code from their respective libraries.

In my **data** folder I used sets of mock data, consolidating all of the data for the team members, the business contacts, the invoices, the bar chart, the donut chart, and the line chart, in one file, and mock geographical features into another.

In my **scenes** folder I divided the web application into different scenes (i.e., pages) to be shown to the user, and wrote an index.jsx file for each scene, with the topbar and sidebar that are always present being included in the global folder. 

In my **App.js** file I imported all the files from the ***scenes*** directory, as well as respective routes for appropriate pathing.

In my **theme.js** file I implemented **two themes: a _light mode_ and a _dark mode_**, with the default being set to dark.

The React element that I used most was probably the *Box element*, which I found to be very convenient as it allows you to add CSS properties on the fly.

The most challenging aspect was probably familiarizing myself with all the different libraries that I used for this project. There seems to always be a quirk there and a discrepancy there that you have to spend time sorting out. Spent the most time trying to get fullcalendar to render properly with the free version, and will continue working on that issue.



