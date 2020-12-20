---
	description: Websites are an essential part of our modern world. We are constantly using them to accomplish varied tasks, but most of us does not know how they actually work. In this post, I talk about the process of building a web application.
---

Nowadays, almost everybody visits many websites on a daily basis. It is hard to stay even one day without accessing any website on either your computer or your smartphone because we rely so much on them, both for keeping our routine (be it work or study) and for entertaining ourselves.

That said, do you really know what is needed for a website to work? We are so used to just type a URL in a browser or click a link that some of us may to take for granted the work done by developers to create those applications. In this post, I make use of my intermediate experience building web applications (like this blog) to explain briefly the process of creating a website.

<HorizontalAd />

# Front-end versus back-end: understanding the basics

<Img url='https://api.stemguy.club/uploads/coding-man.jpg-82ecd7873a153f59ed18bcaeca479db6.png' alt='Man coding with floating interface' credit='Man vector created by upklyak - www.freepik.com' creditLink='https://www.freepik.com/vectors/man' width=5000 height=3333 />

Before diving into the more practical part, it is important to understand the separation of tasks within the application.

## Web: dealing with clients

The front-end of an application is what a client visiting the website directly sees and with which he/she interacts. It is usually more of a visual part, not handling many logic tasks.

## Server: dealing with requests

The back-end of an application is not directly accessible for the client, communicating with the front-end via HTTP requests (which is basically a way of transferring information in the internet). It is usually recommended creating more complex logic functions in this part and sending the results to the web interface.

### Databases: managing information

Ok... I have talked about tasks, but where does information is stored when, for example, an administrator of the STEM Guy blog posts a new article? This is the responsibility of databases! You may have realized that this topic is inside 'back-end'; well, this is because those two are in constant communication. In this sense, the server creates, reads, updates, and deletes — which are usually called CRUD functions — information in the database.

It is also important to point out that there are two types of database programs: SQL (which stores information in tables) and NoSQL (which uses different ways to store information).

<HorizontalAd />

# Technologies: coding an application

<Img url='https://api.stemguy.club/uploads/coding-language.jpg-f2b1afe1591397e71a7bc61ad4c2c278.png' alt='Coding language' credit='Photo by Christopher Robin Ebbinghaus on Unsplash' creditLink='https://unsplash.com/@cebbbinghaus?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText' width=4272 height=2848 />

Now that we have understood the different conceptual parts of a web application, let's take a look at the technologies used to practically create those parts.

## Languages: communicating with a computer

When I try to explain how websites work for some non-tech friend or relative, the most common question that arises is how can we tell a computer what it needs to do. Before answering this question, I must tell you that computers have their own language! That is right, the famous binary code can be directly understood by our machines.

That said, while theoretically possible, it would be extremely hard to code in binary because the simple term "STEM Guy" would be 01010011 01010100 01000101 01001101 00100000 01000111 01110101 01111001. Now, imagine coding a whole application, with many tasks, using this complex syntax! This is why we have different languages that are more familiar to humans and, when our coding is complete, we can compile it (convert from the language used to binary code).

### Programming: performing specific tasks

Programming languages are usually what programmers mean when they say "language". They are able to perform specific tasks, like printing some information or reading some input.

There are a lot of programming languages in the world. For the front-end part, the most famous one is [JavaScript](https://www.javascript.com); while for the back-end, the most used is [PHP](https://www.php.net). Besides, for databases, the most common language is SQL — which is obviously used in SQL database programs —, but each NoSQL program has its own syntax for managing information, the most famous being MongoDB.

### Markup and style: formatting a website

Besides programming, languages can have other functions like markup and styling. For example, HTML — the most famous markup language for the web — tells the computer what should be displayed and how. Furthermore, CSS is the most common language used for styling websites.

## Frameworks: making our lives easier

Even tough I have just talked about the most used languages, nowadays most developers use frameworks to make some processes easier and faster. For the front-end, I use [Next.js](https://nextjs.org), which is a framework of [React.js](https://reactjs.org), which is a framework of JavaScript (crazy right?). For the back-end, I use [Express](https://expressjs.com), which is a framework of [Node.js](https://nodejs.org/en/), which is another frame of JavaScript.

Frameworks add layers of abstraction (which means there is some work being done without we actually coding it), each one with a different purpose. This is why there are so many available, being the developer's responsibility to choose the ones that are more useful for his/her common use.

## Packages: using code from the community

While coding anything, it is common to use libraries/packages created by others in order to execute some task. With web development, this is not different! This is true especially for JavaScript, which has more than 1 million packages available in the community.

<HorizontalAd />

# Deployment: making an application available to the world

<Img url='https://api.stemguy.club/uploads/website-host.jpg-13b54b871df61dc59c00a761b242545e.png' alt='Cloud hosting illustration' credit='Technology vector created by stories - www.freepik.com' creditLink='https://www.freepik.com/vectors/technology' width=2000 height=2000 />

Once a developer finishes coding a website in his/her machine, it is time to make it available to the world!

## Host: using remote computers

In theory, we could host websites in our computers, but they would need to keep turned on all the time, which — along with other reasons — makes it impracticable. Therefore, the most common practice is to use remote computers, by using some hosting service.

There are a lot of options available in the market, but what I currently find the best solution for me is to use [Vercel](vercel.com) to host the front-end (which is free for individuals and has an awesome integration with Next.js) and [DigitalOcean](https://m.do.co/c/3fefb3daa386) to host the back-end (which is paid, but offers an amazing service for a small price), including databases.

## Domain: getting an ID

Once an application is hosted in some service, you can access it via the IP address, which looks like this: 123.456.789.123. Wait, but we do not type strange numbers like this when we want to visit some website, right? We type some nice names like [stemguy.club](https://stemguy.club). The name of those "nice names" is "domain", and they can be registered in some Registrar.

A domain basically directs a browser to some IP address, so that a client does not have to remember those strange numbers to visit some website. Therefore, in principle, it serves like an ID, identifying your application in the world's registry.