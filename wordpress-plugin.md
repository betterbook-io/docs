---
description: Wordpress Plugin
---



## Wordpress Plugin
The [BetterBook Wordpress Plugin](https://wordpress.org/plugins/betterbook/) is an easy way to
integrate the BetterBook booking system into an existing Wordpress website.  This section outlines the 
steps required in installing the Wordpress plugin on your Wordpress website as well as configuring 
the plugin to work with your BetterBook account.

## Installation
### Guided Installation
Install the [BetterBook Wordpress Plugin](https://wordpress.org/plugins/betterbook/) from the Wordpress
Admin console by navigating to `Plugins > Add New` and searching for `BetterBook`.  
 
From the search results, click on the `Install` button to install the latest version of the 
plugin.


![Install the BetterBook Wordpress Plugin in Wordpress to take online bookings in Wordpress](https://github.com/betterbook-io/docs/raw/master/assets/installation-screenshot.png "Install the BetterBook Wordpress Plugin in Wordpress")

 
### Manual Installation
If you are doing a manual install of the plugin, download the plugin from https://wordpress.org/plugins/betterbook/
 and unzip the contents into your `/wp-content/plugins/` directory.
 
The `BetterBook` plugin should now be visible in the `Plugins` view in your Wordpress dashboard.  
Activate the plugin through the ‘Plugins’ menu in WordPress.

## Configuration
Setting up your [BetterBook Wordpress Plugin](https://wordpress.org/plugins/betterbook/) is easy as it
requires only the API Key to be set in the Settings area.


### Setting your API key
Your API key is a unique key that identifies you as a BetterBook client, and is 
generated when you [sign up](https://www.betterbook.io/signup) for a BetterBook account.

The API Key is required in order for the plugin to work, so it is important to configure the 
key in the [BetterBook Wordpress Plugin](https://wordpress.org/plugins/betterbook/) Settings 
dashboard.

To configure your API Key:
1. Navigate to `Settings -> BetterBook` in your Wordpress Admin Console
2. Enter your API Key 
3. Click on "Save" to save the changes.

### Adding the short code to a post
The Wordpress widget can be added to any Post or Page that are created in Wordpress.  

Simply add the following line anywhere in the content body of a Post or Page to 
include the widget in that page:
```php
[betterbook_widget]
```

Save the changes to the page.

