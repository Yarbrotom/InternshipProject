# InternshipProject
This repo contains information on the code I wrote for my internship with Prosper Consulting Inc.


* The first user story I worked on indicated that a non admin user on the website was able to access a page that they shouldn't if they were to manually navigate to it through the url.
The website was already setup to hide the navigation link to that page for non Admin users so my task was simply to prevent someone from navigating to a "Create Productions" page manually.
 
  * The [**Restrict Access to Productions**](https://github.com/Yarbrotom/InternshipProject/blob/master/Restrict%20Access%20to%20Productions.PNG) image shows the code that I added to the Controller to keep a non admin from unauthorized access to the "Create Productions Page".  
&nbsp;
&nbsp;
&nbsp;




* The second user story I worked on was to add cast member information to a Photo page. The instructions were to allow the page to display what object was using that particular photo then allow the user to view or edit that dependency.  I was additionally asked to add links to the Photo page for any dependency to allow the user to view that dependency or edit it. 

  * I started by adding a list to collect cast member data to the view model for dependencies the code can be found in [**this image**](https://github.com/Yarbrotom/InternshipProject/blob/master/PhotoDependenciesVm.PNG).
  
  * Next I added the logic to collect cast member information and add it to the list in the [**photo controller**](https://github.com/Yarbrotom/InternshipProject/blob/master/PhotoController.PNG).  Additionally I added documentation comments because this code would be reused again later.

  * After that I [**moved**](https://github.com/Yarbrotom/InternshipProject/blob/master/PhotoEditMove.PNG) and [**re-factored**](https://github.com/Yarbrotom/InternshipProject/blob/master/PhotoEditNewCode.PNG) the code on the views that displayed any dependency for the photo and added pill buttons to navigate to the edit and details pages for that dependency.  Here is a look at what the page looked like [**before**](https://github.com/Yarbrotom/InternshipProject/blob/master/old%20edit.PNG) and [**after**](https://github.com/Yarbrotom/InternshipProject/blob/master/phot_edit_dependencies.PNG).

