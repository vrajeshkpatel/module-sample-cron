# module-sample-cron
Magento2 Sample Cron Module

Run the following commands:

php bin/magento setup:upgrade

php bin/magento setup:static-content:deploy

php bin/magento cron:run

php bin/magento cache:clean

If you want to verify the custom cron job in the terminal through SQL run below query in phpmyadmin

SELECT * from cron_schedule WHERE job_code like `%custom%`;

<b>Supports : Magento 2.0.x, 2.1.x, 2.2.x, 2.3.x and 2.4.x</b>
