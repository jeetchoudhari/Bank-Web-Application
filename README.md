# Bank-Web-Application
<table><tr><td> <em>Assignment: </em> IS601 Milestone 3 Bank Project</td></tr>
<tr><td> <em>Student: </em> Jeet Nitin Choudhari (jc2494)</td></tr>
<tr><td> <em>Generated: </em> 5/2/2023 3:45:58 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-milestone-3-bank-project/grade/jc2494" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone3 branch</li><li>Create a new markdown file called milestone3.md</li><li>git add/commit/push immediate</li><li>Fill in the below deliverables</li><li>At the end copy the markdown and paste it into milestone3.md</li><li>Add/commit/push the changes to Milestone3</li><li>PR Milestone3 to dev and verify</li><li>PR dev to prod and verify</li><li>Checkout dev locally and pull changes to get ready for Milestone 4</li><li>Submit the direct link to this new milestone3.md file from your GitHub prod branch to Canvas</li></ol><p>Note: Ensure all images appear properly on GitHub and everywhere else. Images are only accepted from dev or prod, not localhost. All website links must be from prod (you can assume/infer this by getting your dev URL and changing dev to prod).</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> User will be able to transfer between their accounts </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of transfer page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235543657-381c3146-013f-44a3-9884-4cbdb2e9cc59.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>&quot;Internal Transfer&quot; heading<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235545422-b7502744-57be-4f95-aa1c-b1d742011d5b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>transfer output<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot showing dropdown values</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235543821-4a8b33e3-299d-4d75-b3c3-992056d39e1d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>account number and current balance as the dropdown text - Account source<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235544241-135fe1ce-5d6c-4bbf-9218-2efe0ef4d21c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>account number and current balance as the dropdown text - Account Destination<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add screenshot showing user can't transfer more funds than they have</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235544083-f73099d2-e493-406f-b2e3-486c083c45ef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>can&#39;t transfer funds than the bank account<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add screenshot showing user can't transfer to the same account</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235544435-a21e2e0c-104c-4cb1-b23c-044dc3c0ef1e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output showing transfer between same acnt not possible - Site<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235544700-c2de1492-f618-42b7-ae04-cd2ba94bc43d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code preventing same account transfer<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add screenshot showing you can't transfer an negative balance</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235544880-c222a0b1-3e4a-4a08-b803-07ca071da41f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output - from website( I have added validator for this) So that no<br>-ve value can be inserted<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235545136-f68fc9c0-b647-43f7-b7e2-dedb76c5cfd6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>CODE ( I have added validator for this in the form) So that<br>no -ve value can be inserted<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add screenshot of the generated transaction history from the db</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235545791-ea870d7e-14b3-44a5-87c2-4da58f3c2fc6.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Row 32 and 33 where id is 36<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 7: </em> Add a screenshot of the Accounts table showing both affected accounts</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235545930-d55905ad-621d-4513-be29-6145a66f8c02.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Transfered from account number 000000000004 to 000000000007<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 8: </em> Briefly explain the code process/flow of a transfer including how the accounts are fetched for the dropdowns</td></tr>
<tr><td> <em>Response:</em> <div>The system fetches all accounts of the current logged-in user. The accounts are<br>passed as a list to the transfermoney page template, where they are used<br>to create a dropdown menu.</div><div>The system fetches the balances of the source and<br>destination accounts. If the source balance is less than the amount to transfer,<br>or if the user is trying to transfer money to the same account<br>or a non-existent account, an error message is displayed.</div><div>The system reduces the amount<br>from the source account balance and adds the amount to the destination account<br>balance. If both of these queries are successful, a new record is inserted<br>into the transactions table. The record includes the source and destination account numbers,<br>the amount transferred, and other details.</div><br></td></tr>
<tr><td> <em>Sub-Task 9: </em> Add pull request(s) url</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/jeetc7/is601-004/pull/42">https://github.com/jeetc7/is601-004/pull/42</a> </td></tr>
<tr><td> <em>Sub-Task 10: </em> Add link to transfer page from heroku</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-jc2494-prod.herokuapp.com/accounts/transfer">https://is601-jc2494-prod.herokuapp.com/accounts/transfer</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Transaction History Page </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of transaction history page showing the new transfer transaction</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235548865-3e9f983e-365b-49d7-978a-300db779cd1a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Transfered from 000000000006 <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshots demonstrating the filters and pagination</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235549167-2abc1cc2-9293-4e9f-80dc-551a7e96dd8f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Account number(000000000005) and date filter applied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235549380-32a937f0-658b-4165-a92c-5f7cddce0a1c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Account number(000000000007) and transaction type = transfer filter applied<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235549572-f86d70a9-41b0-4509-a680-21e8ade2c6ba.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Account number(000000000007) filter<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235551229-a1691e8e-f6b7-40f6-ae2a-abdb02d0e0c2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Pagination output<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how the filters/pagination work</td></tr>
<tr><td> <em>Response:</em> <div>In the Jinja template to display pagination links for a list of transactions.<br>I used pages in which it returns the total number of pages in<br>the list, current_page filter returns the current page number, range returns a list<br>of numbers from 1 to the number of pages.</div><div>The template first checks if<br>there are more than one page. If there are, it displays a navigation<br>bar with</div><div>A link to the previous page, if the current page is not<br>the first page.</div><div>A list of links to each page, with the current page<br>highlighted.</div><div>A link to the next page, if the current page is not the<br>last page.</div><div>We are also using url_for function to generate links to the individual<br>pages. The url_for function takes two arguments: the name of the view function<br>and the values of the parameters that will be passed to the view<br>function. The view function is accounts.transactions and the parameter is the account number.<br></div><br></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add pull request(s) url</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/jeetc7/is601-004/pull/44">https://github.com/jeetc7/is601-004/pull/44</a> </td></tr>
<tr><td> <em>Sub-Task 5: </em> Add link to Transaction History page from heroku</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-jc2494-prod.herokuapp.com/accounts/transactions?acc_number=000000000005">https://is601-jc2494-prod.herokuapp.com/accounts/transactions?acc_number=000000000005</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> User's profile First name and Last name </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the user's profile with the new fields</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235591336-6a8d48a1-c047-45b6-b2fb-558b595ef7e5.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>user&#39;s profile with the new fields<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add pull request(s) url</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/jeetc7/is601-004/pull/45">https://github.com/jeetc7/is601-004/pull/45</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Add link to profile page from heroku</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-jc2494-prod.herokuapp.com/profile">https://is601-jc2494-prod.herokuapp.com/profile</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> User will be able to transfer funds to another user </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the external transfer page with filled in data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235597952-d947d6ae-76ff-429e-8d9c-6d6ce21a63ea.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>external transfer page with filled in data<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235598120-88dde7b5-8cef-4d55-9823-385c916131ce.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>success message<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot showing user can't send more than they have</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235598925-3edad347-95e6-4684-a9c5-a26af6fa70c4.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output from Site <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235599350-0567a8c2-dea6-4c38-90b7-5c9ffd71ac23.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add screenshot showing they can't send a negative amount</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235599498-c1ea2500-9893-492d-8618-c3c19055db74.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added validation in WTF forms in the form class.(No need to check after<br>weather the amount is negative as negative numbers will not be accepted and<br>submitted by the form itself in the front end)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235599751-6063c21a-945a-4ba4-b071-1dc4a6e93dc8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code screenshot off form preventing negative money sending<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add screenshot(s) showing message if a user doesn't exist and/or a destination account wasn't found</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235599972-51efbcbb-4423-4b27-9cc9-2a9fdd26ef90.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>User not found<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235602320-acc9c463-58a8-4717-b319-2e5f3daab63d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add screenshot of the transactions table showing the recorded transfer</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235602590-f8b71773-dc1d-48e5-8476-e73fb97a6fe7.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>transactions table showing the recorded transfer<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 6: </em> Add screenshot(s) showing the updated account balances</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113025/235598381-9111dc67-1fc4-43cb-8373-b3108045116c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Data in table showing the recorded transfer - transferring to acnt no. 000000000015<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 7: </em> Briefly explain the process of looking up the target user's account and the validation logic</td></tr>
<tr><td> <em>Response:</em> <div>When a user enters a destination account number, the system first runs a<br>SELECT query to search for that account in the accounts table. If the<br>account is found, the system then transfers the funds from the user's account<br>to the destination account. If the account is not found, the system displays<br>an error message.</div><div><br></div><div>The last four digits of the account number are taken from<br>the accounts table. The last name of the user is fetched from the<br>users table. If the user's last name exists in the users table, the<br>system then runs a SELECT query with a WHERE clause to filter the<br>results based on the user's last name. The results of the SELECT query<br>are then updated to the appropriate table.</div><br></td></tr>
<tr><td> <em>Sub-Task 8: </em> Add pull request(s) url</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/jeetc7/is601-004/pull/47">https://github.com/jeetc7/is601-004/pull/47</a> </td></tr>
<tr><td> <em>Sub-Task 9: </em> Add link to external transfer page from heroku</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://is601-jc2494-prod.herokuapp.com/accounts/ext_transfer">https://is601-jc2494-prod.herokuapp.com/accounts/ext_transfer</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe any issues and learnings throughout this milestone</td></tr>
<tr><td> <em>Response:</em> <div>Learnings<br>1)I have learned to pass data from various pages like via arguments or<br>using</div><div>session data and to link the frontend with the actual code.</div><div>2)Learned to use<br>WTF forms, adding validations and backed validation for input fields.</div><div>3) Learned to implement<br>Sql queries in actual code.</div><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-milestone-3-bank-project/grade/jc2494" target="_blank">Grading</a></td></tr></table>
