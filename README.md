DotSpotting
==

Dependencies
--

* Apache (with mod_rewrite enabled)
* MySQL
* PHP 5 (with mycrypt support)

Installation Instructions
--

1. `git clone git@github.com:Citytracking/dotspotting.git`
2. `git submodule init`
3. `git submodule update`
4. In the `secrets` directory, copy `dotspotting.php.example` to `dotspotting.php` and adjust the values to suit your configuration.
5. Ensure that the `www/templates_c` directory can be written to by your web server.
6. Enable mod_rewrite in your local Apache.

Known Knowns
--

Dotspotting has proven to be fussy and problematic installing using the default
OS X Apache + PHP binaries. We're not sure why but are continuing to poke at the
problem. It works fine using tools like MAMP, though.