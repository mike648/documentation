=============================
Marketing attribution reports
=============================

The *CRM* app can be used to create detailed lead reports to track the effectiveness of sales and
marketing campaigns, analyze the source of leads, and use filters and groups to organize the
data in each report.

Navigate to the reports
=================================
To access the lead data needed to create marketing attribution reports:

1. Go to the :guilabel:`Leads Analysis` page by navigating to
   :menuselection:`CRM app --> Reporting --> Leads`.

.. image:: marketing_attribution/reporting-tab-and-leads.png
   :align: center
   :alt: Open the CRM app and click on the Reporting tab at the top of the page, then click Leads.

The :icon:`fa-area-chart` :guilabel:`Graph view` will be shown by default, displaying the number of
sales separated by month and grouped by team in graph form.

2. Change to :icon:`oi-view-list` :guilabel:`List view` by clicking the last button on the
   top-right of the page.

.. image:: marketing_attribution/list-view-button.png
   :align: center
   :alt: Click the button with four horizontal lines on the top right of the Leads Analysis page.

Create reports
==============

To start creating a report:

#. Remove any filters already in the search bar located in the top-middle of the page,
   such as :guilabel:`Active or Inactive` or :guilabel:`Created on: 2024` by clicking the
   :icon:`fa-times` :guilabel:`cancel button` next to each filter.
#. Click the :icon:`fa-arrow-down` :guilabel:`down arrow` to the right of the search bar to
   see the list of filtering and grouping parameters.

.. note::
   :guilabel:`Filters`, located in the left column of the search options, can be used to keep only
   the results that fit the filter. For example, selecting the :guilabel:`Won` filter will only
   show won leads in the attribution report. :guilabel:`Group By`, found in the middle column, is
   used to organize the results into groups and can be used with or without filters.

Any combination of filters and groups can be set to generate a marketing attribution report.

.. image:: marketing_attribution/search-results-multiple-options.png
   :align: center
   :alt: Select any number of filters and groups in the search options.

.. tip::
    Setting multiple Group By options will create nested groups according to which is selected
    first. For example, selecting :guilabel:`Country` followed by :guilabel:`City` in
    :guilabel:`Group By` will sort all results *first* by country, *then* by each city in that
    country.

    This can be verified by looking at the direction of the carat in the group tile in
    the search bar.

    .. image:: marketing_attribution/group-by.png
       :align: center
       :alt: The text in the tile is `Country > City`, showing that city is a subgroup of country.

.. example::
    For a useful first report:

    #. Select the :guilabel:`Active` filter to view only leads that are still marked as active.
    #. Select :guilabel:`Source` followed by the :guilabel:`City` or :guilabel:`Country`
       groups depending on which grouping is more relevant.

    .. image:: marketing_attribution/campaign-and-country-groups.png
       :align: center
       :alt: Each lead is now sorted by source, followed by city or country.

    This report will contain all active leads grouped first by the source of the lead, then
    the country or city each lead is from.

Export reports
==============

To begin exporting a report as a spreadsheet:

#. Ensure that all filters and groups for the given report are selected.
#. Click on the :icon:`fa-cog` :guilabel:`Settings button` to the right of Leads Analysis in the
   top-left of the page to view the available export options.

To export the report in the Odoo *Documents* app:

#. From settings, navigate to :menuselection:`Spreadsheet --> Insert list in spreadsheet`.
#. A menu will appear with export options:

   #. The report can be named using the `Name of the list`
      field.
   #. The number of items on the report can be set with the field labeled: `Insert the first _
      records of the list.`
   #. Select either a new blank spreadsheet, or export into an existing spreadsheet
   #. Click the :guilabel:`Confirm` button.

.. image:: marketing_attribution/documents-export.png
   :align: center
   :alt: Set the name, number of records, and location of the export in the option menu.

To export the report as a \*.xlsx file for use in an external spreadsheets program:

#.  From settings, click :icon:`fa-upload` :guilabel:`Export All`.
#.  If prompted, choose a file location and a name for the file, then click :guilabel:`Save`.