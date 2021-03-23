Übersetzungstypen
Textübersetzung
Ausgangstext
5000 / 5000
Übersetzungsergebnisse
Pagseguro Integration Module for OpenCart
======================================
---
Description
---------
---
With the module installed and configured, you can offer the pagseguro as a payment option in your store. The module uses the following features that the pagseguro offers in the form of APIs:

 - Integration with [PAY API]
 - Integration with the [notification API]


Requirements
----------
---
 - [OpenCart] 1.5.5.1
 - [PHP] 5.1.6+
 - [SPL]
 - [CURL]
 - [SUN]


Installation
----------
---
 - Make sure there is no installation of other modules for the pagseguro on your system;
 - Download the repository as a zip file or make a clone;
 - Copy the * admin * and * catalog folders into your OpenCart installation. If you are informed of the superscript of some files, you can confirm the trouble-free procedure. This installation will not affect any file from your system, you will only add the pagseguro module files;
 - Make sure that the permissions of the folder and files recently copied are, respectively, defined as 755 and 644;
 - In the administrative area of ​​your system, go to the Extensions -> Payments menu -> Pagseguro -> Install.


Settings
------------
---
To access and configure the module access the Extensions -> Payments -> Pagseguro -> Edit menu. The available options are described below.

 - ** Activate module **: Active / Disables the module.
 - ** Display Order **: Sets the order in which the pagseguro will appear at checkout from your store.
 - ** E-mail **: E-mail registered in Pagseguro.
 - ** Token **: Token generated in the pagseguro.
 - ** Environment **: Defines the environment of use
 - ** Checkout **: Specifies the checkout template that will be used. You can choose between standard checkout, Lightbox checkout.
 - ** Redirection URL **: At the end of payment flow in PagSeguro, your client will be automatically redirected to the confirmation page in your store or to the URL that you inform in this field. To activate redirection at the end of the payment, it is necessary to activate the service of [API payments]. Note: This URL is automatically informed and you should only change it if you want your customers to be redirected to another location.
 - ** Notification URL **: Whenever a transaction changes from status, the pagseguro sends a notification to your store or to the URL that you inform in this field. Note: This URL is automatically informed and you should only change it if you want to receive notifications in another location.
 - ** Charset **: Coding of your system (ISO-8859-1 or UTF-8).
 - ** Log **: Active / Disables Log Generation.
 - ** Directory **: Enter the location from the OsCommerce installation root where you want to create the log file. Ex .: /logs/ps.log. If you do not know anything, the log will be recorded inside the ../pagsugurroibrary/pagseguro.log.


Changelog
---------
1.3

- adding the option to use the Lightbox checkout;
- adjustments and improvements in general;

1.2

- Adding the Sandbox / Production switching functionality;
- changes in the layout of the configuration panel;

1.1

- Upgrade of lib php in the module;

---
1.0

 - Initial release. Integration with Checkout API and Notifications API;
 - Integration with Pagseguro Notification API;
 - Suitability of the license;
 - Notification;
 - Standard checkout;
 - Integration with sandbox;


License
-------
---
Copyright 2013 Pagseguro Internet Ltda.

Licensed Under The Apache License, Version 2.0 (The "license"); You may not use this file except in compliance with the license. You may get the copy of the license at

http://www.apache.org/licenses/license-2.0

Unless Required by Applicable Law or Agreed to In Writing, Software Distributed Under The License Issa Distributed On An "Basis, Without Warranties or Conditions Of Any Kind, Either Express or Implied. See The License for The Specific Language Governing Permissions and Limitations Under The License.


Grades
-----
---
 - Pagseguro only accepts payment using the Brazilian real currency (BRL).
 - Make sure the informed email and token are related to an account that has the seller or business profile.
 - Make sure you have correctly defined the charset according to the encoding (ISO-8859-1 or UTF-8) of your system. This will prevent transactions from generating possible errors or breaks or even if special characters can be presented differently from the usual.
 - In order to normally occur the generation of logs, make sure that the directory and log file have read and write permissions.


[Doubts?]
----------
---
If you have an e-mail to developers@pagseguro.com.br


Contributions
-------------
---
Did you find it and correct a bug or do you have any feature in mind and want to contribute?

* Make a Fork.
* Add your feature or bug fix.
* Send a pull request in [GitHub].


  [PAYMENT API]: https://pagseguro.uol.com.br/v2/guia-de-integracao/api-de-pagamentos.html
  [API 
Mehr zu diesem Ausgangstext
Für weitere Übersetzungsinformationen ist ein Ausgangstext erforderlich
Feedback geben
Seitenleisten
Zeichenbeschränkung: 5.000. Du kannst mithilfe der Pfeile weiter übersetzen.


[PAYMENT API]: https://pagseguro.uol.com.br/v2/guia-de-integracao/api-de-dagamentos.html
   [Notification API]: https://pagseguro.uol.com.br/v2/guia-de-integracao/api-de-notificacoes.html
   [Doubts?]: Https://pagseguro.uol.com.br/desennvolver/comunity.jhtml
   [Payments via API]: https://pagseguro.uol.com.br/integracao/pagamentos-via-api.jhtml
   [Transaction Notification]: https://pagseguro.uol.com.br/integracao/notificacao-de-transacoes.jhtml
   [OpenCart]: http://www.opencart.com/
   [PHP]: http://www.php.net/
   [SPL]: http://php.net/manual/en/book.spl.php
   [CURL]: http://php.net/manual/en/book.curl.php
   [Gift]: http://php.net/manual/en/book.dom.php
   [GITHUB]: https://github.com/pagseguro/opencart 
