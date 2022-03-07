# Adobe-over-Edge
Wrests File Type Association back from edge to Adobe Acrobat. 

Plagued me forever at work, two users would have it reset seemingly randomly. I noticed in the logs it was checking the hash of the file, usually after week of Patch Tuesday, and if it didn't like the hash of Acrobat (wasn't the newest or something) it was saying "UNSAFE!!!!!! I'll take over" and resetting association. Every time th euser logons this will check the FTA and set it back.  
