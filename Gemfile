source 'https://rubygems.org'

group :app do
  gem 'sqlite3'
  gem 'pg'
  gem 'sequel'
  gem 'syntax'
  gem 'json'
  gem 'version_sorter'
  gem 'net-http-persistent', '~> 2.0'
  gem 'activesupport'
  gem 'rake', require: false
end

group :instrumentation do
  gem 'skylight', require: false
  gem 'derailed_benchmarks', require: false
  gem 'rack-mini-profiler', require: false
  gem 'memory_profiler', require: false
  gem 'flamegraph', require: false
  gem 'stackprof', require: false
  gem 'rack-test', require: false
end

group :yard do
  gem 'yard', github: 'lsegal/yard', branch: 'main'
  gem 'yard-rails'
  gem 'yard-kramdown'
  gem 'yard-sd'
end

group :markup do
  gem 'rdoc'
  gem 'maruku'
  gem 'kramdown', '>= 2.3.1'
  gem 'redcarpet', '>= 3.5.1'
  gem 'github-markup'
  gem 'rdiscount'
  gem 'bluecloth'
  gem 'RedCloth'
  gem 'asciidoctor'
end

group :framework do
  gem 'sinatra', '>= 1.3'
  gem 'puma', '>= 4.3.8'
end

group :test do
  gem 'rspec', require: 'spec'
end
