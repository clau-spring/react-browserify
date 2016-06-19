# React Tutorial

This is the React comment box example from [the React tutorial].

## To use

There are several simple server implementations included. They all serve static files from `public/` and handle requests to `/api/comments` to fetch or add data. Start a server with one of the following:

### Gulp

```
npm gulp install
```

### browserify

```
npm gulp install
```

### babelify

```
npm gulp install
```

### vinyl-source-stream

```
npm gulp install
```

### gulp-uglify

```
npm gulp install
```

### Node

```sh
npm install
node server.js
```

### Python

```sh
pip install -r requirements.txt
python server.py
```

And visit <http://localhost:3000/>. Try opening multiple tabs!

## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 node server.js
```
