Start Date: June 11, 2024
End Date: 
Day 37: July 29, 2024

Today's Progress:

    1. Read Think Python - Review Chapter 5 Conditionals and Recursion exercises.  
    2. Learning With Nature:
        Add click event listeners to the buttons that prompt users to change their username or password if desired. Add change_username() and change_password() functions. After running these functions, the following error occurred: JSONDecodeError.  
        
Challenges:

    Learning With Nature: 

        Error to diagnose:
        JSONDecodeError at /update_profile
        Expecting value: line 1 column 1 (char 0)
        Exception Type: JSONDecodeError
        Exception Value: Expecting value: line 1 column 1 (char 0)
        Raised during: 	parks.views.update_profile  

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