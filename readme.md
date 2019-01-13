Hello World! :)

This is the second evolution of my first React project. I was trying to add some technologies, and I have introduced some Redux and server side rendering.

For security reasons, I have removed .env file in the root directory of project, so obviously app will not work as it should without it.

So if you want to start the app and see it fully working, you will need to register to this website:

https://www.petfinder.com/developers/api-key

And get your own API keys, because we are using "Petfinder" API to get the animal informations. Petfinder is based in US, so it is not available all around the world, only in few countries.

Once you get your keys, you can create the .env file in the root directory, and populate API data in there.
Then navigate to root folder from terminal, run these commands:

npm install
npm run start

And you should have running application in your localhost.

Thanks a lot to Petfinder for making their API available for usage, credits to them.
