Meeting Room Booking System (MRBS) is a webapp for booking rooms or other resources.

Some features from the website:

- Simple to follow, Web based options and intuitive presentation
- Flexible Repeating Bookings
- Ensures that conflicting entries cannot be entered
- Reporting option
- Selectable DAY / WEEK / MONTH views
- Multiple auth levels (read-only, user, admin)
- Support for bookings by time or period - ideal for use in schools
- Room administrators can be notified of bookings by email
- Multiple languages supported (translated to Catalan, Czech, Chinese, Danish, Dutch, Finnish, French, German, Greek, Italian, Japanese, Korean, Norwegian, Portuguese, Slovenian, Spanish, Swedish, Turkish)
- Stable and in use at many organizations

This package integrates MRBS with YunoHosts SSO (you are automtically logged in via YunoHost) and LDAP (the user list is fetched from YunoHost). Admin rights are also configured as a permission in YunoHost.
If you want to modify the settings, you can copy-paste and edit lines from [systemdefaults.inc.php](https://github.com/meeting-room-booking-system/mrbs-code/blob/main/web/systemdefaults.inc.php) and [areadefaults.inc.php](https://github.com/meeting-room-booking-system/mrbs-code/blob/main/web/areadefaults.inc.php) into `/var/www/mrbs/web/config.inc.php`. The files have a good amount of comments that explain the settings.
