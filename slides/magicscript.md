
## Little magic!
<pre><code class="bash">
#!/bin/bash
</code></pre>

1. Git repositories on bitbucket
2. "Alpha" Installation profile includes:
 * Drush makefiles for development and production environment<br>
 * Simple ToDo List feature module
3. Custom Alpha Devel module
 * included conditionally in development build only
 * enables & configures Devel and Mail Reroute modules
4. Build script written in bash     
 * environment aware         
 * Takes 1 option and 1 argument
		* -e | --environment <dev|prod>
		* site lable – used for site folder name and database name
