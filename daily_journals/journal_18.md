Start Date: June 11, 2024
End Date: September 18, 2024
Day 18: June 28, 2024

Today's Progress:

    1. Learning With Nature
        How to exclude fields in database query - Only return notes, images, and documents from lesson_resources?
    2. Start Think Python Chapter 5 exercises



Challenges:

    Learning With Nature
    After attempting to join database query results with chain(), the following error occurred:
        ...
        data_chain = chain(lesson, lesson_resources)
            print('Data Chain:', data_chain)
            return JsonResponse(list(data_chain)) # TypeError: 'Lesson' object is not iterable

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit   
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature

Notes:

    Learning With Nature: Future Development 

    When a user requests to save a lesson, check the database to make sure that lesson hasn't already been saved by the user. Display message if this condition is true.

    When a user clicks on the title (which is a link) of a saved lesson, display the complete lesson stored in the database with all edits.

    When a user clicks to edit a saved lesson that has already been updated, display the form with the current data for the form fields. 

    At present, if a user makes a request and proceeds to make another request without clicking the 'logo' or 'Find Parks by State', the visible divs do not clear and new content is added below. How to clear a page when a new request is made without deleting or removing divs or refreshing the page. The user should not have to go back to the beginning to clear the page for a fresh start. 