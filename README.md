## **TASK**
*Analyze part of the specification and write test cases for it (test cases created in QASE)*
___
***Specification:***

+ When server response 403 to api/v1/getAnswer a new toaster with error deatails should appear
+ First row, title: Automatching by Asset Name wasn't finished
+ Second row: Please proceed with the manual match, or create a Service Now ticket. ServiceNow - link to the ServiceNow system (to create a new ticket) https://delo/tickets/new
+ Third row: Date and time, when the synchronization has started 
+ The standard "Close" button
___
## **ANSWER**
:white_check_mark: **Questions about the specification**
1. Does the link “ServiceNow” open in new tabs or on the current page?
2. What format is the date and time displayed?
3. Where is the button “close” exactly situated (on the right, left or center of the
toaster)?
4. What color is the button “close”? What fonts are used?
5. Whatdoestheuserseeonthescreenafterclosingthetoaster?Wheredoesit
redirect us after closing the toaster?
6. What happens to the background of the application when the toaster
appears?

:white_check_mark: **Taste Cases created in QASE. You can see them in more detail on the screenshots in the directory [Test Cases For The Toaster](https://github.com/qasvitlana/TestCases_ForTheToaster/tree/main/Test%20cases%20for%20a%20toaster)**
