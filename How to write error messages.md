# How to write error messages #

“The best error message is the one that never shows up” — Thomas Fuchs

The basic idea is to think of potential errors during the process of creating the application and not after it is implemented. This will help you prepare different scenarios for various error situations. What is more, you may even be able to eliminate errogenic situations from your product.

You have to make it clear that the error occured (visibility of system status). The best option is to display the error message close to the error's source.

![visibility](visibility.png)

przykłady, ale są też wyjątki (np komunikat microsoft z wojtka Aleksandra)

"Error messages should be expressed in **plain language** (no error codes), precisely indicate the problem, and constructively suggest a solution.

As Wojciech Aleksander points out in his "UX writing. Moc języka w produktach cyfrowych",when you write an error message it is best to use *inverted pyramid*:

![pyramid](The-inverted-pyramid.png)

The most improtant information is how to solve the problem.

Then you can explain what happened, and finally, you may provide the user with some details, eg. what brought the error about.

Compare these two messsages:

![wrong_2](wrong_2.png)

![good_podpowiedzi](good_podpowiedzi.png)

The first one only communicates about the error without any expalanation what went wrong, what is missing and how to enter the correct data.

The second one, on the other hand, gives the solution first, and then informs that the error occurred.

In the example above you can notice that error messages should be also presented with visual treatments that will help users spot and recognize them.

Conventionally, use bold text and highlights, high-contrast and red color (as in the message above) for the affected elements that require correction. 

However, remember that for about 350 million people worldwide with a color-vision deficiency, this may not be enough and, therefore, apply the animation to indicate errors as well.

![amazon](amazon.jpg)

Z Wojtka aleksandra o podpowiedziach w wyszukiwarce

**use confirmative sentences**

**Give alternative solutions** (Wojtek - nie zostawiaj na lodzie)


!!!!!!youtube video: provide helpful constraints so that the user is limited to scenarios in which they can face an error message!!!!!


## Use the right format for your error messages ##

Error messages are typically presented in modal dialog boxes — overlays that prevent users from interacting with underlying content. Putting error messages in modal dialog boxes has a major benefit — it gets 100 percent of the user’s attention. Thus, they should only be used in important situations like destructive actions (such as deletions).




However, this quickly becomes a drawback if that attention isn’t necessary. In many cases, it’s possible to show the error messages using alternative patterns such as inline or as a status message.

