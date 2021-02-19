---
title: Install - Update - Uninstall
weight: 20
---

Install
-------

The installation is easy, just like installing any other Joomla! extensions, you can use Joomla!'s `Extension Manager` to install. Using `Upload & Install` tool to upload the ZIP package of `CM K2 Inline` to install is the easiest and fastest way.

Update
------

You can update `CM K2 Inline` with Joomla!'s `Extension Manager`, the same way you update other Joomla! extensions.

After you update, you should go to `Template Override` section in `CM K2 Inline` to click `Create override layout file` to update the override layout file in your template's override folder. This makes sure you have the latest code, otherwise there would be errors.

Uninstall
---------

You can remove `CM K2 Inline` with `Extension Manager`. Before you uninstall, you need to go to `Template Override` section and click `Delete override layout file` button to delete the override layout file in your template's override folder.

If you forget deleting override layout file before you uninstall `CM K2 Inline`, you still can delete it manually by using file manager in your hosting control panel or FTP client. The file is located at `administrator/templates/TEMPLATE NAME/html/com_k2/items/default.php`, replace `TEMPLATE_NAME` with the name of your default back-end template; if you use the default back-end of Joomla! 3, the file path is `administrator/templates/isis/html/com_k2/items/default.php`.

If override layout file still exits in your template's override folder after you uninstall `CM K2 Inline`, you will have errors in your `K2`'s item list.