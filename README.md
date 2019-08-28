# MaintenancePassword

**A Statamic addon to display a maintenance page with a password access.**


This addon will add a maintenance page preventing acces to yoru website. You can sen set up a password to let "friends & family" people to cces the site. This is a great way to demo a site or remotely test new website before launch.


## Getting started

Juste copy the MaintenancePassword folder in your `site/addons` folder. After that, you may run the following command to refresh the addons :
```
php please update:addons
```

Then, add the following tag at the top of your layout file (usually found in `site/themes/[your theme]/layouts/default.html)`) : 

```
{{ maintenance-password }}
```

You then need to define a password in the addon's settings.


## Settings

Go to `Addons`, then click on the three dots at the right of the addon's line, and click `Settings`

Here you can set the main password.
You can also change the title and subtitle shown on the maintenance page. You can also set a logo if you need.


## Removing the mainenance page

If you want to remove the maintenance page, you either set an empty password in the settings, or to remove the addons from your site's addons foler.

## Coming soon
Here are some of the stuff that will be added in the near future :
 * custom css
 * setting the page's title
 * setting up (and revoking) multiple passwords.
 * one click to activate/deactivate the maintenace page
