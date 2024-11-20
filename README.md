# Dashboard
Admin Dashboard
1. Overview
The Admin Dashboard Frontend is a lightweight, responsive HTML and CSS-based template for managing administrative tasks. It is designed to display critical metrics like sales, customer data, recent orders, and notifications in an organized and visually appealing format.

2. Features
Responsive Sidebar Navigation: Allows quick access to dashboard sections like analytics, settings, and user management.
Insights Cards: Displays metrics for sales, expenses, and income with progress indicators.
Recent Orders: A table showcasing product details, payment status, and order progress.
Sales Analytics: Key metrics such as online orders, bulk orders, and B2B orders with trends.
Theme Toggle: Switch between light and dark modes for better accessibility.
Real-Time Updates Section: Displays user activities and recent updates dynamically.
Profile Management: Includes admin profile info with a profile photo.



4. Setup and Usage
Clone or Download:
Download or clone the project repository to your local machine:

bash
Copy code
git clone https://(https://github.com/Ayushshah07/Dashboard).git
cd admin-dashboard
Open in Browser:
Double-click the index.html file or open it in a browser of your choice.

Custom Fonts:
The dashboard uses Google Fonts (Material Symbols Sharp). Ensure internet access is available for the font to load correctly.

JavaScript Integration:
The interactivity of the sidebar and theme toggle is powered by the script.js file. Ensure this file is linked for full functionality.

5. Customization
Update Branding
Edit the logo text in the <div class="logo"> section within index.html.
Replace profile photos in the /images folder.
Change Colors or Themes
Modify colors in the style.css file for customization.
Update the dark_mode and light_mode classes in the theme-toggler JavaScript logic for theme customization.
Add or Edit Sidebar Items
Update the <a> tags in the sidebar section of index.html to add or remove navigation links.
Dynamic Data
Replace placeholder values in sections like "Recent Orders" or "Sales Analytics" with data from an API or backend service.
6. Browser Compatibility
The dashboard is compatible with modern browsers:

Chrome: Latest version
Firefox: Latest version
Edge: Latest version
Safari: Limited testing
7. Contributing
We welcome contributions to improve this dashboard. To contribute:

Fork the repository.
Create a feature branch:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Description of changes"
Push to the branch:
bash
Copy code
git push origin feature-name
Open a pull request for review.
