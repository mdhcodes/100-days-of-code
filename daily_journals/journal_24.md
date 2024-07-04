Start Date: June 11, 2024
End Date: September 18, 2024
Day 24: July 4, 2024

Today's Progress:

    1. Update Lesson model and return values to include hasResources Boolean field. This field will
       be true if the user has saved Resources for this lesson.
    
    2. When a lesson is edited (hasResources), the 'Edit' button is removed and the 'Update'        
       button is put in its place. In this way, an edited lesson will have one object in Resources that can be updated multiple times without creating new entries for the same lesson.

    3. Comment get_edit_form function in views.py and edit_lesson function in learning.js. The
       program is building the form dynamically and not accessing forms.py. 

Challenges:  

    Create update form and display the current values for each of the following fields - notes, image, and doc_upload.

    Some of the images from NPS are not loading. Error in console 'Image corrupt or truncated'.
    Messages should slowly fade away. 

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit   
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature  

Notes:

    Learning With Nature: Future Development     

    At present, if a user makes a request and proceeds to make another request without clicking the 'logo' or 'Find Parks by State', the visible divs do not clear and new content is added below. How to clear a page when a new request is made without deleting or removing divs or refreshing the page. The user should not have to go back to the beginning to clear the page for a fresh start. 

    Remove lessons app that is not being used in the program.

    Clicking on the username should load the user's profile information allowing user to change their password.

    Option for user to upload multiple images and documents.