# Design Doc: Mini Slack

## Adam Shuai, Nov 2017

### Overview

Mini Slack is a full-stack system supporting multiple users real time sending messages in multiple groups. This document covers the details of the implementation of this project from engineering perspective.

### Major Use Cases

##### User account 

1. User can create account, log in and log out.
2. User can edit the basic details like uploading image.
3. User can add friends and delete friends.

##### Chat 

1. Multiple users can chat every channel.
2. User can join multiple channels.
3. User can send emoji, sticker.
4. Chatting history will be stored. 

##### Channel

1. User can see list of channels.
2. User can create the channel to chat.
3. User can search channel.

##### Bot

1. Every Channel has a bot to chat.
2. Every user can have a private channel chat with bot.

### High-level Stack Diagram

| Stack           | Technologies                             |
| --------------- | ---------------------------------------- |
| Frontend-client | AngularJS, Socket.io                     |
| Backend-server  | Express, Socket.io, MongoDB, Redis, Nginx, Bot Service |

### Architecture

![architech](/Users/SuperFahai/Documents/CS503/capstone/Design Doc/architech.png)

### Detailed Design

##### Log in & Register



##### Bot API



### UI Example

![ui2](/Users/SuperFahai/Documents/CS503/capstone/Design Doc/ui2.png)



![ui1](/Users/SuperFahai/Documents/CS503/capstone/Design Doc/ui1.png)

![ui3](/Users/SuperFahai/Documents/CS503/capstone/Design Doc/ui3.png)

