# Netflix Clone

### Running Project Locally
* First get a TMDB API key from [here](https://www.themoviedb.org/documentation/api)
* Create a `.env` file in root project and add: `API_KEY=YOUR_API_KEY_HERE`
* Then run:
```shell
npm install  # Install packages
npm run dev  # Run the web server - Defaults to localhost:8080
```

Original source: https://github.com/AndresXI/Netflix-Clone

Forked here because `Aux.js` is a reserved filename on Windows, and students were having problems cloning it via Git on Windows.

- Demo: http://netflix-clone-react.surge.sh/

This project is a simplified front end clone of Netflix. It was created with React and CSS (Grid and Flexbox). It uses [The MovieDB Api](https://www.themoviedb.org/documentation/api) to search for movies and display details. Feel free to contribute!

### Tools used:
- Webpack 
- Axios
- Redux & React
- Sass (grid & flexbox)
- Media queries
- Swiper JS

### User Stories: 

- User can search for movies and TV shows on TMDb
- User can the see upcoming and trending movies. Data updates weekly 
- User can click on a movie and a modal should pop up. It should display the title, release date, overview, and runtime.  
- The webpage adapts to any screen size.

### Video Walktrough 
![](https://github.com/AndresXI/Netflix-Clone/blob/master/netflix-demo.gif?raw=true)



Please feel free to create a pull request and submit any issues!
Currently looking for backend developers. If you would to contribute to support a backend, reach out, all ideas are welcomed!
