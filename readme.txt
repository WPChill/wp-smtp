=== WP SMTP ===
Tags: wp smtp,smtp,mail,email,logs,mailer,wp mail,gmail,yahoo,mail smtp,ssl,tls
Contributors: wpchill,silkalns,raldea89,giucu91,andylukak,shenyanzhi
License: GPLv3 or later
Requires at least: 2.7
Tested up to: 5.9
Stable tag: 1.2.4

WP SMTP can help us to send emails via SMTP instead of the PHP mail() function.

== Description ==

WP SMTP can help us to send emails via SMTP instead of the PHP mail() function.
It adds a settings page to "Dashboard"->"Settings"->"WP SMTP" where you can configure the email settings.
There are some examples on the settings page, you can click the corresponding icon to view (such as "Gmail""Yahoo!""Microsoft""163""QQ").
If the field "From" was not a valid email address, or the field "SMTP Host" was left blank, it will not reconfigure the wp_mail() function.

= CREDITS =

WP SMTP plugin was originally created by BoLiQuan. It is now owned and maintained by Yehuda Hassine.

= Usage =

1. Download and extract `wp-smtp.zip` to `wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. "Dashboard"->"Settings"->"WP SMTP"
4. For more information of this plugin, please visit: [Plugin Homepage](https://wpsmtpmail.com/ "WP SMTP").

== Installation ==

1. Download and extract `wp-smtp.zip` to `wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. "Dashboard"->"Settings"->"WP SMTP"
4. For more information of this plugin, please visit: [Plugin Homepage](https://wpsmtpmail.com/ "WP SMTP").

== Changelog ==

= 1.2.4 =
Changed: Added base64 encode for username and passwords ( https://github.com/WPChill/wp-smtp/issues/2 )
Added: Setting to disable the email logging. ( https://github.com/WPChill/wp-smtp/issues/3 )

= 1.2.3 =
Fix auto loading require path

= 1.2.2 =
Just update info

= 1.2 =
Fixed: handle the mail parts as needed

= 1.2 =
New and shiny mail logger.

= 1.1.11 =
All good, still maintained, just update some info

= 1.1.10 =

New maintainer - yehudah
https://wpsmtpmail.com/v1-1-10-wp-smtp-is-back/

* Code structure and organize.
* Credentials can now be configured inside wp-config.php

= 1.1.9 =

* Some optimization

= 1.1.7 =

* Using a nonce to increase security.

= 1.1.6 =

* Add Yahoo! example
* Some optimization

= 1.1.5 =

* Some optimization

= 1.1.4 =

* If the field "From" was not a valid email address, or the field "Host" was left blank, it will not reconfigure the wp_mail() function.
* Add some reminders.

= 1.1.3 =

* If "SMTP Authentication" was set to no, the values "Username""Password" are ignored.

= 1.1.2 =

* First release.


== Screenshots ==

1. Main settings
2. Test settings
3. Mail Logs
4. Collapse to show mail body
5. Select rows to delete


== Frequently Asked Questions ==

You can submit it in https://wordpress.org/support/plugin/wp-smtp, if It's urgent like a bug submit it here: https://wpsmtpmail.com/contact/


