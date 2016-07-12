# Intro

## Programming for Non-Programmers

## Class Expectations

# How the web works

## What happens when you go to a website?

### You Do: What you see:

1. Go to http://generalassemb.ly
- Admire the beautifully-designed website

### You Do: What your computer sees:

1. Go to https://www.hurl.it/
- As your destination, enter "generalassemb.ly"
- Check that you're "not a robot"
- "Launch Request"

### Takeaways

- Whenever you go to a webpage, all this information is being transacted beneath the surface very, very fast

## What happens when you look at an image?

### You Do: What you see:

1. Go to https://upload.wikimedia.org/wikipedia/commons/c/c0/Nicolas_Cage_Deauville_2013.jpg
- Admire Nic Cage's shining face

### You Do: What your computer sees:

1. Go to https://hurl.it
- As your destination, enter "https://upload.wikimedia.org/wikipedia/commons/c/c0/Nicolas_Cage_Deauville_2013.jpg"
- Check that you're "not a robot"
- "Launch Request"
- **Then:** Click "view raw" to the top-right of the image (after the "Headers" section)

### Takeaways

- What you see and what the computer sees are completely different

## Your web browser is an actor

The job of a stage actor is to take a bunch of text -- a script -- and interpret it, turning it into something *more than text* -- a play.

The job of a web browser is to take a bunch of text -- source code --  and interpret it, turning it into something *more than text* -- a webpage, or an image.

### Differences in interpretation

Different actors will interpret the same script in different ways. Leonardo DiCaprio gave a completely different interpretation of Romeo in 1996 than Leonard Whiting in 1968.

Different web browsers will interpret the same source code in different ways. GA's site looks very different on Chrome, on Internet Explorer, and on your smartphone.

### Standards

- **Question:** Have you ever opened a document in Microsoft Word only to see that some of the letters and punctuation got replaced with weird, glitchy characters? Why do you think that is?

- **Question:** Everyone says a meter is 100 centimeters long. What's stopping you from being different and saying a meter is 90 centimeters long?

Different web browsers interpret code in different ways. To keep sites consistent, web browser developers agreed on **standards**: "this piece of code will do this specific thing".

> **Illustration:** This is why everyone hates Internet Explorer. Microsoft invented its own standards, thinking, "Since most people use Internet Explorer, they'll conform to the standards we invent, and then we'll effectively control the internet." People just stopped using IE instead.

## Clients and servers

Your web browser gets source code from an application on another computer called a **server**.

- **Question:** Servers and clients in computing are like clients and servers in a restaurant in that:
  - Servers work 9 to 5 and clients tip them
  - Servers make things out of the ingredients that clients bring them
  - Servers take requests from clients and respond to them
  - Servers tell clients what to do

A server application's job is to be a secretary: it "listens" for a "phone calls" requesting a file, then sends back a copy of the file.

- **Question:** Server computers are a lot like your computer. You can run a server on your computer that everyone in the world could access: I could run GA's website from my laptop. So why don't I?
  - Consistency: I want to turn my computer off.
  - Speed: My computer spends most of its energy making things show up on my screen. Websites are run on computers specifically designed to run servers, and they often don't even have screens.
  - Security: I take my computer with me everywhere and have used the same password for everything since 7th Grade.

> **Illustration:** Screenshare logging into a Digital Ocean server via SSH and updating a live website.

### Front and back

- **Question:** Shakespeare has been commissioned to write two plays: one for the King of England and one for the King of Spain. He only has time to write one play. What can he do?
  - Send the same play to both.
- **Question:** Further complicating things: the play makes fun of the Spanish monarchy. Clearly Shakespeare can't send that play to the Spanish King. What can he do?
  - Slightly rewrite the Spanish play to make fun of the English monarchy.
- **Question:** When I open up my Facebook profile, I load 2.1 megabytes of source code: HTML, images, Javascript, and so on. There are 1 billion Facebook users. **True or false:** Facebook has one billion 2.1-megabyte files stored on its computers, one file for each user.
  - False. Every Facebook profile page is more-or-less the same, just with some text and images swapped out. Facebook would have 2 million gigabytes of nearly-identical data. Any time Facebook wants to change its interface, they would have to rewrite all 2 million gigabytes.
- **Question:** What could Facebook do instead to give the *illusion* of everyone having their own profile page?
  - Use one file as a template, instead of 1 billion separate files. Then when someone requests their profile page, load the template, insert the appropriate data into it, and send it to the user.

**Back-end developers** are all about what code should be sent to your web browser. They can do this in virtually any programming language: PHP, Ruby, Python, Java, etc.

**Front-end developers** are all about what your web browser does with that code once it receives it. They deal exclusively with HTML, CSS, and Javascript.

## AMA about the Internet

# Getting to know your computer (Cloud9)

- [DC Directory Tree](https://github.com/ga-wdi-exercises/dc_directory_tree)

- [CLI Gardening](https://github.com/ga-wdi-exercises/cli_gardening)

- [To Oz](https://github.com/ga-wdi-exercises/to_oz)

# Web Design

## HTML

- [HTML Tag Matching](https://github.com/ga-wdi-exercises/html_tag_matching)

- [HTML Fixit](https://github.com/ga-wdi-exercises/html_fixit)

## Developer Tools

- Hijack Google

## CSS

- Making colors from words

- [CSS Crash Course / Review](https://github.com/ga-wdi-exercises/css-review)

- [Positioning Operation](https://github.com/ga-wdi-exercises/positioning_operation)

# Git

- [Love Song](https://github.com/ga-wdi-exercises/love_song)

## Deploying

- [Portfolio Page walkthrough](https://www.youtube.com/watch?v=I6jocfpmKP0&index=1&list=PLae1he6d1WIlAWnbAMIWFzL0ibaKr4q-P)

# JS

- [JS Data Types practice](https://github.com/ga-wdi-exercises/js-data-types)

- [Debugger Jokes](https://github.com/ga-wdi-exercises/debugger-jokes)

- [Fizzbuzz Mix n' Match](https://github.com/ga-wdi-exercises/fizzbuzz_js)

- [Errors Practice](https://github.com/ga-wdi-exercises/js-errors-practice)

- [DOM Practice](https://github.com/ga-wdi-exercises/js-dom-quotes/tree/jquery)

- [Mini Pixart](https://github.com/ga-wdi-exercises/pixart_js_mini)
