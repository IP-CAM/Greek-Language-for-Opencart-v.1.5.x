Greek Translation of OpenCart
==============================

This translation is for version 1.5.6 of OpenCart and for catalog only (not for the admin interface).
  
Installation
-----------
1. Copy the 'catalog' and 'admin' folders into your OpenCart installation.
2. Make sure the folder has - as well as its contents - the appropriate permissions as listed in the OpenCart manual.
3. Enter the OpenCart administration, go to System> Localization> Languages.
4. Enter a new language with the following parameters:
  Language Name: Greek
  Code: gr
  Locale: el_GR.UTF-8, greek
  Image: gr.png
  Directory: greek
  Filename: greek
  Status: Enabled
  Sort Order: 2 (or any other available number you have, if for example it will be only Greek put 1)
5. Click Save and the language is installed.

  Log in normally to your store and change the language to Greek from the icon at the top of the screen. Browse the store and make sure all texts are displayed correctly. After checking your store, you can preselect Greek as the language.

FAQ
---
* Q: Since this translation is for catalog only, why add files to the `admin` directory?

A: OpenCart 1.5.6 seems to be looking for files in `admin / language / greek` for some emails sent to the customer, such as status update of the order, instead of using files from` catalog / language / greek`. Therefore, I have copied all the `admin / language / english` from the default installation to` admin / language / greek` and translated only some files related to emails that go to the client. Maybe there is a better way to fix this but, for now, it works.

* Q: Are there any plans for translating the administration interface?

A: No. I personally prefer it in English so I'm not interested in bothering to translate it. However, if anyone is interested and bothers, I would be happy to include it in this project.

License
------------
This translation is governed by the terms of use of the GPL v3 license.

The project is on github at:
https://github.com/lathan/opencart-greek
Any corrections, remarks, comments and pull requests are welcome.

Good sales :) 
