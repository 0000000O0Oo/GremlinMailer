# aGremlinMailer
aGremlinMailer is an automation tool to create HTML files with your targets information.



<h2>Phishing</h2>
aGremlinMailer is particularly useful for phishing attacks since it can create more than a 1,000 different mails each containing the different informations of your targets in a matter of seconds, all you need is a template and a list of targets. <i>Note that aGremlinMailer does not support the sending of mails yet, for now it only generate the HTML files for sending !</i>

<h2>How it works ?</h2>
When you're running the program, it will first ask you for 2 things.

- HTML Template
- List of Targets File

![Image](https://i.imgur.com/W3AyG8K.png)

Note that if you choose default as shown in the screen it will choose the name mail.html for the mail template and list.txt for the list of target


<h3>- HTML Template</h3>
In your HTML Template file you're gonna need to replace the informations you want to change by one of the different tags available tags :

- ^N^ : Name
- ^LN^ : Last Name
- ^E^ : Email
- ^D^ : Actual Date

<h3>- LIST FILE</h3>
For the list file you will need to use one of these formatting :

- FirstName
- FirstName LastName
- FirstName LastName Email

An example could be :

TheGreenGremlin Gremlin gremlin@gremlin.com

John Doe jdoe@doodoo.com

Jane Doe mjdoe@dodoo.com

![action](https://i.imgur.com/EveZ44R.png)
