<h1>Making An Admin Account</h1>

<h2>It's a good security practice to use a separate admin account to prevent unwanted lateral movement.</h2>

1. Navigate to 'Active Directory Users and Computers' by clicking the Start icon, selecting 'Windows Administrative Tools,' and then choosing 'Active Directory Users and Computers.'
<img src="" height="80%" width="80%"/>

2. To create a space for our admin account within an Organizational Unit (OU), right-click on 'YourDomain.com,' go to 'New,' and select 'Organizational Unit.'
<img src="" height="80%" width="80%"/>

3. Name the new OU 'Admin.'
<img src="" height="80%" width="80%"/>

4. Now that the 'Admin' OU is created, let's add an admin user account. Right-click on the new OU, go to 'New,' and select 'User.'
<img src="" height="80%" width="80%"/>

5. Name the user account as you like. For the user logon name, it's a good practice to use "a-" before the username to indicate it's an admin account.
<img src="" height="80%" width="80%"/>

6. Set a password for the account. Although it's not recommended for security reasons, for the sake of this lab, uncheck the 'User must change password at the next logon' and check 'Password never expires.'
<img src="" height="80%" width="80%"/>

7. Click 'Finish.'
<img src="" height="80%" width="80%"/>

8. You should now see the new account within the 'Admin' OU.
<img src="" height="80%" width="80%"/>

9. Next, assign the new user account to the admin level. Right-click on the user and select 'Properties.'
<img src="" height="80%" width="80%"/>

10. In the 'Member Of' tab, click 'Add.'
<img src="" height="80%" width="80%"/>

11. Type 'Domain Admin' and click 'OK.'
<img src="" height="80%" width="80%"/>

12. Click 'Apply' and then 'OK.'
<img src="" height="80%" width="80%"/>

13. To use the new account, log out of the current admin account and log in to the new account you've just created by clicking 'Other users' in the bottom right."
<img src="" height="80%" width="80%"/>
