Start Date: June 11, 2024
End Date: 
Day 43: August 8, 2024

Today's Progress:

    1. Learning With Nature:
        Begin to implement the gradual fading of the success alert after a lesson is edited or when any success alert is visible.
        
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

    Option for user to upload multiple images and documents.

    Nature Walk Website: Run program in the terminal via ... > node index.js

    After saving a lesson, the success alert remains visible and the page does not change. 
        Gradually fade away the success alert.
        Change 'Save' button to saved. (Remove alert 'This lesson is already saved' and option to save again.)
        Display newly saved lesson.

    After update/reset username,        
        Display an alert that confirms the username was updated.
        Display ?

    After update/reset password, user is automatically logged out when index.html is requested.       
        Display an alert that confirms the password was updated.
        Display ?