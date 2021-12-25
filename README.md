# Salesforce-Full-Course
Day-1 20-12-21
1.Cloud
2.Cloud Computing
3.Types of Cloud

1.What is cloud?
     Cloud is a place to store any kind of data like audio,video and documents.It refers software and services that run on internet instead of locally on our system.

2.what is cloud computing?
     Cloud computing is on demand network services provide to IT
Industries via pay-per-use. Instead of  buying and managing the physical data centers, the technology provided by the cloud such as server,networ and storage…etc,.

3.Types of cloud:
  Iaas→Infrastructure as a service.
     In this we need to build a infrastructure as our wish but network,server and storage managed by vendors.
  
  Paas→Platform as a service.
     In this, we need to make platform and we can do anything as what we wish like creating application and manipulating.
  
  Saas→Software as a service.
     In this,we just getting services don’t need to build infrastructure or create platform those are already managed by vendors we are just going to access the services. 
     
     ********************************************************************************************************************************************************************

     Day -2 21/12/2021

1.CRM
2.Salesforce 
3.TrailHead 
4.Developer Console


1.CRM-Customer Relationship Management
    It improves the relatio between customers and keep them in touch, Update news about the product to the customers.

2.SalesForce– 1999, CEO→marc benioff
  It is a business platform to sell,service and explore the products, All the data store safely in the cloud.

3.TrailHead→Place to study about salesforce.

4.Devloper console→create salesforce account for individuals.

********************************************************************************************************************************************************************

Day-3 22/12/21

OBJECT IN SALESFORCE:
  Objects:
     Collection of fields like database in salesforce. There are two types..

1.Standard object
   Already pre built in salesforce platform eg:Accounts,contacts.We can modify but can’t delete. 

2.Custom object
   We can customize the object depends our wish. Custom object field names end with ‘_c’ we can identify the custom object with this indication.

How to create custom object:
1.In the trailhead create and launch playground it takes us to salesfoce developer platform.
2.And go to the set up “gear simple” of top right in menu bar
3.Then click object manager and give new custom you can see such as below.


4.Give the details..
5.After create object manager we need to create fields so,
6.Do the 2 step and select the object  you created by quick find search bar.
7.In selected object click the fields and relationship and give new to add more.


8.After you did all work in the custom object you need to add in front end so,
9.Go to set up “gear simple” then search tab in  quick find.
10.Into the tab give custom object tab new thats it.
11.Now you can get it from the quick search in front end.
********************************************************************************************************************************************************************
Day-4 23/12/21

1.Lightning app
   To create lightning app,Click set up gear icon and search app and click app manager give name select include object home object is mandatory and give next thats it.


2.Picklist 
  It is a datatype in an object,In picklist we are going to select a specific item that why its called as a picklist.

  To create picklist 
   i.Click set up gear icon go to object manager select your object and go to fields and relationship 
   ii.Then select picklist datatype and give name select non global and give values and save it.


3.Multi picklist
   Same as picklist but here we are going to select multiple items .

  To create multi picklist
     i.Click set up gear icon go to object manager select your object and go to fields and relationship 
      ii.Then select multi picklist datatype and give name select non global and give values and save it.


4.Global picklist
    It is a common field for many objects.

   To create global value picklist
      i.Click set up gear icon and go to home search pick list value set and click new  then give label and details and save it.


5.Field dependency
   Here in an object one field depend with another the field.
One field is called control field another one is called dependent field.

   To create Field dependency
        i.Click set up gear icon go to object manager select your object and go to fields and relationship 
        ii.Click field dependency filed in right side top.
        iii.Then select control and dependent field.
        iv.Include respective values in dependent field after that save it.
*******************************************************************************************************************************************************************

Day -5 25/12/21

Relations in salesforce 
  Relate one object to another object to avoid redundancy.
Two types in salesforce
  1.Mark details
  2.Look up

1.Mark details
  It is a Many–One relationship, 
 Should be Created in many field object 
 When creating Mark details its field will be required ever
 Roll up summary available to master object

   Roll  up summary
     It shows minimal information which gather from child object.
*******************************************************************************************************************************************************************


