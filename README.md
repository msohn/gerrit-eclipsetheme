# Gerrit style plugin for the Eclipse Foundation

This plugin uses CSS to style the header of the Gerrit UI for the Gerrit
server of the Eclipse Foundation.

This plugin is based on the
[polyCssStyle example plugin](https://gerrit.googlesource.com/plugins/examples/+/refs/heads/stable-3.1/example-polyCssStyle/).

## How to install

Copy the file `gerrit-eclipsestyle.html` into the Gerrit site's `plugins`
directory. There is no need to restart, once the file was copied, Gerrit
will detect the new PolyGerrit plugin after a few moments and will use it.
