# NUral Network (server)

I used node.js and express.js to handle server side requests and orchestrate responses to the react client. I used lots of RESTful APIs to perform the backend functionalities mentioned in client side readme.

I originally had the server configured to interact with the postgresql database where I used SQL queries to retrieve data and display to the web app (for assignment 5), but changed it to configure the supabase database and authentication for assignments 7 and 8. I also used the supabase storage service to store users' profile photos. I attempted to deploy the project to vercel, but I am not sure how to handle the change in deployment url each time on both the client and server, hence the deployment does not work as of 12/31/2024.
