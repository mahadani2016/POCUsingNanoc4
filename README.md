
Before installing nanoc4, ensure you have a supported version of Ruby. Nanoc supports Ruby 2.1 and up, and JRuby 9000 and up:

% ruby --version
ruby 2.3.0p0 (2015-12-25 revision 53290) [x86_64-darwin15]
%

You can install Nanoc 4 using RubyGems:

% gem install nanoc

To generate the full HTML file, compile the site by running nanoc:
Go to the project folder and execute
$ nanoc

start a web server by running nanoc view:

$ nanoc view
