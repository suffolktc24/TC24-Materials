# TC24-Materials
Supporting materials for Tableau Conference 24 presentation - Build Better: Assembling the Ultimate Construction Dashboard.

These materials will provide you with the basic structure to navigate from one dashboard to another dashboard while maintaining the value of your selected parameter.  

You can then design the workbooks to have the same look and feel, making the end user think they are in the same dashboard.

Materials include:
2 Tableau workbooks (TC24 - Profit, TC24 - Sales) ; Excel-based URL data source (Navigation_URLs_TC24) (we upload as Tableau extract)

Materials not included:
Superstore sales data source; parameter data source

We use Superstore sales as the driver of the parameter data source for simplicity in this example, but you would ideally have a separate data source for this of just the parameter field you would like to use (e.g., `select distinct [parameter] from database.schema.table`).

To have this work on your Tableau site, please change "yourpod" and "yoursitenamehere" in the URL data source to correspond to your Tableau pod and Tableau site name. You can then upload this as a published data source on your site and connect the Tableau workbooks to that data source.
