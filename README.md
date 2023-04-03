<h1>Manually adding users to active directory</h1>

<h2>Description</h2>
In this lab we're going to walk through how to create users in active directory using Oracle Virtual box. Configuring and running this lab has been done in the Active Directory lab previousely created.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Server 2019</b>

<h2>Walk-through:</h2>

<h3><p align="center">
1. Manually adding users:</h3> <br/>

First, open the domain controller (DC) -> Navigate to the server manager -> select local server<br/>
Next select tools in the right hand corner -> select "Active Directory users and computers -> Select the drop down menu of the domain ( created in the Active directory lab) -> select users<br/><br/>

![users folder](https://user-images.githubusercontent.com/129562058/229324885-4d08c0c9-ba02-46ed-84e9-d33b08c86eff.png)<br/><br/>

From here right click on a blank space within the users folder -> New -> user<br/><br/>

![new---user](https://user-images.githubusercontent.com/129562058/229324937-c166733d-7f63-4bbb-8a0f-050c65378257.png)<br/><br/>

A dialog box will pop up prompting you to fill out the users information (first name, last name, and username) -> next a dialog box will pop up promting you to create a password for the user.<br/><br/>

![dsfadfsaf](https://user-images.githubusercontent.com/129562058/229325357-d0b6acdc-9a53-43b8-8079-36da6033fb15.png)<br/><br/>

Next to check if the user has been added to the domain right click the newly created user located in the user folder -> select "member of"<br/><br/>

: This section should show that the newly created user is a member of the domain and has been given access acordingly<br/><br/>

![johndoe](https://user-images.githubusercontent.com/129562058/229325215-b2c85737-e9bc-4eb8-9c10-cf9c464a8021.png)
