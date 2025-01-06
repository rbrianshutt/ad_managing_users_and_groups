<h1>Active Directory - Managing Users and Groups</h1>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/active-directory.png)

<h2>Description</h2>
Manage users and groups using Active Directory.  
<br />

<h2>Program walk-through:</h2>


- <b>Installed and configured Active Directory</b>

<br/>
<b>Open the Active Directory Administrative Center (ADAC).  You can pull it up by typing in "active directory" in the Windows search menu.</b>
<br/>
<br/>
 
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/adac.PNG)
<br />
<br />
<b>To add a new user, double click on the Users entry to see the list of users and groups.  Go to New under Users, then click User</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/new_user.PNG)
<br />
<br />
<b>Create a user named Alex with a username alex.  Fill in the mandatory fields indicated by the red star.</b>  
<br/>
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/create_user_alex.PNG)
<br />
<br />
<b>We have an account for Alex, but we need to enable it.</b>  
<br/>
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/example(local)users.PNG)
<br />
<br />
<b>If we try to right click and enable a newly created account we will get an error message.  We need to set the password before an account can be enabled.</b> 
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/failed_to_enable_account_alex.PNG)
<br />
<br />
<b>Set the password by clicking on Reset Password under Tasks on the right hand side of the screen.</b>   
<br/>
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/enable_alex.PNG)
<br />
<br />
<b>Enter and confirm the password.  Make sure the "User must change password at next logon" is checked.</b>  
<br/>
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/reset_password.PNG)
<br />
<br />
<b>To add a new group, Go under Tasks, look under Users, then Group.</b>   
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/new_user.PNG)
<br />
<br />
<b>Create a new group called Python Developers.  Enter in the required fields.  Press OK.</b> 
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/create_group.PNG)
<br />
<br />
<b>Right click on Python Developers and click "Add to another group".</b> 
<br/>
<b>We add this group to an existing group called Developers.  We can verify Developers is a valid group by clicking on Check Names.</b>
<br/>
<br/>
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/add_to_group_developers.PNG)
<br />
<br />
<b>Double click Python Developers from the list.  This allows us to edit the group.  Lets look at the Members section on the left.</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/Python_developers_add_member.PNG)
<br />
<br />
<b>We can add or remove a user by clicking on the Members link.  We add our new user Alex to the Python Developers group.</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/add_alex_python_developers.PNG)

<b>We want to remove Alosha from the Java Developers group and add her to the Python Developers group.  We click on the Members Of link on the left.</b>
<br /
![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/alosha_remove_java.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/alosha_add_python_developers.PNG)
<br />
<br />
<b>text</b>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/group_policy_management.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/create_gpo_in_this_domain.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/new_wallpaper.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/edit_wallpaper.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/desktop_wallpaper_editor.PNG)
<br />
<br />
<b>text</b>
<br/>

![](https://github.com/rbrianshutt/ad_managing_users_and_groups/blob/main/Google%20IT%20Support%20Active%20Directory/enable_wallpaper.PNG)
<br />
<br />
<b>text</b>
<br/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
