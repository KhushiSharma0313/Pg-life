# Pg-life

PG Life is a website created using React, PHP to address the challenges students face when searching for suitable accommodation upon joining college or university.

## Features

- Fully functional with frontend and backend
- Fully responsive design, optimized for all devices
- Operational across various platforms and devices

## Tech Stack

- HTML
- CSS
- Bootstrap 5
- JavaScript
- AJAX
- PHP
- MySQL

## Usage

To run the application, follow these steps:

1. Clone this repository.
2. Install dependencies.
3. Start the server.

```bash
git clone <https://github.com/KhushiSharma0313/Pg-life>
cd pg-life
# Install dependencies
# Start the server
```

## Web App Functionalities

### Home Page:
- **Search Bar:** Allows users to enter city names (in any case) to view listed PGs in that city (if available in the database).
- **Main Cities Section:** Circular sections displaying main cities; clicking on them reveals a list of PGs in that city.

### PG List Page:
- **PG List:** Displays all PGs and their main features in the selected city using visually appealing cards.
- **Filter Bar:** Allows sorting of PGs by rent and rating in ascending or descending order.
- **Interest Indicator:** Indicates how many users have marked a PG as interested, displaying its popularity.
- **Interactive Features:** Logged-in users can mark PGs as interested directly from the list, with a heart icon toggle for like/dislike functionality.

### PG Details Page:
- **View Button:** Clicking on "View" button in the property list page displays the entire details of the selected PG.
- **Image Carousel:** Displays images of the selected PG in a carousel format.
- **Detailed Information:** Shows amenities, testimonials, and address of the PG neatly.
- **Interest Indicator:** Indicates how many users have marked the selected PG as interested, providing insight into its popularity.
- **Interactive Features:** Logged-in users can mark PGs as interested from the details page, with a heart icon toggle for like/dislike functionality.

### Dashboard:
- **User-Specific View:** Only visible to logged-in users, showing their account details.
- **Interested Properties:** Displays cards of PGs marked as interested by the logged-in user across any city.
- **Dynamic Updates:** Allows removal of PGs from interested list directly from the dashboard, with the section updating dynamically.

### Navbar:
- **Brand Name:** Displays the brand name of the web app.
- **Login/Signup Options:** Shows "Signup" and "Login" options if not logged in.
- **Dashboard/Logout Options:** Shows "Dashboard" and "Logout" options if logged in, along with the current user's first name displayed using SESSION.
- **Responsive Design:** Features a responsive toggler navbar for ease of use on different devices.

### Breadcrumb:
- **Navigation Aid:** Shows the relative location of the user in the web app.
- **Hyperlinks:** Contains hyperlinks for easy navigation between endpoints.

### Footer:
- **Popular Cities List:** Displays a list containing hyperlinks to popular cities' PG listings.
- **Copyright Information:** Provides copyright information for the web app.

### User Experience:
- **Guest Access:** Allows browsing the entire web app without logging in for user convenience and attraction of new users.
- **Logged-in Features:** Certain features such as dashboard access and marking properties as interested are available only upon logging in.
  
## Exception Handling
- Custom codes and UI ensure that exceptions are handled effectively, providing clear feedback to users in case of faults.

