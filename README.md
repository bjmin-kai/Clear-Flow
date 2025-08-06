# Clear-Flow
A power automate workflow that automatically extracts email attachments, uses copilot to scrape information, then uploads that information into a structured excel file.

There are key connectors that are necessary for this workflow to operate. This workflow needs connection to outlook 365, one drive, and excel.

In one drive it is necessary that a few things are set up before use. First is a main folder to house your attachment and excel file libraries. The main folder should be titled Order Entry Workflow. Two folders inside of this main folder should be titled "Email Attachments", and "Account overview". Alternatively you can edit the names to better fit your needs within the workflow.

Lastly, it is important that you create a templeted excel file that can be used when the excel file needs to be created. This excel file is titled "Customer_Dashboard_Template.xlsx" and should be located in your Account overview folder.
