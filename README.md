#WEBAssignmentBlog

### To run this app
- Run `composer install`
- Create MySQL database
- Create `.env` file
  - Update `APP_KEY` with `php artisan key:generate`
  - Update database connection info
- Run `php artisan migrate`
- Seed the database
  - `default.jpg` and `default-post.png` should have '777' permissions on Mac, but not necessary on Windows
  - Run `php artisan db:seed`
- Run `php artisan storage:link`
- Set up Apache web server