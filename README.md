# Awesome Rails (Ruby on Rails) [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of frameworks, gems, tools, libraries, templates, engines, and learning resources for building modern web applications with **Ruby on Rails**.

## Contents

- [Official Resources](#official-resources)
- [Starter Kits & Templates](#starter-kits--templates)
- [Authentication & Authorization](#authentication--authorization)
- [APIs, GraphQL & Serialization](#apis-graphql--serialization)
- [Background Jobs & Queues](#background-jobs--queues)
- [Front-End & Full-Stack Enhancements](#front-end--full-stack-enhancements)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [Database, ORM & Caching](#database-orm--caching)
- [Security](#security)
- [Deployment & DevOps](#deployment--devops)
- [Monitoring, Debugging & Error Tracking](#monitoring-debugging--error-tracking)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Ruby on Rails Guides](https://guides.rubyonrails.org/) – Official Rails documentation covering concepts, patterns, and best practices.
- [Ruby on Rails API Docs](https://api.rubyonrails.org/) – Reference documentation for Rails modules, classes, and methods.
- [Rails Repository](https://github.com/rails/rails) – Source code of the Rails framework.
- [Ruby Language](https://www.ruby-lang.org/en/) – Official website of the Ruby programming language.
- [Hotwire](https://hotwired.dev/) – Official Rails-native framework for building dynamic interfaces without JavaScript-heavy SPAs.

## Starter Kits & Templates

- [Jumpstart Rails](https://jumpstartrails.com/) – Full-featured SaaS starter with billing, teams, dashboard, and admin.
- [Bullet Train](https://bullettrain.co/) – Rails SaaS template featuring multi-tenancy, billing, and workflows.
- [Rails Templates by Suspenders](https://github.com/thoughtbot/suspenders) – Thoughtbot’s Rails project template with development best practices included.
- [Rails Composer](https://github.com/RailsApps/rails-composer) – Customizable Rails application generator for quick scaffolding.
- [Jumpstart Pro](https://jumpstartrails.com/pro) – Commercial template for Rails SaaS products with built-in authentication and billing.

## Authentication & Authorization

- [Devise](https://github.com/heartcombo/devise) – Flexible authentication solution for Rails applications.
- [OmniAuth](https://github.com/omniauth/omniauth) – Multi-provider authentication with OAuth integrations.
- [Pundit](https://github.com/varvet/pundit) – Lightweight authorization using plain Ruby policy classes.
- [CanCanCan](https://github.com/CanCanCommunity/cancancan) – Rules-based authorization with expressive DSL.
- [Rodauth Rails](https://github.com/jeremyevans/rodauth-rails) – Full-featured authentication framework with a secure design.

## APIs, GraphQL & Serialization

- [Jbuilder](https://github.com/rails/jbuilder) – JSON templating for building structured API responses.
- [ActiveModel Serializers](https://github.com/rails-api/active_model_serializers) – Serializer layer for Rails APIs.
- [Blueprinter](https://github.com/procore/blueprinter) – Fast, flexible object serialization for APIs.
- [Grape](https://github.com/ruby-grape/grape) – REST-like microframework for building Rails-integrated APIs.
- [GraphQL Ruby](https://github.com/rmosolgo/graphql-ruby) – GraphQL implementation for Ruby with schema tools and subscriptions.

## Background Jobs & Queues

- [Sidekiq](https://github.com/sidekiq/sidekiq) – High-performance background job system using Redis.
- [Resque](https://github.com/resque/resque) – Redis-backed job processing library for slow or scheduled jobs.
- [Delayed Job](https://github.com/collectiveidea/delayed_job) – Simple background job processing system using ActiveRecord.
- [GoodJob](https://github.com/bensheldon/good_job) – Postgres-backed job processing for Rails with concurrency controls.
- [Que](https://github.com/que-rb/que) – Efficient Postgres-based job runner for multi-processing workloads.

## Front-End & Full-Stack Enhancements

- [Hotwire (Turbo + Stimulus)](https://hotwired.dev/) – Rails-native framework for dynamic, real-time frontends with minimal JS.
- [Stimulus](https://stimulus.hotwired.dev/) – Lightweight JS framework for enhancing HTML interactions.
- [Turbo](https://turbo.hotwired.dev/) – Speeds up Rails apps with frame-based rendering and WebSocket updates.
- [ViewComponent](https://github.com/ViewComponent/view_component) – Framework for building reusable, testable UI components in Rails.
- [TailwindCSS Rails](https://github.com/rails/tailwindcss-rails) – Native integration for TailwindCSS in Rails applications.

## Testing & Quality Assurance

- [RSpec Rails](https://github.com/rspec/rspec-rails) – Behavior-driven testing library for Rails applications.
- [Minitest](https://github.com/seattlerb/minitest) – Fast, lightweight test framework included in Ruby.
- [FactoryBot](https://github.com/thoughtbot/factory_bot) – Test data factories for easier model creation.
- [Capybara](https://github.com/teamcapybara/capybara) – Integration testing framework for simulating real user interactions.
- [Rubocop](https://github.com/rubocop/rubocop) – Code style and static analysis tool for Ruby.

## Database, ORM & Caching

- [ActiveRecord](https://guides.rubyonrails.org/active_record_basics.html) – Rails’ ORM for interacting with relational databases.
- [PgSearch](https://github.com/Casecommons/pg_search) – Full-text search for PostgreSQL-backed Rails apps.
- [Redis](https://redis.io/) – In-memory store widely used for caching, sessions, and background jobs.
- [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) – Tagging DSL for Rails models.
- [Scenic](https://github.com/scenic-views/scenic) – Versioned SQL views integrated with Rails migrations.

## Security

- [Brakeman](https://github.com/presidentbeef/brakeman) – Security scanner for Rails applications.
- [Rack Attack](https://github.com/rack/rack-attack) – Middleware for rate limiting and protection against brute-force attacks.
- [Secure Headers](https://github.com/twitter/secureheaders) – Adds security headers to protect against browser-based attacks.
- [Devise Security Extension](https://github.com/devise-security/devise-security) – Enhancements for password expiration, lockable accounts, and security policies.

## Deployment & DevOps

- [Capistrano](https://github.com/capistrano/capistrano) – Deployment automation tool for Rails applications.
- [Kamali](https://kamal.hotwired.dev/) – Deploy Rails apps using Docker and lightweight orchestration.
- [Heroku](https://www.heroku.com/) – Platform-as-a-service for simple Rails app deployment.
- [Render](https://render.com/) – Modern hosting platform for Rails apps with background jobs and databases.
- [DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform/) – Full-stack hosting for Rails apps with autoscaling.
- [Fly.io](https://fly.io/) – Global containers hosting ideal for Rails applications with Action Cable or Turbo Streams.

## Monitoring, Debugging & Error Tracking

- [Sentry](https://sentry.io/) – Real-time error tracking and performance analytics for Rails applications.
- [Skylight](https://www.skylight.io/) – Performance monitoring designed specifically for Rails.
- [New Relic](https://newrelic.com/) – Observability platform for application and infrastructure metrics.
- [Bugsnag](https://www.bugsnag.com/) – Error monitoring and stability analytics for Rails apps.
- [RailsPanel](https://github.com/dejan/rails_panel) – Chrome extension offering Rails-specific request insights.

## Learning Resources

### Tutorials
- [GoRails](https://gorails.com/) – Screencasts covering Rails, Turbo, Devise, and full-stack development.
- [RailsCasts (Archive)](http://railscasts.com/) – Classic Rails tutorials with timeless best practices.
- [Build With Hotwire](https://www.buildwithhotwire.com/) – Tutorials on Hotwire, Turbo, and modern Rails UX patterns.

### Guides
- [Rails Guides](https://guides.rubyonrails.org/) – Comprehensive official documentation for Rails features.
- [Everyday Rails Testing](https://everydayrails.com/) – Practical testing strategies with RSpec.
- [The Ruby on Rails Tutorial](https://www.railstutorial.org/book) – Full introduction to Rails app development.

### Courses
- *The Complete Ruby on Rails Developer Course* – Comprehensive Udemy course on Rails and Ruby fundamentals.
- *Full-Stack Rails Developer Bootcamp* – Career-track training for Rails development.
- *Hotwire + Rails Mastery* – Course focused on modern Rails frontends.

## Related Awesome Lists

- [Awesome Ruby](https://github.com/awesomelistsio/awesome-ruby)
- [Awesome APIs](https://github.com/awesomelistsio/awesome-apis)
- [Awesome SaaS](https://github.com/awesomelistsio/awesome-saas)
- [Awesome Web Development](https://github.com/awesomelistsio/awesome-web-development)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
