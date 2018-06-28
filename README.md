# ImgHorde
- Server that stores images to IPFS and disk.
- Images are content addressable by IPFS hash or sha256.

## Routes
### POST /images "store image"
### GET /images/:sha256 "get image"
### GET /images "list images"

## Install & Setup
```sh
git clone git@github.com:rgruesbeck/imghorde.git; cd imghorde
docker-compose run server npm install
```

## Run Development Server
### start
```sh
docker-compose up
```

## Test
```sh
docker-compose up
```
In another shell, run
```sh
npm test
```

### urls
- Images: [localhost:5000/images](http://localhost:5000/images)
- Ipfs Web Console: [localhost:5001/webui](http://localhost:5001/webui)

## Todo
- Get testing database
