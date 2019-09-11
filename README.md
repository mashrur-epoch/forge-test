# forge-test
Forge WordPress Developer Test
Requirements
node v8.15.0
npm v6.4.1
WordPress Latest
Overview
This theme utilises existing css markup from a batch of html templates.

Try to utilise WP CLI

The base files required for a WordPress theme have been setup and all the styles and markup required already exist.

The repository contains a database containing the data required.

WordPress login:-

u: tom.riddle

p: passwordisweak

Tasks
For the purpose of these tasks please disable guttenberg by installing the classic editor plugin: https://en-gb.wordpress.org/plugins/classic-editor/

Please clone a version of this repository and complete your solution within your own repository, once completed please get in touch with a link to your repo.

Set the site up locally for development and import the database.
Using the gulp file compile the existing css and js from the /src/ directory to the /dist/ directory.
Using the gulp file compile/compress the images from the /src/ directory to the /dist/ directory.
Using a WordPress action include the compiled styles and js in the header and footer.
Using a WordPress action remove the WordPress version of jQuery and replace with the version included here /src/js/modules/jquery.js
Create a WordPress template to display the content from a blog post using the html in post.html.
Create an archive to display the list of blog posts based upon posts.html, add a category filter to the top of the blog posts archive for the default categories. Only show non-empty categories, the markup for the filters can be text links, extra points for the use of ajax.
Create a WordPress menu and replace the static version in the header.
Add a global Advanced Custom Fields options page to update the phone numbers, email address, street address and social media links in the footer
Create a plugin file and utilising mu-plugins to setup a custom post type of "Team" and a custom taxonomy of "Department".
Using Advanced Custom Fields flexible content create three blocks of your choice based upon the markup in front-page.php. These blocks should be re-usable for any other pages created.
