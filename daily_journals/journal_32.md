Start Date: June 11, 2024
End Date: September 18, 2024
Day 32: July 12, 2024

Today's Progress:

    1. Learning With Nature:
        Begin to activate the 'Hello, username' link. Clicking on the username will load the user's profile information allowing the user to change their password if desired.

        PROBLEMS: 
        1. When the 'Find Parks by State' button is clicked, the Edit Lesson text flashes on the screen which is not desired. 
        2. When dynamically created, the 'Edit Lesson' and 'Update Lesson' h3 titles are displayed at the end/bottom of the page after all other text has been posted. 

        SOLUTION: Place h3 heading element in index.html without setting the innerHTML. Update the innerHTML of the element (edit-lesson-h3) dynamically.

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