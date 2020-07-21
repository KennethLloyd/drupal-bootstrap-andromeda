# drupal-bootstrap-andromeda

Andromeda website built with Drupal CMS through PHP Composer and styled with Bootstrap 4

## Requirements

1. PHP 7.3 and above
2. Composer
3. MySQL/MariaDB
4. NPM
5. Gulp

## Running the application

1. Clone this repository and get inside the directory
   ```sh
   $ git clone https://github.com/KennethLloyd/drupal-bootstrap-andromeda.git
   ```
2. Install project dependencies with composer

   ```sh
   $ composer install
   ```

3. Create a database and take note of your credentials

4. Configure your Drupal local installation and run the setup at http://localhost:8080

   ```sh
   $ chmod 755 run-local-server.sh
   $ ./run-local-server.sh
   ```

5. Navigate to the appearance tab and select the Andromeda custom theme as the default theme

6. Install Bootstrap 4 custom theme dependencies

   ```sh
   $ cd web/themes/custom/bootstrap_custom
   $ npm install
   ```

7. Build the theme
   ```sh
   $ gulp
   ```
