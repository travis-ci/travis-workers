source :rubygems

ruby '1.9.3', engine: 'jruby', engine_version: '1.7.0'

gem 'travis-core',        github: 'travis-ci/travis-core', branch: 'sf-redis-workers'
gem 'travis-support',     github: 'travis-ci/travis-support'
gem 'travis-sidekiqs',    github: 'travis-ci/travis-sidekiqs', require: nil

# gem 'newrelic_rpm',       '~> 3.4.2'

# can't be removed yet, even though we're on jruby 1.6.7 everywhere
# this is due to Invalid gemspec errors
gem 'rollout',            github: 'jamesgolick/rollout', ref: 'v1.1.0'
gem 'sidekiq'
gem 'hot_bunnies',        '~> 1.4.0.pre4'
gem 'hubble',             github: 'roidrage/hubble'

