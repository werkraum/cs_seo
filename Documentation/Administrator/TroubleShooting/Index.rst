﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt

.. _admin-faq:

Trouble shooting
----------------

I get an error when I edit a page. What should I do?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Please include the TypoScript from the extension in your root ts.

There is no domain displayed in the google preview. What should I do?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Please insert a domain record at the the root page.

.htaccess disallow frontend access. There are no evaluation results. What should I do?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Give your server access to the frontend. Include the following line in your .htaccess file and replace
the x with the IP from the server.

Order allow,deny
Allow from xxx.xxx.xxx.xxx

You could also use the domain instead of the IP.

Allow from .mydomian.com