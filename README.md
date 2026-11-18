# Decadent plugin for Decaid

Connects a Decent espresso tablet running [Decaid](https://github.com/decentespresso/decaid) to [Decadent](https://decadentcoffee.app), the dial-in companion: your coffees, your shots and the profile for the next one.

## Install

The easy way: [Tablet setup](https://decadentcoffee.app/clean-decent-tablet/). Plug the tablet into a computer with a USB cable and open that page in Chrome or Edge. It installs the Decadent app on the tablet, adds this plugin to Decaid and switches it on.

Or by hand:

1. On the tablet, open Decaid and go to **Plugins**.
2. Open the cogwheel menu and choose **Install plugin**, then **GitHub Release**.
3. Type `decadentcoffee/decadent-plugin` and choose **Install**.
4. Decaid adds the plugin switched off. On **Decadent** in the list, open the **⋮** menu and choose **Load**, then switch on **Auto-load on startup**.

Decaid keeps the plugin updated from here.

## Then

Decaid's **Notifications** now show a notice from Decadent. Tap **Open Decadent** there, or open [decadentcoffee.app/app](https://decadentcoffee.app/app/) on the tablet. Log in or sign up, and Decadent links the tablet to your account. Chrome offers to add the Decadent icon to the tablet's Home screen from that page.

Needs Decaid 0.9.2 or later.

## What it does

- Reports the machine's state and finished shots to your Decadent account.
- Loads the profile Decadent recommends when you choose it in the app.
- It starts nothing on the machine by itself.

Permissions: `log`, `api`, `pluginStorage`, `notifications`.
