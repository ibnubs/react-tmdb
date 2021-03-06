# TMDb API w/ React

### Live demo

https://tmdb.arthurn.me/

### Tools used

- webpack 4.6.0
- react 16.2.0
- redux, redux-thunk
- material-ui, styled-components, grid-styled

### Development

Start: `yarn dev` (default port: 3000)

Start and open bundle analyzer: `yarn dev-bundle-analyzer` (default port: 8888)

### Production

Build: `yarn build`

Build and open bundle analyzer: `yarn build-bundle-analyzer`

### .prod.env file example

```
THEMOVIEDB_API_KEY=8SUisSHs7sSIsioSPsms
THEMOVIEDB_API_LANGUAGE=en-EN
THEMOVIEDB_API_ADULT=false
```

[Language variables](https://developers.themoviedb.org/3/getting-started/languages)

### TODO

- [x] remove redux-logger from production build
- [x] remove style-loader
- [x] change favicon
- [x] axios instead of fetch
- [x] search input
- [x] fav/unfav movies
- [x] react-helmet titles
- [x] favorite movies page
- [x] react-router-redux
- [x] responsive
- [x] better appbar
- [x] better colors for randomgradients
- [x] better pagination buttons
- [x] fix fav from movie details page
- [x] recommendations cards
- [x] async/await instead of promises
- [x] genres => ls
- [x] similar movies instead of recommended
- [x] netlify deploy config
- [x] short genres (recommended cards)
- [x] react-loadable
- [x] movie poster => background
- [x] webpack compression plugin
- [x] lazyload posters
- [x] mute adult movies
- [x] adaptive gradient
- [x] show "no results"
- [x] svg logo component
- [ ] details page
- [ ] fix useless rerenders
- [ ] infinite scroll for similar movies (???)
- [ ] remove useless babel polyfills (???)
- [ ] catch no poster
- [ ] typescript
