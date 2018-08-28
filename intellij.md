## JPA PersistenceCapable not found on random entities
Problem:
Keeps giving that error when attempting Intellijbuild
Cause:
The problem is something cached in the .idea folder
Solution 
1. firstly try **Invalidate caches / Restart** from main menu
2. still broken, then try **Close Project** and re-importing (making sure Gradle is selected)
3. still broken, delete .idea folder completely and re-import project


