## Swiss Accounting Integration for Frappe/ERPNext v14

ERPNext Functionality with Swiss QR Integration 
and Abacus Export


### Structure

App Contains 2 Modules

1. Abacus Exports
2. Swiss QR Bill

#### Swiss QR Bill

It Contains 1 Doctype Called **Swiss QR Bill Settings**

In order to Setup QR Bill to Working Following Things are Required

1. Create A Company With Proper Address
2. Create A Customer with Proper Address and Language
3. Create A Bank Account For Company with IBAN
4. Add Entry in Swiss QR Bill Settings for Company


### To install this Swiss Accounting Integration,

1. bench get-app https://github.com/bvisible/Swiss-Accounting-Integration.git
2. bench --site prod.local install-app swiss_accounting_integration
3. bench clear-cache

To uninstall this Swiss Accounting Integration,

1. bench --site prod.local uninstall-app swiss_accounting_integration


#### License

GNU GPL V3
