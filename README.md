# pushover-messenger
Bash script to send push notifications to mobile devices using the Pushover service. Create an account on https://Pushover.net then create an application. Use your user key and application key to send custom push notifications to your devices.

-u, Pushover user key (will use $PU_USER env varialbe if set)
-k, Pushover app token/key (will use $PU_TOKEN env variable if set)
-t, title (optional)
-m, message
