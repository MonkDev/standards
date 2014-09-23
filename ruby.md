Ruby
====

1.  We adhere to the [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).
    [RuboCop](https://github.com/bbatsov/rubocop) should be used to detect
    violations of the standard.
2.  Dependency management should be done with [Bundler](http://bundler.io).
3.  Code documentation should be done with [YARD](http://yardoc.org).
4.  Testing should be done with [RSpec](https://relishapp.com/rspec).
5.  Task running should be done with [Rake](https://github.com/jimweirich/rake).
6.  [Code quality and analysis tools](https://github.com/metricfu/metric_fu/wiki/Code-Tools)
    should be used if possible.
7.  The Ruby version should be specified in [a `.ruby-version` file](http://rvm.io/workflow/projects#project-file-ruby-version)
    or [Bundler's `Gemfile`](http://bundler.io/v1.7/gemfile_ruby.html).


Rails
-----

1.  We adhere to the [Rails Style Guide](https://github.com/bbatsov/rails-style-guide).
2.  Configuration should be done with [Figaro](https://github.com/laserlemon/figaro).
3.  In addition to the code quality and analysis tools mentioned previously,
    [rails_best_practices](https://github.com/railsbp/rails_best_practices)
    should be used to detect violations of Rails best practices.

Bundler
-------

1.  [Be purposeful in specifying version requirements](http://robots.thoughtbot.com/a-healthy-bundle).
2.  An exact version should be specified for frameworks like Rails and more
    fragile gems.
3.  A pessimistic version should be specified for gems that follow semantic
    versioning.
4.  No version should be specified for gems that are safe to update often or
    have no impact on the code in production, such as development dependencies.
