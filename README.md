# E-Commerce-data-manipulation-via-RPA
E-commerce data manipulation using RPA is an automation project that will produce the various book details using ISBN number to clients via e-mail. When we search for a particular book using ISBN number in any e-commerce website, the result is not ready for consumption and is not clearly formatted. ISBN refers to International Standard Book Number. 
           This project enables various E-Commerce websites to reap loads of benefits from the RPA software robots as these kind of activities can be fully automated without the intervention of any human being at all.  It reduces the time and effort required to drill down the relevant book information and collates the automated results in excel which is easy to consume, visualize and understand by the clients. It also automates the mail that is sent by the clients and saves the attachment of input files required for the project. Atlast, the business file which is generated is sent via mail to the clients using RPA. 


~Module Splitup

Module 1: Input Business File                [Sridhar R]
Module 2: Search the required ISBN number    [Swathika G]
Module 3: Web manipulation and extraction    [Swathika G]
Module 4: Business file report generation    [Swathika G]
Module 5: File transfer via e-mail           [Yeesha Sharookhan S] 

Task Splitup

Input Business File

1) Receive the mail with the input files.
2) Fetch the attachments in the mail using IMAP protocol with the required properties.
     
Search the required ISBN number

1) Open the browser and type the E-Commerce website link(Amazon.in)
2) Check if there is any user account logged in.
3) If logged in, Sign out from the account.
4) Fetch the ISBN numbers from the input files(PDF or Excel).


Web manipulation and extraction

1) Type the ISBN number in the search bar.
2) The data is extracted from the screen using screen scraping.
3) Similarly, the data is extracted for all the ISBN numbers.

Business file report generation 

1) The data extracted is splitted using various VB commands.
2) The data is then assigned to the respective variables which are stored in a datatable.
3) An excel sheet is created from the datatable values.
4) Thus, the business file is generated.

File transfer via e-mail

1) An input excel file of client details such as name and mail_id must be created.
2) An input notepad file is created with a default text template/format  which is sent as body to the mail.
3) The business file is then sent using the SMTP protocol with the given requried properties.

~Advantages over existing methods

1) The results of  E-Commerce search using RPA are in well documented format. 
2) Time consumption is reduced.
3) The automated results will be produced in excel format which is easy to visualize and understand.
4) Minimal man power consumption. 
5) Computational errors and mistakes are minimized. 

~Future Enhancements

1) The initial data which is not in documented form can be converted to Business file and can be exported via mail to required customer.
2) The resultant excel sheet can be uploaded to moodle or any other educational website which is useful for the reference of students.

~Team members: 
1) Sridhar R                711715104058
2) Swathika G               711715104065
3) Yeesha sharookhan S      711715104308

Department Of Computer Science and Engineeering
