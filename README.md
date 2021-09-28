
<h1 align="center">Weather bot for Telegram 🌦</h1>
<div align="center">
  
 <div align="center">
  
[![Telegram](https://img.shields.io/badge/Telegram%20Bot-1.0.0-0088cc)](https://t.me/WeatherAryanBot)

</div>
  
###### You can get information about weather in all cities in the world in real-time

[![JDK](https://img.shields.io/badge/JDK-15-orange)](https://www.oracle.com/java/technologies/javase/15-relnote-issues.html)
[![Maven](https://img.shields.io/badge/Maven-4.0.0-9cf)](https://www.apache.org)
[![Telegram API](https://img.shields.io/badge/telegrambots-5.0.0-blue)](https://core.telegram.org/bots/api)

</div>

## Table of Contents

- [Screenshots](#screenshots)

- [Technology stack](#technology-stack)

- [Installation](#installation)

- [Deploy](#deploy-on-heroku)

- [Environment Variables](#environment-variables)



  
## Screenshots

![App Screenshot](https://github.com/filtitov2001/WeatherBot/blob/main/assets/first.png)

![App Screenshot](https://github.com/filtitov2001/WeatherBot/blob/main/assets/second.png)

  
## Technology Stack

* Java 15
* Telegram API
* Maven
* Open Weather Map API


  
## Installation

For install the project, follow next steps:

- Open the Terminal

```bash
  git clone https://github.com/filtitov2001/WeatherBot
  
```
- Set your generated token and username in application.yml

- Build the project and start:
```bash
  mvn -DskipTests clean dependency:list install
  
  cd target
  
  java -jar Telegram_WeatherBot.jar
  
```
    

## Deploy on [Heroku](https://heroku.com)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Environment Variables

To run this project, you will need to add the following environment variables to your application.yml file


- `TELEGRAM_BOT_USERNAME` - Create a bot via [BotFather](https://t.me/botfather)

- `TELEGRAM_BOT_TOKEN` - Get token by contacting  to [BotFather](https://t.me/botfather)


## Copyright

Copyright © 2021 by [Felix Titov](https://github.com/filtitov2001)
