In OrangeHRM link (https://opensource-demo.orangehrmlive.com/web/index.php/auth/login) only one set of valid username and password exists (Username : Admin, Password : admin123). 
Since in the task, we are asked to use five set of user details, I have used one valid user details and remaining four user credentials that I have used are random. That is the reason for one test passing and remaining four test cases failing. Since it cannot login with wrong credentials, in assert statement the test case fails as it does not get logged in.
Kindly advise.
