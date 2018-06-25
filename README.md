# SETUP

Day 8 exercise uses Slim HTML with Ruby on Rails.

1. In terminal, execute the following commands:
    ```
    > rails new example
    > cd example
    > bin/rails server
    ```
2. Upon executing these commands and navigating to localhost:3000
on your browser (to verify that your 
Ruby on Rails project is correctly set up), press **CTRL + C**
to stop the server.

3. Add `gem 'slim-rails'` to `Gemfile` (appending to end of file is fine)

4. Execute the following commands in the terminal:
    ```
    > bundle install
    > bin/rails generate controller Example index
    > bin/rails server 
    ```

5. You can type your Slim code into your newly-generated 
Slim file located in 'app/views/example', called `index.html.slim`.
Now navigate to `localhost:3000/example/index` to see the 
code rendered in the browser.