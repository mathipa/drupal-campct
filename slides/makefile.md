
# Inside Make file
<pre><code class="bash">
api = 2
core = 7.x

; MODULES

projects[ctools][version] = 1.9
projects[ctools][subdir] = contrib

projects[jquery_update][version] = 3.0-alpha2
projects[jquery_update][subdir] = contrib

; Themes Download
projects[bootstrap][version] = 3.1-beta3
projects[bootstrap][type] = theme

projects[adminimal_theme][version] = 1.22
projects[adminimal_theme][type] = theme

; Libraries Download
libraries[backbone][download][type] = git
libraries[backbone][download][url] = https://github.com/jashkenas/backbone.git
libraries[backbone][download][tag] = 1.0.0

; Patches
projects[libraries][type] = "module"
projects[libraries][version] = "2.1"
; Patch against Invalid argument supplied for foreach() libraries.module:161 http://drupal.org/node/1938638#comment-7177618
projects[libraries][patch][] = "http://drupal.org/files/0001-Fix-1938638-by-coredumperror-Fix-typo.patch""

projects[link][version] = "1.1"
projects[link][type] = "module"
; Patch against notice on content type editing 'title_value' in 'link_field_update_instance' undefined http://drupal.org/node/1914286#comment-7055150
projects[link][patch][] = “path to your patch”
</code></pre>