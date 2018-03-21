# Scheduler-InvoiceNinja
A module for InvoiceNinja for scheduling events via FullCalendar


Scheduler Module for InvoiceNinja
----------------------------------

Installation or Update:
Initial Installation or update from Scheduler v2.0.0 and later:

1.) Open a terminal in the InvoiceNinja web directory.

2.) Type "php artisan module:install cytech/scheduler --type=github" and press "Enter".

3.) Type "php artisan module:migrate Scheduler" and press "Enter".
    Answer "Yes" if prompted to continue.

4.) Type "php artisan module:publish scheduler" and press "Enter".
    Check that all permissions for Modules directory and contents are correct.

In InvoiceNinja

5.) Scheduler menu - Utilities - Settings
       Set options to your preference.
       
       If running the Workorders Addon for InvoiceNinja:
       Set Enable "Create Workorder" functionality to "Yes"

NOTE: Occasionally there may be a conflict with old views in the Laravel cache.

      If you receive an odd error on page load after install try and clear the cache by:
      (in browser address bar:)
            http://<YourFusionInvoice>/scheduler/viewclear

That should do it !
Description of functions is available in Scheduler -> Utilities -> About

If you find this product useful, feel free to buy me a beer: https://paypal.me/cytecheng



Alternative installations:

1.)

clone into "yourInvoiceNinja"/Modules/Scheduler:

cd /var/www/yourInvoiceNinjaWeb

mkdir Modules

cd Modules

git clone https://github.com/cytech/scheduler.git Scheduler

or

Extract contents of zip file into "yourInvoiceNinja"/Modules/Scheduler  web directory.

You should have a "yourInvoiceNinja"/Modules/Scheduler directory and contents
containg Assets, Config, Database, etc.
    
"yourInvoiceNinja"/Modules/Scheduler

                                ├── Assets
                                ├── Config
                                ├── Database
                                ├── Datatables
                                ├── Http
                                ├── Models
                                ├── Policies
                                ├── Presenters
                                ├── Providers
                                ├── Repositories
                                ├── Resources
                                ├── Transformers
                                ├── composer.json
                                ├── FullCalendar LICENSE.txt
                                ├── gulpfile.js
                                ├── LICENSE
                                ├── License.txt
                                ├── module.json
                                ├── package.json
                                ├── README.md
                                ├── SchedulerAuthProvider.php
                                ├── start.php
                                └── yarn.lock


2.) Open a terminal in the InvoiceNinja web directory.

3.) Type "php artisan module:migrate Scheduler" and press "Enter".
    Answer "Yes" if prompted to continue.

4.) Type "php artisan module:publish scheduler" and press "Enter".
    Check that all permissions for Modules directory and contents are correct.

5.) Scheduler menu - Utilities - Settings
       Set options to your preference.
       
       If running the Workorders Addon for InvoiceNinja:
       Set Enable "Create Workorder" functionality to "Yes"

NOTE: Occasionally there may be a conflict with old views in the Laravel cache.

      If you receive an odd error on page load after install try and clear the cache by:
      (in browser address bar:)
            http://<YourFusionInvoice>/scheduler/viewclear

