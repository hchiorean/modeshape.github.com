source 'https://rubygems.org'

if RUBY_PLATFORM=~ /mswin|mingw|cygwin/
  gem 'therubyracer', '0.11.0beta1' # Call JavaScript code and manipulate JavaScript objects from Ruby and vice versa  gem "ruby-debug"
  gem 'win32-open3-19'  
else
  gem 'therubyracer', '~> 0.11.4' # Call JavaScript code and manipulate JavaScript objects from Ruby
end

#gem 'awestruct', '~> 0.5.2.1'	# Framework for creating static HTML sites
gem 'awestruct', :github => 'mojavelinux/awestruct', :branch => 'integration'
gem 'uglifier', '~> 2.0.1'	# Ruby wrapper for UglifyJS JavaScript compressor
gem 'cssminify', '~> 1.0.2'	# CSS compression using YUI compressor
gem 'less', '~> 2.4.0'   # Invoke the Less CSS compiler from Ruby
gem 'rb-fsevent', '~> 0.9.3'	# FSEvents API with Signals catching (without RubyCocoa)
gem 'kramdown', '~> 1.0.1' # Kramdown works on all platforms, rdiscount only on mri
gem 'therubyrhino', '~> 1.73', :platforms => :jruby # JavaScript on JRuby
gem 'htmlcompressor', '~> 0.0.3' # Adds in HTML minification, helps remove the warning on awestruct startup
gem 'json', '~> 1.7.7'
gem 'asciidoctor', '~> 0.1.4'
gem 'git', '~> 1.2.6'
gem 'trollop', '~> 2.0'
gem 'coderay', '~> 1.1.0'