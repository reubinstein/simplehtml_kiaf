# This a Simple (suposed to be) one page website
> The website should be interactive. The main purporse is that when user "A" enters a text ,
> an image will be generated base upon that text, then an image will be displayed on the user' platform.
> The could be more than one user, but only one user is able to generate an image at a time. Meaning
> when user "A" is using, User "B" should be told that the current resources of image generation are
> being used by someone else.(here a loading screen or UI should be put in place to emphasize that.

# Features
1. To use the system, the user should register using an email.(which will be used by the system, to verify the identity of the user, everytime access is required).
2. The system can register as many user as possible, each capable of accessing previous text for imageneration in a certain column(menaing they will be store in a db).
3. The system should be capable of providing a feedback mechanism that will allow the user to :
   - To ask if the generated image ressembled the description / text they entered (yes/no)
   - How accurate or close the image was to the description / input sliding bar (0-10)
   - if the user said no to the first question, give an input text should be given to the user to describe what features weren't in the generated image
   - finally, the image itself should be upload together with the above instruction to be saved on the user database.
4. A list of at least 10, should be kept seen by each user (demostrating just how different every user text and image generated are)
