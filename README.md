# Pepper Spray
## Installation
### Software dependencies
To make the project up and running, you need:

* **Node** 0.8.19
* **NPM** 1.1.32
* **PostGreSQL** 9.*


### Step 1: Download the dependencies
The app is build at the top of the pleasant [Node Package Manager](http://npmjs.org/). To download and set up the whole dependancies three, simply run from the project's root directory :

    $ npm install

### Step 2: Edit the configuration
#### Use configuration file
The default configuration is present into *config/default.json*. Every modifications in this file will be commited. The *runtime.json* file is an auto-generated file that you shouldn't edit.

* **Development mode**: If you want to overide default values, you have to create a file named *config/development.json* and corresponding to your local configuration. This file will be ignored by git. 
* **Production mode**: if you want to overide default values, you have to edit the *config/production.json* file to fit with your production environment. This file will be ignored by git.

#### Alternative: use environment variables
The following environment variables can be use with the highest priority :

* **PORT** defines the port to listen to (ex: *80*);
* **DATABASE_URL** defines the database URL;
* **NODE_ENV** defines the runtime mode that affects the configuration (ex: *development*, *production*, etc).

### Step 3: Build the database


### Common issues
* **Error: watch ENOSPC**: Do not run the application with DropBox on the same system.
Link: [https://groups.google.com/forum/?fromgroups=#!topic/nodejs/LX7sz9f-fmY](https://groups.google.com/forum/?fromgroups=#!topic/nodejs/LX7sz9f-fmY)

## Licence
Copryright © [Journalism++](http://jplusplus.org) - All rights reserved