# Themely WHMCS Hook

#### Integrate Themely cPanel plugin with WHMCS and automatically install WordPress on new account creation.

## Installation Instructions

Hooks live inside files located within the `/WHMCS_ROOT/includes/hooks/` directory. To integrate Themely cPanel plugin with WHMCS follow the instructions below.

**Step 1**

Download the `themely.php` file and upload/place it to your hooks directory.

**Step 2**

Log into your WHMCS Admin Dashboard and navigate to `Setup > Products & Services > Products & Services`.

**Step 3**

Click the edit icon for the product you wish to configure. Then, click on `Custom Fields`.

**Step 4**
 
Create 2 custom fields for the WordPress Admin Username and Password. Field names **must be exactly** as you see highlighted below (upper and lowercase characters do matter). Display order is of course at your discretion.

`WordPress Admin Username`

`WordPress Admin Password`

Select *Required Field* & *Show on Order Form* for both custom fields.

![Themely WHMCS Custom Fields](assets/whmcs-custom-fields-20191205.PNG)


## Configuration Instructions

You can select which theme will be installed with WordPress by editing line 90 and 91 of the `themely.php` file.

Configuration options are found on line 86-89.

![Themely WHMCS Hook Config](assets/whmcs-hook-config-20191205.PNG)


## Get Help/Support

To get assistance with the Themely WHMCS hook or to suggest new features; here's how you can reach me:

Submit support ticket: https://github.com/ismaelyws/themely-whmcs-hook/issues (click on the green **New Issue** button)

Email: ismaelyws [at] gmail [dot] com

Twitter Direct Message: https://twitter.com/messages/compose?recipient_id=ismaelyws

Phone: +1 (514) 883-0132 (please only use this in case of emergency)

Time Zone: Eastern Standard Time (GMT -4)