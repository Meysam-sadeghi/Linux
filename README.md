To send email through Gmail, you need to install the msmtp package (sudo apt install msmtp or sudo yum install msmtp).
If you use Gmail, you need to enable "Allow less secure apps" in your Gmail account settings.
If you are using the method of sending mail through a local server, make sure that ssmtp or postfix is ​​configured correctly.
If needed, you can run this script on a schedule using cron.
You can report more detailed information about consumed resources using the mpstat, iostat, free and nload tools.
This script is an example and may require additional configuration for your specific environment.
