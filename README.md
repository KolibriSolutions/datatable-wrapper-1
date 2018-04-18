# datatable-wrapper-1
A wrapper script around DataTables

Created by Jeroen 2016-2018, Marketplaces ELE. Kolibri Solutions
General init wrapper script for all datatables, including copy and csv export.
make sure your table has the class ".datatable"

* Function to transform all tables with class '.datatable' to a DataTable.
* Features on top of default DataTables:
* - Store/recall sorting/filtering settings in URL to share/bookmark a sorted table
* - Dropdown selects in the table header, for any column supplied in dropdownColumns. (Append a <br /> after the header text)
* - CSV/Copy buttons with datatables.buttons. Customize columns to export using exportColumns
* - Export valid URLs to CSV/Copy by prepending the domain before exporting
* - Add extra buttons with 'extraButtons'
* - Responsive view for small screens
* - Use with normal datatables-options using the customOptions argument

 @param cols array of options for each column. At least a Null array with a null for each column.
 @param dropdownColumns array of column indices. Each column index in this array gets a dropdown select.
 @param exportColumns array of columns, or Column selector. Included columns are used for the export to csv/copy.
 @param extraButtons extra buttons from DataTables.Buttons to include above the table.
 @param customOptions custom DataTables options to extend the default options with.
 @constructor

This script is no longer in production use, it has been replaced by datatable-wrapper-2, together with YADCF.
