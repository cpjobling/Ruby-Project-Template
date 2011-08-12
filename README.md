# Ruby Project template with RSpec, Cucumber and Guard

This is a template that you can use to bootstrap a new ruby project. It
contains hello-world features and specs adapted from the 
[http://pragprog.com/book/achbd/the-rspec-book](RSpec Book).

## Getting started

1. If using RVM, edit the .rvmrc file to suit your project requirements.
2. Install bundler: `gem install bundler`
3. Install guard `gem install guard`
4. Install dependencies: `bundler install`
5. Launch guard: `guard start`

Guard will run rspec and cucumber against some "hello world" specs and
features that will verify that these are tools are correctly
installed. After this runs, you can remove the hello-world spec and
features.

Guard will also continuously watch the Gemfile and will re-run bundler
if it changes. 

After this, you can do as you will!

Good luck!
