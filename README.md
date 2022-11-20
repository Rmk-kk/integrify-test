# Test task for Integrify

This project was made with react create-react-app, react-bootstrap, react router.

## Used technologies

`React`, React Hooks: `useEffect`, `useState`, `useParams`; Router hook: `useNavigate`; `Localstorage`, `JSONPlaceholder API`, `AccuWeather API`, `React bootstrap` and `CSS styling`

## Disclaimer
Weather API is very limited for requests. I have tried to make dynamic weather cards when you send request for 'Find city by name', this function can easily create a lot of requests, so API can be locked for 24 hours because of limit really fast. I highly recommend checking it on cities, like Helsinki, Oulu etc., because there are almost no cities with same names. ( Example : You will search for Moscow, it will find about 24 cities named Moscow, and each city will create a request for weather to show you current weather there. So it's 25 requests, and the limit is 150/ daily).

## Features 
### Client Card
 1. localstorage set for Client Card tasks. It's made to imitate post requests to server when adding or removing a new person, so you can add/remove, reload page and the changes will still be there. 
 2. You can add client to favourites, and then sort the list to show only favourite clients
 3. Ability to delete and add clients from the list ( Max 12, after that button is disabled)
 4. Expand cards to see more detailed information about the client
 5. For new clients i connected 'id generator', so the id of new clients and old ones are unique, but in different style.
 6. You can click on button at the end of the list to add new client.
 7. Added filter by name to quickly find client if you know his/her name.

### Weather API
 1. Dynamic Cards - When searching for city you see live weather there, and on click you will be re-directed with router to city page to see forecast for 5 days.
 2. On City page you see 5 days forecast, and if you hover on one of those cards it will rotate showing you forecast for the night time that day.
 
 
### Screenshots

`Screenshots are scrollable to right side, when you open them`

![Weather API - Search](https://github.com/Rmk-kk/integrify-test/tree/master/public/screenshots/image_2022-11-20_12-34-14.png?raw=true)
![Weather API - City Page](https://github.com/Rmk-kk/integrify-test/tree/master/public/screenshots/image_2022-11-20_12-34-25.png?raw=true)
![Cards API - All Cards](https://github.com/Rmk-kk/integrify-test/tree/master/public/screenshots/image_2022-11-20_12-34-56.png?raw=true)
![Cards API - Detailed information](https://github.com/Rmk-kk/integrify-test/tree/master/public/screenshots/image_2022-11-20_12-35-02.png?raw=true)


    

