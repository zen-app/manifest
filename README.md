# Zen Manifest

Every time that we need to learn something new like a language or framework, 
we usually follow simple tutorials or even "Hello World" examples reading the technical stuff.

But this is boring, 
I know... normally we learned the basics doing that, however, we must try to do more than that, 
we must to apply this new knowledge building something really nice, something with some purpose. 

So, why not make a kind of To Do List, or something using an external API? That's much cool than a simple "Hello World" right?

Zen is that proposed. A challenge to improve your skills in development.

## What is the Zen proposal?
Let's think about many options that we can make? What is the main goal thinking in features and how it's should work?

#### Front End
On the Front End side you might develop only with JavaScript or maybe you might to learn about ES6 too. However, we you talk about frameworks, we have a lot of options like AngularJS, ReactJS, Backbone, Ember, etc.

#### Back End
If you want to do the things simple, go ahead, but if you don't know how an API should work, it's time to change it. Doesn't matter what framework you'll use, just try to do your best. It's a great time to learn a new type of database.

Try to keep the things simple and modular, you know... a good software, you know...

Maybe some patterns and tests can be an awesome ideia to,
trust me, after banging his head for a long time, 
TDD can be a great idea to addopt.

Let's think in some <del>damns</del> MVP exemples.

Let's take a look in a few features for each kind of app:

- [To Do List](#user-content-to-do-list)
- [Weather Monitor](#user-content-weather-monitor)

### To Do List

- We can create new tasks;
- We can mark a task as completed;
- We also can delete a task;

Ok, but what can be a task?

- Tasks normally have a description *(ex: Learn something new)*;
- Tasks can have a category *(ex: Personal)*;
- Tasks can have a due date *(ex: Jun 4th 2016)*;

#### Additional Features

If the simple simple MVP isn't enogth to you, maybe you could to push some cool stuff into your project:

- Tasks can have tags/labels to filter and search;
- Create an external API integrate on your Frond End (We love API's didn't we?);
- You must be logged in to use the service (That provides you a easy way to get this data in any place);
- Reminders via email, Push Notification and SMS (Why not? Mandrill, SendGrid, Twilio and others services to you learn);
- Integrate your app with social networks (Because Social login make the things really easy);

### Weather Monitor

- Add places and retrive the Weather data from external [Yahoo Weather API](https://developer.yahoo.com/weather/);
- Allow user configure application weather display (Fº or Cº);
- Show the forecast about that place (Next 5 days);

#### Additional Features
- Store places into LocalStorage;
- Add Location Autocomplete while user are typing;
- Validate data and display error if the Locations doesn't exists;
- Create a list with more than one place;
- Allow user remove places click in the "X" icon;
