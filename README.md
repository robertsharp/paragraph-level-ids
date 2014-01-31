paragraph-level-ids
===================

http://www.robertsharp.co.uk/paragraph-level-ids

I’ve created a simple plugin for WordPress sites.  The Paragraph Level IDs plugin adds an ‘id’ attribute to each paragraph tag in a blog post, giving the author and readers additional functionality.

So for example, < p > becomes < p id="para1234-5" >.

The plugin also offers the option to include an anchor tag before each paragraph, like this: < a name="para1234-5" >< /a >.

Both these additions allow anyone to link directly to that paragraph in the post. This is especially useful for long tracts of text, academic writing, and legal documents.

I have written an accompanying blog post, explaining what inspired me to write the plugin.
http://www.robertsharp.co.uk/2013/10/09/why-i-wrote-my-wordpress-plugin/

Installation works just like most other WordPress plugins.

Download the plug-in from right here or better yet, the WordPress plugin repository.
http://wordpress.org/plugins/paragraph-level-ids/
Unzip the files and upload rs-para-level-ids.php to the wp-content/plugins directory.
Visit the plugins section of your WordPress Dashboard.
Activate the plugin
Nothing will be changed in your website’s source code until you visit the ‘Paragraph IDs’ options under the WordPress ‘Settings’ menu.

Please review this plugin on the WordPress plugins directory, and add your vote to the ‘compatability’ section to let others know that it works.
http://wordpress.org/support/view/plugin-reviews/paragraph-level-ids

Change Log

0.2 (current version) – Added a settings menu, with the ability to add an ‘id’ to the <p> tags, an anchor, or both; and customisation options. 02/10/2013

0.1 – A very simple proof-of-concept with no settings. 29/09/2013

Road Map

In the future I hope to make the following improvements.

A feature that would place a discreet but clickable (or right-clickable) link at the end of each paragraph, to allow easy linking, like this. #
Streamline the code so it is at its most efficient and smallest file size.
Further customisation options for the id and anchors.
A test to prevent anchors and ids from having the same value.
A degree of backwards compatibility
Ensure the layout of the settings page is as pretty and efficient as possible.
Language localisation for the settings page.

I would welcome any advice, offers of support, bug-testing, forking the project and troubleshooting to help make these extra features possible.
