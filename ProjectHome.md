The default CRM application available at [iFreeTools CRM](http://crm.ifreetools.com) has a native data-model. That is, the model is defined within the source code.

To have a fully customizable CRM application, which can match more with one's business processes, one can use [iFreeTools Creator](http://creator.ifreetools.com).  Within Creator, one can define their own data-model, in terms of _Entities_ ("tables") and _Attributes_ ("columns" or "fields").

This project here holds the data-models for CRM (Customer Relationship Management) application - equivalent to the one found in the native CRM application. This data-model can be imported as CSV files into [iFreeTools Creator](http://creator.ifreetools.com) to get started quickly.

Before importing the CRM _Entities_ and _Attributes_, kindly make sure the **App Settings** under **Admin** has _**Extends**_ value set as _Engine_ (which is the default value, if you had not changed this explicitly), as we want a blank slate to built upon. If in case you had changed this earlier, from the default value to _CRM_, you will have to change this back again to _Engine_ before import.

You can then add/update/delete _Entities_ or _Attributes_, to tweak the application as per your requirement.

## Steps to create you own Custom CRM Application, using iFreeTools Creator ##

  * Download the CSV files : [entities.csv](http://crm-apps-datamodel.googlecode.com/svn/trunk/csv/entities.csv) and [attributes.csv](http://crm-apps-datamodel.googlecode.com/svn/trunk/csv/attributes.csv)
  * Login into [iFreeTools Creator](http://creator.ifreetools.com) using either you Google Apps or Google user account.
  * [Customize and Re-brand](http://blogs.ifreetools.com/2009/11/ifreetools-crm-on-your-sub-domain-with.html) the application, including mapping to your Google Apps sub-domain. (**optional**)
  * Proceed to _Admin_ > _Entities_ > _More Actions_ (button) > _Import Entities_
  * Provide the entities.csv file and complete the import process. You will now find the entities listed on the left panel.
  * Proceed to _Admin_ > _Attributes_ > _More Actions_ (button) > _Import Attributes_
  * Provide the attributes.csv file and complete the import process.

**That's it !** Now your app is ready with the default CRM datamodel.

## Default CRM Entities and Attributes ##
The default entities and attributes that will be created when uploading the CSV files are as listed below.
| **Entities**  | **Attributes** |
|:--------------|:---------------|
| Campaigns     | Name, Owner, Start Date, End Date, Type, Status, Expected Revenue, Budgeted Cost, Actual Cost, Expected Response Percentage, Number Sent |
| Vendors       | Name, Owner, Category, Gl Account, Email Id, Phone, Mobile Phone, Home Phone, Skype Id, Website, Address Line1, Address Line2, City, Zip Code, State, Country, Address on Map |
| Products      | Name, Image, Owner, Code, Vendor, Is Active, Manufacturer, Category, Sales Start Date, Sales End Date, Support Start Date, Support Expiry Date, Unit Price, Commission Rate, Is Taxable, Usage Unit, Quantity Ordered, Quantity in Stock, Reorder Level, Handler, Quantity in Demand |
| Leads         | Name, Company, Title, Email Id, Phone, Mobile Phone, Home Phone, Skype Id, Website, Address Line1, Address Line2, City, Zip Code, State, Country, Address on Map, Website, Number of Employees, Annual Revenue, Email Opt out, Owner, Status, Source, Industry, Rating, Campaign Source |
| Accounts      | Name, Owner, Account Rating, Account Site, Account Number, Ticker Symbol, Type, Ownership, Industry, Phone, Fax, Website, Number of Employees, Billing Address Line1, Billing Address Line2, Billing City, Billing Zip Code, Billing State, Billing Country, Billing Address on Map, Shipping Address Line1, Shipping Address Line2, Shipping City, Shipping Zip Code, Shipping State, Shipping Country, Shipping Address on Map |
| Contacts      | Name, Email Id, Phone, Mobile Phone, Home Phone, Skype Id, Website, Account, Title, Department, Alternate Email Ids, Assistant Name, Assistant Phone, Reports to, Vendor, Campaign Source, Lead Source, Mailing Address Line1, Mailing Address Line2, Mailing City, Mailing Zip Code, Mailing State, Mailing Country, Mailing Address on Map, Other Address Line1, Other Address Line2, Other City, Other Zip Code, Other State, Other Country, Other Address on Map |
| Opportunities | Name, Owner, Amount, Account, Closing Date, Stage, Type, Probability, Next Step, Expected Revenue, Lead Source, Campaign Source |
| Solutions     | Question, Answer, Owner, Product, Status |
| Cases         | Subject, Product, Owner, Type, Status, Origin, Priority, Reason, Contact, Account, Opportunity, Reported by, Phone, Email Id, Description, Solution |
| Tasks         | Subject, Owner, Due Date, Status, Priority, Lead, Account, Contact, Opportunity, Case, Campaign, Vendor, Product |
| Call Logs     | Subject, Call Type, Call Purpose, Lead, Contact, Owner, Date and Time of Call, Duration of Call, Account, Opportunity, Case, Campaign, Vendor, Product, Call Result, Billing |

Change _Entities_ or _Attributes_ as per your requirement to complete the customization.

Add more users from under _Admin_ > _Users_ > _Add User_ (button) providing a Google Apps or a Google email-id. When your users login into iFreeTools Creator, they will be taken to the your Custom CRM app

Use the feedback form in the application or send a mail to [raj@sahasvat.com](mailto:raj@sahasvat.com) in case you have any queries.