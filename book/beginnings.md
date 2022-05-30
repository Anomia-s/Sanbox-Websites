## Beginnings
So, you have decided that you want to create your very own Sandbox. That's great.

The first question you have to ask yourself is: "Do I want to be *special*?"; Most Sandbox websites, are mirror of others... they have very similar features, layouts, and sometimes even the character is the same.

It's fine to make your site like the rest, It's the easiest path and most secure. Innovating can be dangerous if not done properly. (BrickPlanet "custom" character is a good example).

If you've decided to be Unique, then you're probably going down the wrong path. Innovating first requires base knowledge of what's common. Most "innovative" websites end up also being very similar to the rest, and that's because they don't know what's new.


### What makes an average Sandbox website?
Most Sandbox websites are composed of 4 core pages.

- Homepage
- Store
- Forums
- Avatar Editor

With these, you have the basics of a Sandbox website.

#### Homepage
The homepage is the most simple of them all, it normally has your character (as a headshot or full body) in a box, your username, and a feed on the side.

The feed though, tends to be used as a Chatbox for users. It's a global feed where everyone publishes random things.

#### Store
The store is amongst the most complex things. It features all the site and user made items and some of them have to be "limited" (numbered stock). The store tends to exist to support another feature we have not mentioned, **trading**, but that's far more complicated and will be mentioned in further chapters.

#### Forums
The heart of every Sandbox websites. People tend to call this websites "Blocky Character Forum Simulator" or "Forum Simulator" in short. Even though people complain about most websites not having a proper client (Game Engine for development and gaming), **nobody really uses them**. Ironically enough, the forums are the most used feature in all Sandbox websites, no exception.

It tends to be simple to create, hardest thing making "quote replies".

#### Avatar Editor
Things tend to go downhill here. This page is where Store Items you bought are worn by your character. Making a proper Avatar editor is... hard.

Most avatar editors run off a headless (Non-graphical) version of blender that renders the avatars using a Python script.

> Note: Python is a programming language that's really versatile and works with Blender.

In my three to now four years of working in different websites, I've seen "horrifying" avatar renderers. Some generated python files for each render, **and did not delete them afterwards...**, so if you had to make a site backup, you'd find yourself with **TERABYTES** of python files scattered around. Certainly not something we want.

Finally, the Avatar renderer speed tends to be something people obsess to. While working at Polytoria, I was creating a TCP service for the Polytoria Renderer written in Golang, and willem kept complaining our renders too 300ms over a TCP network.

Note; TCP is an Internet protocol for messaging between connections.
Note; GoLang is a programming language.

In the end, we did not use the GoLang renderer at all due to an issue with the textures made by the Modellers.

## Let's start!
Yes! But hold on! Do you know any programming language at all? And basic security measures? Or how the Web works at all?

If you are here, most likely not. But if you do, please continue to the next chapters. Otherwise, stay here.

### Learning to code.
"Coding" or "Programming" can both be the easiest and hardest tasks of all. Specially in the **CHAOTIC and FAST EVOLVING** enviorment the World Wide Web is... I myself found myself quite overwhelmed by the ammount of changes that kept happening to the Web.

WORRY NOT though. In this book you'll learn the essentials. And even in the chaotic world of the web, you don't really need to keep up with the latest technology to be good enough. There's a lot of old tech that's still up to today's web standards.

#### PHP, Devil's right hand.
Most newbie web developers in the Sandbox community begin learning PHP, and for a good reason. Atleast 90% of the sites I've seen run off this language. 

PHP is amongst the most hated languages to learn web development with. Unless you use a very Opinionated framework, or know very well Web Architecture (Designing project structures and ideating appropiate code abstraction), it can get extremely messy to work with and very quickly. **Most Sandbox websites have admitted that this happened to them.**


> Note; An "Opinionated" framework is a framework that **requires you to do things in an specific and certain way**.

> Note; A "Framework" as it's name suggests, it's a base codebase to work on top of, it comes with utlities made to help you get things done faster.

So in short; If you are a newbie, and want to use PHP, use an opinonated framework. **Laravel is an excellent choice.**

To note though, unless you know how to set up your servers very well. (And have various of them working together), PHP can easily get clogged. (Slowing down all your site). So this works well for small and medium sites. 

Growth in Sandbox website is exponential though (the more people join the faster more people will join), so you should be ready to fight off these requirements.
