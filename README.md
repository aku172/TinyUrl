# TinyUrl
TinyUrl problem statement

1. The system (app) should take an URL string as input, return a generated “shortened” URL.
2. The app should be able to track the users who try to access the shortened URL. For example, if I generate a shortened URL for a file that I have on AWS S3, and I share it with 10 people, the app should be able to track that who and when accessed the shortened URL that was generated.
3. Any generated URL should expire after 72 hours, in which case, if an attempt is made to access the same, it should notify the person who generated the URL in the first place to generate a new one.

Notes:
1. Input URL would have the base URL along with any applicable path variables and request parameters.
2. Think big, how would your system scale with billions of combinations of input URL strings, and high transaction rates?
3. Feel free to use any technology that you think would suit the case.
4. Unit tests would get you brownie points, but are not mandatory.
