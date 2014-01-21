# Phusion Passenger: Node.js WebSocket demo

This application demonstrates WebSocket support in [the Phusion Passenger application server for Node.js](https://www.phusionpassenger.com/), through the use of the awesome [Socket.io library](http://socket.io/). Passenger supports all major modern web technologies, such as WebSockets, entirely out of the box. You don't have to do anything: WebSocket support just works.

<div style="text-align: center"><a href="https://www.phusionpassenger.com"><img src="http://blog.phusion.nl/wp-content/uploads/2014/01/Passenger_chair_256x256.png" width="256" height="256" alt="Phusion Passenger"></a></div>

## Getting started

 1. [Install Phusion Passenger](https://www.phusionpassenger.com/).
 2. Clone this repository:

         git clone https://github.com/phusion/passenger-nodejs-websocket-demo.git
         cd passenger-nodejs-websocket-demo

 3. Install dependencies:

         npm install socket.io

 4. Run Phusion Passenger in its Standalone mode:

         passenger start

 5. Access the demo application at http://0.0.0.0:3000/, and see it in action.

## About Phusion Passenger

<a href="http://vimeo.com/phusionnl/review/80475623/c16e940d1f"><img src="http://blog.phusion.nl/wp-content/uploads/2014/01/gameofthrones.jpg"></a>

[Phusion Passenger™](https://www.phusionpassenger.com/) is a web server and application server, designed to be fast, robust and lightweight. It takes a lot of complexity out of deploying web apps, adds powerful enterprise-grade features that are useful in production, and makes administration much easier and less complex. Phusion Passenger supports Ruby, Python, Node.js and Meteor, and is being used by high-profile companies such as **Apple, Pixar, New York Times, AirBnB, Juniper** etc as well as [over 350.000 websites](http://trends.builtwith.com/Web-Server/Phusion-Passenger).