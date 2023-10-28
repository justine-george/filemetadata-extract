# File Metadata Microservice

A microservice that extracts metadata of the uploaded file.

## Live Demo

Check out the microservice [here](https://filemetadata-extract.fly.dev/).

## Usage

Upload a file and the microservice will return the metadata of the file.

## Example Output

```json
{
  "name": "test.txt",
  "type": "text/plain",
  "size": 4
}
```

## Tech Stack

- Node.js
- Express.js
- Multer
- fly.io

## Run locally

```
npm install
npm start
```

## Deploy on fly.io

```
fly launch
fly deploy
```
