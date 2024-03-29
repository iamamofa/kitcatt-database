## How to Set up the project

----->  Create .env file if not exist into project's root. <---
- Run `composer install`
- Run `php artisan key:generate`
- Set up the DB configurations into `.env`

      DB_USERNAME=root (database username)
      DB_PASSWORD=root (database password)


- Run `php artisan migrate --seed`

## Import Postman Collection

Import postman collection from `project_root/postman/postman_collection.json`

### Default User Credentials

- Email : `pearl_dickinson@gmail.com`
- Password : `w_EaYt2FfQMXFym`

### Default Admin Credentials

- Email : `laura_hartmann@hotmail.com`
- Password : `xPqBWaee7tOHD72`

Note: you can change the admin / user credentials as you want and then again you have to run php artisan migrate:fresh --seed


#### Other Information :

- Role Admin will have all the permission by default.
- We are providing Roles / Permissions APIs from where you can create new role and assign permissions to related Role
- If You are assigning some Role to User then all permissions of that Role will be default assigned to that user.



## Support

If you want to support the development of this app, feel free to [sponsor](https://ko-fi.com/justiceoheneamofa) me or [buy me a coffee](https://ko-fi.com/justiceoheneamofa).

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/justiceoheneamofa)

## Copyright

This project has no license. That means you are not allowed to sell or distribute this app.
All rights reserved.
© 2023 Justice O. Amofa
