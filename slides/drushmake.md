
## Drush Make/make file

<p>Drush make is an extension to drush that can create a ready-to-use drupal site,
pulling sources from various locations.</p>
<pre><code class="bash">
$ drush generate-makefile example.make
$ drush make [-options] [filename.make] [build path]
 </code></pre>
Among drush make's capabilities are:<small>
 * Downloading Drupal core, as well as contrib modules from drupal.org.
 * Checking code out from SVN, git, and bzr repositories.
 * Getting plain .tar.gz and .zip files (particularly useful for libraries that can not be distributed directly with drupal core or modules).
 * Fetching and applying patches.
 * Fetching modules, themes, and installation profiles, but also external libraries.
 </small>

<img src="/img/logo.png">