# MoneyMoney extension for Uberspace.de accounts

This extension for [MoneyMoney](https://moneymoney-app.com/) retrieves
the balance and transactions from [Uberspace.de](https://uberspace.de/)
accounts.

## Login

Email-based login only: After entering your credentials, MoneyMoney will fetche data for all Uberspaces/asteroids associated with that email address.

This extension is a fork of [hatobi's fork](https://github.com/hatobi/moneymoney-uberspace) (which supports email-based login, but still mandates you to specify asteroid(s) manually) of [puppe's original extension](https://github.com/puppe/moneymoney-uberspace) (now outdated).

~~Quick-fix: login for Uberspace accounts using an e-mail address for login is now possible. Username used in MoneyMoney should consist of two parts:
``user@domain.de|username`` where the first part is the e-mail address used for logging in to the Uberspace dashboard and the second part is the username used on the host (nicknamed "Asteroid").~~

~~Old accounts that still use username and password for login do not need to change the saved login credentials.~~

## Background

Since May 2024 it is possible to manage multiple Uberspace hosts under the same login credentials ([Announcement](https://blog.uberspace.de/2024/05/alle-unter-einem-dach/)).


