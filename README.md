# Laravel 6 Real Estate / Management with Adminpanel





This is a result of 2-hours live-coding series on Youtube: [see playlist](https://www.youtube.com/watch?v=Oq_b1g_JpCM&list=PLdXLsjL7A9k0HPZVGiA7WZDM9Zg0OnulJ)

![Laravel Real estate administration](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-25-at-11.12.16-AM.png)

![Laravel Real estate front](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-25-at-1.53.12-PM.png)

- - - - -

- Front-end part is taken from [Homespace theme](https://colorlib.com/wp/template/homespace/) by [Colorlib](https://colorlib.com) and transformed into Laravel Blade and assets.
- Admin part is fully generated with [QuickAdminPanel](https://2019.quickadminpanel.com).

---

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel by going go `/login` URL and login with credentials __admin@admin.com__ - __password__

