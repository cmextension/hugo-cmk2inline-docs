---
title: Manage Columns
weight: 40
---

After installing `CM K2 Inline`, you can find it in Components menu item in Joomla! back-end top menu.

![](/images/backend_menu.jpg)

Access `CM K2 Inline`, you see the page to manage columns in `K2` item list. The core columns which are displayed in `K2` item list are created by default. You can't delete these columns but you can hide them if you don't need them in the item list.

![](/images/column_list.jpg)

You can do the following actions:

* **New**: Create new column for extra field.
* **Edit**: Edit a selected column.
* **Publish**: Show selected columns in `K2` item list.
* **Unpublish**: Hide selected columns in `K2` item list.
* **Show on phone**: Show selected columns on mobile.
* **Hide on phone**: Hide selected columns on mobile.
* **Check-in**: Check-in a checked-out column (column is being edited and not checked-out).
* **Delete**: Delete selected columns.

Create new column
-----------------

Click `New` button on the toolbar to create a new column, you see the form as the screenshot below.

![](/images/column_form.jpg)

* **Name**: The name of new column.
* **Language constant**: Language constant for the name of this column. This can be useful when there more than 2 languages in your back-end and you want to different names based on the current language. You can use Language Manager to add your custom language constant. If this field is empty, the Name field is used as column name.
* **Hidden on phone**: Show or hide this column on phone.
* **Width**: The width of column in item list. Example: if you want column has 300px widh, you enter `300px`; if you want it to take 50% of the item table, you enter `50%`.
* **Extra field**: The `K2`'s extra field which column displays info for.
* **Status**: Published column is showed in item list, unpublished column is not.

Change ordering
---------------

To change the columns's ordering, you sort the column list by ordering, drag and drop the icons in the first column. This is the same to changing ordering in other Joomla! core extension like Categories, Content (Articles),...