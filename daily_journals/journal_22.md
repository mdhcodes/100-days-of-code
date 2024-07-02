Start Date: June 11, 2024
End Date: September 18, 2024
Day 22: July 2, 2024

Today's Progress:

    1. Learning With Nature:
        An email address is no longer required to register. 
        https://stackoverflow.com/questions/48448563/my-password-is-stored-inside-the-email-field-in-django-admin
            "The second argument of the create_user method is email."  
            user = User.objects.create_user(username, email, password)  
            "Fix - Change code to pass password as a keyword argument."  
            user = User.objects.create_user(username, password=password)  

        Add npid CharField to the Lesson class model to store the original National Park Service lesson ID. This ID will be used to check if a lesson has already been saved by the user eliminating duplicates in the database.

        When a user tries to save a lesson, the database is checked to make sure that lesson doesn't already exist or wasn't already saved by the user. Display message if this condition is true.


Challenges:

    The message alerting the user that the lesson is already saved does not display on screen when this condition is true.

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit  
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature  

Notes:

    Learning With Nature: Future Development 

    When a user clicks on the title (which is a link) of a saved lesson, display the complete lesson stored in the database with all edits.

    When a user clicks to edit a saved lesson that has already been updated, display the form with the current data for the form fields. 

    At present, if a user makes a request and proceeds to make another request without clicking the 'logo' or 'Find Parks by State', the visible divs do not clear and new content is added below. How to clear a page when a new request is made without deleting or removing divs or refreshing the page. The user should not have to go back to the beginning to clear the page for a fresh start. 

    Remove lessons app that is not being used in the program.

    Clicking on the username should load the user's profile information allowing user to change their password.