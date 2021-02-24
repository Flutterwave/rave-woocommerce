# WooCommerce Rave Payment Gateway

 - **Contributors:** Flutterwave Developers
 - **Tags:** rave, woocommerce, payment gateway, bank account, credit card, debit card, nigeria, kenya, international, mastercard, visa, barter
 - **Requires at least:** 4.4
 - **Tested up to:** 5.6.1
 - **Stable tag:** 2.2.6
 - **License:** MIT - see below

Take payments on your store using Rave.



## Description


Accept Credit card, Debit card and Bank account payment directly on your store with the Rave payment gateway for WooCommerce.

#### Take Credit card payments easily and directly on your store

Signup for an account [here](https://rave.flutterwave.com)

Rave is available in:

* __Nigeria__
* __Ghana__
* __Kenya__
* __Uganda__
* __Tanzania__
* __Rwanda__
* __South Africa__


## Recurring Payment Support
For Recurring payment, you will need to install the [WooCommerce Subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/) plugin. No subscription plans is created on Rave. The WooCommerce Subscriptions plugin handles all the subscription functionality.



## Installation


### Automatic Installation
*   Login to your WordPress Dashboard.
*   Click on "Plugins > Add New" from the left menu.
*   In the search box type __Rave Woocommerce Payment Gateway__.
*   Click on __Install Now__ on __Rave Woocommerce Payment Gateway__ to install the plugin on your site.
*   Confirm the installation.
*   Activate the plugin.
*   Click on "WooCommerce > Settings" from the left menu and click the __"Payments"__ tab.
*   Click on the __Rave__ link from the available Checkout Options
*   Configure your __Rave Payment Gateway__ settings accordingly.


### Manual Installation
*  Download the plugin zip file.
*  Login to your WordPress Admin. Click on "Plugins > Add New" from the left menu.
*  Click on the "Upload" option, then click "Choose File" to select the zip file you downloaded. Click "OK" and "Install Now" to complete the installation.
*  Activate the plugin.
*  Click on "WooCommerce > Settings" from the left menu and click the __"Payments"__ tab.
*  Click on the __Rave__ link from the available Checkout Options
*  Configure your __Rave Payment Gateway__ settings accordingly.

For FTP manual installation, [check here](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).


## Split payment feature
* Enable the split payment in the rave woocommerce settings page.
* Enter the specify subaccounts for the split (create can create subaccounts on your Flutterwave dashboard).
* save and start transaction

This split will be initiated for all transactions.

## Assign a subaccount to a Product
* Disable the split payment in the rave woocommerce settings page.
* Click on "Products".
* Select "Add New".
* Scroll down until you see the 'Flutterwave - Select subaccount'.
* Select a subaccount.

### Configure the plugin
To configure the plugin, go to __WooCommerce > Settings__ from the left menu, click __Payments__ tab. Click on __Rave__.

* __Enable/Disable__ - Check the box to enable Rave Payment Gateway.
* __Mode__ - Check the box to enable Live Mode.
* __Webhook Instruction__ - Please ensure that you copied the URL displayed in red into your Rave dashboard as described.
* __Enter Secret Hash__ - Ensure that secret hash entered is the same with the one on your Rave dashboard.
* __Rave Test Public Key__ - Enter your test public key ravesandbox.flutterwave.com.
* __Rave Test Secret Key__ - Enter your test secret key ravesandbox.flutterwave.com.
* __Rave Live Public Key__ - Enter your live public key rave.flutterwave.com.
* __Rave Live Secret Key__ - Enter your live secret key rave.flutterwave.com.
* Click __Save Changes__ to save your changes.



## Screenshots

##### 1. Rave WooCommerce Payment Gateway Setting Page
![Screenshot featuring Rave's WooCommerce Payment Gateway Setting Page](assets/img/screen1.PNG)


##### 2. Rave WooCommerce Payment Gateway on the Woocommerce order checkout page
![Screenshot featuring Rave's WooCommerce Payment Gateway on the WooCommerce order checkout page](https://cloud.githubusercontent.com/assets/8383666/21472783/a87138de-cae9-11e6-9330-4550c45a028c.png)


##### 3. Rave pay modal showing card payment option
![Screenshot with Rave's pay modal showing card payment options](assets/img/screen2.PNG)


##### 4. Rave pay modal showing account payment option
![Screenshot with Rave's pay modal showing account payment options](assets/img/screen3.PNG)



### Suggestions / Contributions

To contribute, fork the repo, add your changes and modifications, then create a pull request.


### License

##### MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
