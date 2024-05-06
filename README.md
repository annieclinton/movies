![alt text](https://github.com/annieclinton/movies/blob/main/movieLogbookSmall.png)

# Movie Logbook
This fullstack web application allows users to log and track horror movies they've watched, including details like the movie title, main actor, and how much they liked it. 

Users can add new movies, like them, and delete them from the list. 

**Link to project:** https://movies-ive-been-watching.onrender.com/  

Please note, since this project is hosted using Render's free tier, loading may take 50 seconds or more.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Express, MongoDB, Render 

I created a server using Node.js and Express. Node.js allowed me to write my backend code in JavaScript, a language I also use for front end development, and Express allowed me to simplify the code and use more intuitive, readable methods.

For storing the movie data, I used MongoDB, a NoSQL database. MongoDB stores its data in objects, so I wasn't required to learn another querying language, like SQL.

The frontend is simple but functional, built with HTML for structure, styled with CSS for a nice appearance, and powered by JavaScript for interactivity. Users can interact with the application through forms to add movies and buttons to like or delete them.

To make the app available and operational online, I deployed it on Render, a cloud service that offers hosting for fullstack web applications. Render automatically handles deploying the app from the GitHub repository, which makes updates and management relatively straightforward.

## Optimizations

As previously mentioned, since this web app is hosted for free  on Render, the server instance will spin down with inactivity, which can delay requests by 50 seconds or more. It would be great to host this on a paid platform which loads immediately for a better user experience. 

The app currently loads all movie data at once, which could become slow as the number of entries grows. To optimize this, I would implement pagination to load a fixed number of movies per page. This would reduce the load time significantly and improved the user experience.

I would like to write css to improve the way the project looks.  

## Lessons Learned:

Building this project was a fantastic learning experience, especially in understanding how the frontend and backend work together. I learned how to create a server, link it to a database, use ejs, and deploy a web service. 

Initially, my Render deployment failed, but I was able to solve the problem by whitelisting the IP address on MongoDB. Of course, Render was initially unable to access the MongoDB database, since the only IP address allowed to access it had been from my personal computer. 





