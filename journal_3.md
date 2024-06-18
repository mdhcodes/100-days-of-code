Start Date: June 11, 2024  
End Date: September 18, 2024  
Day 3: June 13, 2024  

Today's Progress:  

    Prepare to access data from the Smithsonian database  
    
    1. Get Smithsonian API Key and add it to .env file  

    https://medium.com/django-unleashed/securing-django-applications-best-practices-for-managing-secret-keys-and-environment-variables-f10f5a53490b  

    https://stackoverflow.com/questions/15209978/where-to-store-secret-keys-django  

    https://docs.djangoproject.com/en/5.0/ref/settings/#std-setting-SECRET_KEY  

    2. Install python-dotenv module in virtual environment - pip install python-dotenv  

    3. Add the following to settings.py  
     
    from dotenv import load_dotenv  
    load_dotenv()  
    import os  

    4. Add virtualVisit app to settings.py INSTALLED_APPS  

    5. Add path to include('virtualVisit.urls) in urls.py in the museums project directory  

    6. Add urls.py to museums project app virtualVisit  

    7. Add templates/virtualVisit - index.html and layout.html  

    8. Add static folder to virtualVisit app - styles.css and museums.js  

    9. Start Project - python manage.py runserver  

    10. Use Postman to analyze the data gathered from the Smithsonian API and find the paths to extract artifacts I'd like to use in my project.  

    SI API DOCS - https://edan.si.edu/openaccess/apidocs/  

    https://www.postman.com/opamcurators/workspace/open-access-museums/request/1501710-a22477b3-72ff-4781-b165-5079183cc0a5  

    GET Request: https://api.si.edu/openaccess/api/v1.0/category/art_design/search?api_key={{si_api_key}}&q=birds&start=0&rows=10  

    JSON Response (possible paths to art resources):  
        "record_link":  
        "online_media": {  
            "media": [  
                {  
                    "content": link to image  
                    "thumbnail": link to image  
                    "altTextAccessibility":  
                    "resources": [  
                        "url": link for image - automatically downloads to computer when clicked  
                    ]  
                }  
            ]  
        }  
 
    11. Research 3D rendering options  
        Carnegie Mansion - exterior and interior   
        https://www.si.edu/object/3d/carnegie-mansion-exterior:5010a19c-2f7f-4325-b43c-bebe6711b473  
        https://www.si.edu/object/3d/main-floor:bf46d303-9620-466b-8ea7-5f86f1541a1f  
        https://www.si.edu/object/3d/2nd-floor:6c927e24-7dfc-49f3-ad37-e62843875dd2  
        https://www.si.edu/object/3d/3rd-floor:29702a91-7f25-4012-855c-1fb0f39afbb7  

        three.js - https://threejs.org/  

    12. Read Think Python  
        // - Integer division also called floor division because it rounds down.  
        ** - exponent - raises a number to a power  
        ^ - XOR is a bitwise operator  

Challenges:  

    Determining the best approach to render a 3D space.   

Link(s) to Work:  

    [Virtual Museum Visit]https://github.com/mdhcodes/virtual-museum-visit  

Notes:  

    [Any additional notes]  