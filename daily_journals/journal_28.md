Start Date: June 11, 2024
End Date: September 18, 2024
Day 28: July 8, 2024

Today's Progress:

    1. Learning With Nature:
        
        Create functionality to update lesson Resources within the edit function. 
        If Lesson.hasResources == True, update the specified Resources entry. 
        If Lesson.hasResources == False, create a new Resources entry.
        
        The 'Saved Lessons' link leads to a list of lesson titles. Clicking on those titles leads to the display of a complete lesson. Clicking the 'Complete Lesson' URL leads to the NPS lesson plan.

        The #complete-lesson div is hidden as needed and complete lessons are displayed with park learning resources as well.

        TODO: Save only the one park code that applies to the specified lesson plan - must repair Lesson model and database. At present, I save the full array of park codes and access the first code.

Challenges:  

    Learning With Nature: 
        Some of the images from NPS are not loading. Error in console 'Image corrupt or truncated'.
        Messages should slowly fade away. (Virginia)  

        Find Parks by State
            Click a state
            Click a park link
            Click 'Saved Lessons'
                Click a lesson title - should display only current Park Learning Links (If a 'Park Link' search occurred before clicking on 'Saved Lessons' and then clicking on a 'Saved Lesson Title', the #park-learning div is not cleared and two results are displayed.)

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit      
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature 

Notes:

    Learning With Nature: Future Development     

    At present, if a user makes a request and proceeds to make another request without clicking the 'logo' or 'Find Parks by State', the visible divs do not clear and new content is added below. How to clear a page when a new request is made without deleting or removing divs or refreshing the page. The user should not have to go back to the beginning to clear the page for a fresh start. 

    Remove lessons app that is not being used in the program.

    Clicking on the username should load the user's profile information allowing user to change their password.

    Option for user to upload multiple images and documents.

    Nature Walk Website: Run program in the terminal via ... > node index.js