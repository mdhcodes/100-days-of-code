Start Date: June 11, 2024
End Date: September 18, 2024
Day 19: June 29, 2024

Today's Progress:

    1. Learning With Nature
        I used .values() to return specific field name values from Resources
        https://docs.djangoproject.com/en/5.0/ref/models/querysets/#values - "... specify field names to which the SELECT should be limited."
        
        lesson_resources = Resources.objects.filter(pk=resource_id).values('notes', 'image', 'doc_upload')  

Challenges:    

    Learning With Nature
    The following errors continue to persist. 
        - TypeError: 'list' object is not callable  
        - AttributeError: 'QuerySet' object has no attribute 'serialize'  
        - TypeError: 'Lesson' object is not iterable  
        
    In addition, I was unable to join QuerySets via chain or union to pass one QuerySet to JsonResponse().

Link(s) to Work:

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit  
    [Learning With Nature]https://github.com/mdhcodes/learning-with-nature  

Notes:

    Learning With Nature: Future Development 

    When a user requests to save a lesson, check the database to make sure that lesson hasn't already been saved by the user. Display message if this condition is true.

    When a user clicks on the title (which is a link) of a saved lesson, display the complete lesson stored in the database with all edits.

    When a user clicks to edit a saved lesson that has already been updated, display the form with the current data for the form fields. 

    At present, if a user makes a request and proceeds to make another request without clicking the 'logo' or 'Find Parks by State', the visible divs do not clear and new content is added below. How to clear a page when a new request is made without deleting or removing divs or refreshing the page. The user should not have to go back to the beginning to clear the page for a fresh start. 