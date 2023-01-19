## Coding Task for Interview:

Code a web panel where you can login with telegram and using bot/chat commands it can control a trello board to add/remove cards and columns.
Host the created platform and provide access to the github codebase along with test credentials. For added bonus you can attach a video recording of using the platform.

## Skillset Required:

    - Back-End
    - Front-End Development
    - Third Party API Integrations

- Explaination: https://www.youtube.com/watch?v=bFFMX1L8TKI

## Features

1. Add Cart
2. Remove Card
3. Move Card

## Steps

- NodeJS + MongoDB Setup
  - Design Schema - Board, Tasks, Users
  - Create API's - /boards, /boards/1,
  - Use MongoAtlas
  - Deploy Backend to Cyclic, Render
- [Bot Setup](https://www.youtube.com/watch?v=bFFMX1L8TKI)
  - Create a Bot Using BotFather
  - Create a new Backend in Nodejs add [node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api)
  - Add if else for condition and fetch data from NodeJS API
  - Convert response to text
  - send it to frontend
  - Deploy bot to Cyclic, Render: https://www.cyclic.sh/posts/how-to-build-a-telegram-bot/
- Frontend
  - Call backend API to show board
