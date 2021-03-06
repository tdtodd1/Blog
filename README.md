# Blog
 1. Todo
 - Home page displaying Signup and Login options.
 - Signup/login pages with forms.
 -  Customized home page after logging in/signing up with a logout option. Clicking on logout
    should take you to the home page. Server side PHP
 -  create/display blog posts

 - The customized homepage should have search and review/comment features.
 - Search Feature: JSON data retrieval from a Web Service using AJAX and displaying the
    response in a specific format (refer to how yelp displays the result items). Below are some
    web services that you can choose from to get your data:
        • Movies: http://www.omdbapi.com
        Scroll down to usage and parameters sections to learn more about this service for
        movie data.
        For example, you can search for movie details by its title as follows:
        http://www.omdbapi.com/?apikey=78852e23&t=gone+with+the+wind
        To analyze the JSON response you can copy and paste the above URL into the
        browser. The response is a JavaScript object with various properties. Please sign
        up for a key and replace this api key with your own.
        • Books: https://www.googleapis.com/books/v1/volumes?q=title:web+development
        You can use this web service for searching books by title. For example, all web
        development books by using
        https://www.googleapis.com/books/v1/volumes?q=title:web development
        • Photos: https://pixabay.com/api/docs/
        You can use this web service for searching photos. Scroll down to the parameters
        section to learn more about this service for retrieving photos.
        For example, you can search for photos of yellow flowers as follows:
        https://pixabay.com/api/?key=15701013-
        d345344bc05906c8b823eb2d7&q=yellow+flowers&image_type=photo
        To analyze the JSON response you can copy and paste the above URL in the
        browser. The response is a JavaScript object with various properties. Please sign
        up for a key and replace this api key with your own.
        • Museum: https://github.com/harvardartmuseums/api-docs
        You can use this web service for searching museum collections. For example, you can
        search for Vincent Van Gogh’s work as follows:
        https://api.harvardartmuseums.org/object?apikey=YourAPI_Key&q=vincent+van+gogh
        Please sign up for a key and replace this api key with your own.
        • There are several web services APIs available through RapidAPI. If you want to use any
        of RapidAPI, you have to create an account with them.
 - User review/comments: Clicking on an item from the result list should take the user to the
 review/comments page. This page should display information of the selected item along with
sample reviews, and let the user write a review on the item. You can use window.location to
 pass data between the two pages through JavaScript.