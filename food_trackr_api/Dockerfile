FROM rails:4.2.6

# Create and migrate DB
RUN bundle exec rake db:create
RUN bundle exec rake db:migrate

# Start rails server
CMD ["bundle", "exec", "rails", "server", "-b", "0.0.0.0"]
