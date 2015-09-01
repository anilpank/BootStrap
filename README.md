# BootStrap
Bootstrap reference

## Tips

* For convenience choose your primary target device and create layout for that device first after that add classes to make it responsive for other devices.

*  There is no need to customize the layout for extra small devices like mobile phones; since columns on extra small devices are always horizontal and rendered as one column grid layout by default.

* Tip: You can use the Bootstrap list group component for creating sidebar navigation. For example, displaying the list of product or categories on your website.

* Use the classes .navbar-left or .navbar-right instead of .pull-left or .pull-right to align the nav links, forms, buttons or text inside the navbar

* To create navbars that is not fixed on the top or bottom, place it anywhere within a .container, which sets the width of your site and content.

* Remember to add padding (at least 70px) to the top or bottom of the <body> element to avoid the content to go underneath the navbar while implementing fixed top or bottom navbar. Also be sure to add your custom style sheet after the core Bootstrap CSS file, otherwise it may not work

* Place the fixed .navbar content inside the .container or .container-fluid for proper padding and alignment with the rest of the content.