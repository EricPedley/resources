# Resources
List of useful coding resources curated by me
## Cloud Services
    
- **Github pages** - host a static site for free (only works with static sites, you can't write your own backend). Also, it turns markdown into HTML, which is really convenient (I used that feature to make this page)
- **Heroku**  - host the entire site, including the backend server and a free postgresql database (caveat - your server takes 30 seconds to load("cold boot") and you only get five apps)
- **Firebase** - free nosql database and easy way to implement user authentication
- **OpenShift Online** - like heroku, except much more complicated and you only get one free project. The advantage is that it has more RAM, so I tried to host a minecraft server on it
- **IBM Cloud** - free APIs (I've used their speech to text, but they have many more)
- **MongoDB Atlas** - free MongoDB database
- **Google Cloud Platform** - I've used their youtube data API. There are lots of other APIs, for lots of them you need to activate your an account by providing payment info. Another caveat: your projects get deactivated after 90 days of inactivity
- **Cron as a Service** - Schedule http requests. For free you get one request to schedule. I use it to refresh my Google Cloud Platform projects every month so they don't get deactivated for inactivity
    
## Youtube Resources
- [**thenewboston Java Tutorials**](https://www.youtube.com/watch?v=Hl-zzrqQoSE&list=PLFE2CE09D83EE3E28&ab_channel=thenewboston)  - These came in really useful during my first Java class. Probably learned more from these tutorials than my teacher.
- [**Tensorflow ML Zero to Hero**](https://www.youtube.com/watch?v=KNAWp2S3w94&list=PLZKsYDC2S5rM6yKBs5ParXS6RWda6iAnK&index=1&ab_channel=TensorFlow) - Good playlist for getting started with Tensorflow. Does a good job of explaining the code as well as the concepts.
- [**The Computer Scientist's Reinforcement Learning Series**](https://www.youtube.com/watch?v=8MC3y7ASoPs&list=PLIfPjWrv526bMF8_vx9BqWjec-F-g-lQO&ab_channel=TheComputerScientist)  - This guy is criminally underrated. If you want to get introduced to reinforcement learning I would watch this series. A tip from me: try to convert his code from Tensorflow 1 to Tensorflow 2 without using the import tensorflow.compat.v1 trick. It helps cement the concepts.
- [**Web Dev Simplified**](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)  - I came across this channel to learn some specific concepts once I learned web dev at a hackathon, but he also has beginner tutorials that look good to me.
- [**Derek Banas**](https://www.youtube.com/user/derekbanas) - If you already know basic programming concepts and need to learn a new language his videos are great. He just goes over the syntax and he's really straightforward.
- [**Godot Action RPG Tutorial**](https://www.youtube.com/watch?v=mAbG8Oi-SvQ&list=PL9FzW-m48fn2SlrW0KoLT4n5egNdX-W9a&ab_channel=HeartBeast) - This is how I learned the basics of the Godot game engine. You don't need to watch all the videos, just the parts you need for your game
-[**Garbaj**](https://www.youtube.com/c/Garbaj/featured) - Useful FPS tutorials for Godot

## Miscellaneous
- **Ngrok** - easy way to host games. It basically forwards your localhost port to the world wide web. I've used it to host game servers like Minecraft. If the game you're using doesn't let you specify a port number to connect to, use Hamachi instead
- **Git and Github** - I don't know this wasn't the first thing we learned about in programming class. If you're using something like Google Drive file sync to backup and sync your code, you're doing it wrong.