# test-your-own-ruby-gem-locally

Sometimes you need to do the upgrade to the gem and do test in local. Here is the easiest way to apply the ```latest gem version``` to your ```irb```. <br />

* cd to the ```root dir``` of your gem project
* rake build
* gem build GEMNAME.gemspec( like ```gem build to_file.gemspec``` )
* sudo gem install GEMNAME -l ( like ```sudo gem install to_file -l``` )
* run irb and do your test 🕶️
