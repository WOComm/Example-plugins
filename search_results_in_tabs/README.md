This plugin is designed to demonstrate to you how you can include script content in other templates.
More information here https://www.jomres.net/manual/developers-guide-2/52-customising-jomres/366-including-script-content-in-another-template
This functionality allows you to include output from Jomres scripts in other Jomres templates without needing to modify any code and is a useful tool when customising your site.


In this example we will show you how you can create tabs to show search results of different property types. At it's core it uses the "search" shortcode functionality that you can find in Admin > Jomres > Tools > Shortcodes

A normal search by property type shortcode would look like 

{jomres search &ptype=1}

To see it displayed using the technique I linked to above, you would use 

{jomres_script search &ptype=1}

in the template file. See below for examples.

To display these tabs in a content item you would do 

{jomres search_results_in_tabs} (Joomla) or [jomres search_results_in_tabs] (Wordpress) in the content item.

