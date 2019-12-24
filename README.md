# hello-node-world-by-express

## Startup

Install dependencies

```sh
npm install
```

Run

```sh
npm start
```

## Testing

```sh
npm test
```

## Startup by Docker Container

```sh
docker build -t hello-node-world-by-express:latest .
docker run -p 80:3000 -d -it --name app hello-node-world-by-express:latest
```
