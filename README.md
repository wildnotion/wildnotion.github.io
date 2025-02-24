wildnotion.github.io
SNHU CS-499 C-1

**Original CS360 Project:** Non-functional, with many comments only stating **"FIXME"** or **"Please add the correct logic."**

**Update_01:** A simple, yet functional two-tier SQLite database with login and cache creation.
           Addition of comments on algorithms, debug logs for tracking, and better format consistency.  

TODO:
- Implementation of the inventory, the third tier of the database, connecting items to each cache.
- Adding images for each cache and each item while updating each layout's user interface (UI).

**Informal Code Review:** https://youtu.be/Qr_exohsXqc
           The TODO's in this README were constructed after performing a code review on the the non-functioning **Original**, 
           and the functional **Update_01**. The review starts with coverage on the **Original** before moving onto the updated build
           I created for a better artifact enhancement strategy and additional code review reference points.
                
**Update_02:** A functional three-tier SQLite database with login, cache creation, and adding items to a cache's inventory.
           Implementation of a grid image selection for choosing cache and item images.
           Continued addition of comments on algorithms, debug logs for tracking, and better format consistency.  

TODO:
- Addition of a permissions activity to allow access of GPS sensor.
- Addition of a GPS manager class to obtain GPS coordinates from sensor.

**Update_03:** A functional three-tier SQLite database holding usernames and passwords, cache details including latitude
           and longitude (while location services permissions are granted), and specific item information per cache.
           including login, cache creation, and adding items to an inventory.
           Reduction of debug logs to clean up source code.  

TODO:
- Addition of an encryption manager to secure all stored data.
- Addition of user interface elements such as borders and art to organize space.
- Clean up source code.

**Update_04:** A functional three-tier SQLite database using AES-256 encryption for stored usernames, passwords, cache
             details, and item details. While location services permissions are granted, allows acquisition of GPS
             coordinates. Previous debug logs removed with most runtime errors currently being ignored in the try/catch
             blocks if they occur. 

FUTURE UPDATES: 
- Addition of user interface elements such as borders and art to organize space.
- Addition of user interface functionality such as editing the count for items and the GPS location for caches. 
- Localization into other languages, such as Japanese and Spanish.

**StashCache_Beta.apk:** The signed Android Package (APK) file generated using **Update_04** for testing and feedback.
