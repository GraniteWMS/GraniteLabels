These are updated Label files for use with Bartender 2019 onwards.  

To use ShipLabelIntegration do the following:
Change the Database connection and it is ready to use.
The View Label_ShipLabel gets data from ERP (EVOTable -InvNum)(Sage300 -OEORDH)
The available fields are mapped on the label format ShipLabel with a Database connection and Query prompt on Order Number (Number field in the View)
BTIntegration picks up a record where Status is ENTERED, prints the Record and Updates Status to PRINTED.  This allows easy reprint and test by just changing the Status.

The ShipLable integration is also set up to print a Receive Confirmation label.  In a future iteration I will split this out