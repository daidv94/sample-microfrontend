# Microfrontend

This is a very easy sample to get started with micro frontend architechtures

## Application overview

- Container

  Container app, you can call it a shell, contain all the other projects, route federation to other services. All the other team can work in independce.

- Cart

  Cart function, a micro frontend service

- Products

  Product function, simple list product

## Sample

### Container

Run `npm install && npm run start` and then access `http://localhost:8080`

### Cart

Run `npm install && npm run start` and then access `http://localhost:8082`

### Products

Run `npm install && npm run start` and then access `http://localhost:8081`

</br>

In this sample, I use the webpack module to try the micro frontend
