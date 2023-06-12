# 👋 Hello developer!

This template is beautifully designed to play battleship game with multiplayer mode. It utilizes utilizes flex containers for effortless positioning and employs Socket.IO to transfer real-time game information across the players. 

This project serves as an example of what can be achieved. It is not a fully functional product. Feel free to use the source code and ideas as a starting point for your own projects.

This is only one of the many templates available from W3Schools. Check our [tutorials for frontend development](https://www.w3schools.com/where_to_start.asp) to learn the basics of [HTML](https://www.w3schools.com/html/default.asp), [CSS](https://www.w3schools.com/css/default.asp) and [JavaScript](https://www.w3schools.com/js/default.asp). 🦄

## Knowledge requirements

To be able to fully understand and modify this template to your needs, there are several things you should know (or learn):

- [HTML](https://www.w3schools.com/html/default.asp)
- [CSS](https://www.w3schools.com/css/default.asp)
- [Sass](https://sass-lang.com/)
- [JavaScript](https://www.w3schools.com/js/default.asp)
- [React](https://reactjs.org/)
- [Node.js](https://www.w3schools.com/nodejs/default.asp)
- [Express.js](https://expressjs.com/)
- [Socket.IO](https://socket.io/)

## 🎨 Where to find everything?

This template is made by using several technologies.  
Below are explanations about where to find specific code.

Public resources are found in the folder `public`.

Data is stored in your admin console.

### Root HTML

There are two important HTML files in this project which are the root pages around the application. It is a bit different from a default React project as you in this case have two. One in root folder and one in `public`. The reason for this is that one is rendered before the other.

### CSS and images

The CSS in this project is of type Sass which is a CSS framework. You can read more using the link provided in Knowledge requirements. You can find the sass files together with the components in `client/src/components/` and there is one main sass file located on the top level `client/src/index.scss`. 


### Application

You can find the core frontend React application in `client/src`. Here you have a normal React setup with `index.jsx` as the glue that pieces the `.jsx` components together with the HTML. You will have to know React to use this template.

### Backend

The backend work is in `server/`. 
Game management related logic is in `server/gameManager.js`
Socket related codes are in `server/socketHooks.js`.
Ping API is in `server/index.js` and other resources are servered from `server/index.js`.

**Do not change the `w3s-dynamic-storage` folder name!**  
**By changing the `w3s-dynamic-storage` folder name, you risk the space not working properly.**

### Config Management

Client side config shall be updated in `client/src/config.js`.
In the Environment tab, update server side configuration.

## 🔨 Please note
For now files created/uploaded or edited from within the terminal view will not be backed up or synced. 

## ⛑ Need support?
[Join our Discord community](https://discord.gg/6Z7UaRbUQM) and ask questions in the **#spaces-general** channel to get your space on the next level.  
[Send us a ticket](https://support.w3schools.com/hc/en-gb) if you have any technical issues with Spaces.

Happy learning!
