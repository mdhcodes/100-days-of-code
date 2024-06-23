Start Date: June 11, 2024
End Date: September 18, 2024
Day 13: June 23, 2024

Today's Progress:

    1. Learning With Nature:
        Solved the issues with passing form data to views.py and the database from JavaScript. The solution is found here: https://developer.mozilla.org/en-US/docs/Web/API/FormData.

    > The FormData interface provides a way to construct a set of key/value pairs representing  
    > form fields and their values, which can be sent using the fetch() method. It uses the same  
    > format a form would use if the encoding type were set to "multipart/form-data".  
    
    I couldn't use fetch() with JSON.stringify because it passed an empty object to views.py. The errors 'No KeyError' and 'TypeError: object of type 'NoneType' has no len()' would occur.

    I'm now able to access the data from a saved lesson, display it, and add additional content such as text and files (images and documents) essentially editing the lesson and saving the changes. 

Challenges:

    Overcame a challenge - I can edit a lesson and save the changes to the database.

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature

Notes:

    [Any additional notes]