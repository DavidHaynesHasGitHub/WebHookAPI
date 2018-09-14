
#------------------------------------------------------------------------
# Gemfile
#------------------------------------------------------------------------
source 'http://rubygems.org'

gem 'rake'
gem 'middleman', '>= 4.0.0'
gem 'middleman-livereload'
gem 'middleman-search_engine_sitemap'


#------------------------------------------------------------------------
# Deployment - requires additional configuration.  See links below

gem 'middleman-aws'         # https://github.com/alienfast/middleman-aws


# Even though already required by the middleman-aws gem, it appears middleman does not
#   pick up transitive dependency extensions early enough  to avoid the
#   "== Unknown Extension:" error.  Add these to your main project
#   (I wish this was unnecessary but don't know how to work around it)

# https://github.com/fredjean/middleman-s3_sync
gem 'middleman-s3_sync', '>=4.0.0'

# https://github.com/andrusha/middleman-cloudfront
gem 'middleman-cloudfront',
  #'>=4.0.0' waiting for release of PR https://github.com/andrusha/middleman-cloudfront/pull/23
  github: 'rosskevin/middleman-cloudfront', branch: 'middleman-4'

#------------------------------------------------------------------------
# Other dependencies below here.
gem 'middleman-syntax', '~> 3.0.0'
gem 'middleman-autoprefixer', '~> 2.7.0'
gem 'middleman-sprockets', '~> 4.1.0'
gem 'rouge', '~> 2.0.5'
gem 'redcarpet', '~> 3.4.0'
gem 'nokogiri', '~> 1.8.2'



