# Hydro Raindrop WordPress Plugin

## About WP Hydro Raindrop
This plugin allows users to enable the Hydro Raindrop MFA to add an extra layer of authentication security on a WordPress website.

## Requirements
* For the MFA to work you need to [register for an account](https://www.hydrogenplatform.com) on the Hydrogen platform.
* IMPORTANT: SSL (HTTPS) MUST be enabled for MFA to work.
* PHP 7.0 or higher is required.

## Installation and Configuration

* [Download](https://wordpress.org/plugins/wp-hydro-raindrop/), install and activate `WP Hydro Raindrop` in your WordPress installation.
* Under `settings` in the admin bar navigate to `Hydro Raindrop MFA`
* Open up a new tab in your browser and navigate to the [Hydrogen website](https://www.hydrogenplatform.com). Create an account, login.
* Generate API credentials by reading the agreement and signing at the bottom. You are now provided a `Client ID` and `Client Secret`.
* Paste the `Client ID` and `Client Secret` into the Hydro Raindrop MFA settings fields in WordPress.
* On the Hydrogen dashboard scroll down to the table below on the `Hydro` line and click `+ Create App` or click [here](https://www.hydrogenplatform.com/account/hydro-app).
* On the Hydro App page click `+ Add New` and name the application.
* You have now created your sandbox app and are provided an application ID. Paste that ID the Hydro Raindrop WordPress Config under `Applicaiton ID`.
* In set the dropdown to `sandbox`. Don't forget to set the dropdown to production once ready to move to production.

NOTE: All applications will remain in sandbox mode until approved. Please send Hydrogen a support message to review and approve it [here](https://www.hydrogenplatform.com/account/support).

## Further Reading
* [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop)
* [Hydrogen](https://www.hydrogenplatform.com)

## About Hydro
Hydro enables new and existing private systems to seamlessly integrate and leverage the immutable & transparent dynamics of a public blockchain to enhance application and document security, identity management, transactions and artificial intelligence. The global community of Hydro developers works to create smart contracts that enable this functionality, core protocols that facilitate on-chain integrations by private companies, and ancillary products and implementations of the protocols that empower end users to navigate within a global web3 financial framework.