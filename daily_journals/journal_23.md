Start Date: June 11, 2024
End Date: September 18, 2024
Day 23: July 3, 2024

Today's Progress:

    1. Learning With Nature:  
        A message alerting users that a lesson they're trying to save is already saved displays on screen when this condition is true. (If a message is sent via context and render() it appears on the screen. When a message is sent via JsonResponse() it appears in the JS console. I can access the JsonResponse with result.message in JavaScript to display on screen.)

        I updated all messages so one div element accepts all JsonResponse messages.

        When a user clicks on the title link of a saved lesson, the complete lesson stored in the database with all resources is displayed.

Challenges:

    1. When a user clicks to edit a saved lesson that has already been edited, display the form  
       with the current data for the form fields.   
       Update views.py function get_lesson_to_edit and JavaScript function get_lesson.  

       get_lesson_to_edit
       Determine if a lesson has already been edited.
            if edited
                update existing resources - don't create a new entry.
            else
                add new resources

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