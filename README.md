# About
[![Netlify Status](https://api.netlify.com/api/v1/badges/b9fc7858-c920-402b-9da3-c1dec04f5af3/deploy-status)](https://app.netlify.com/sites/amphibiandiseaseportalnewinterface/deploys)

View running site at: https://amphibiandiseaseportalnewinterface.netlify.app

A lightweight interface for visualizing amphibian disease, drawing on data that has been validated and loaded into GEOME.  This interface is written
in angularJS v1.7 and bootstrap v3.x with the code library controlling aggregation and display functions running at [trait-viz](https://github.com/biocodellc/trait-viz) and document store queries handled by [biscicol-server](https://github.com/biocodellc/biscicol-server).  


# first time installation steps
```
npm install 
```

# to run on a local server
```
npm start 
```

# deployment 
The following uses `public/` as the output directory:
```
gulp clean
gulp   
```

# Serving on the Web

1. Just point Apache or Nginx to the `public/` directory after running gulp
2. Netlify: deploy build command, use `gulp` and point to directory `public`

