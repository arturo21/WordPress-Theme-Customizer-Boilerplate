WordPress Theme Customizer Boilerplate
=================================================

Theme Customizer Boiler plate you can use in your themes. For detailed explanation, check http://www.wpexplorer.com/theme-customizer-boilerplate/

Copy entire /customizer directory into your theme's directory and include customizer.php from your theme's functions.php:

require( get_stylesheet_directory() . '/customizer-boilerplate/customizer.php' );

Then you can change contents of $options array in options.php file and use whatever fields you need.

@slobodanmanic