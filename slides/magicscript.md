
## Demo!

<small>I’ll be demonstrating the following components and pointing out how they work together to address the 4 areas mentioned in the previous slide:</small>

1. Git repositories on bitbucket
2. Our "Alpha" Installation profile includes:
 * Drush makefiles for development and production instances<br>
 * a Simple ToDo List feature module
3. Our Custom Alpha Devel module:
 * is included conditionally in development build only
 * enables & configures Devel and Mail Reroute modules
4. Our Build script which takes care of:     
 * building development and production instances of this site
 * installing the site without user intervention
 * migrating site content and assets across production build