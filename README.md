# Rumzer.Ai
Text to Image Generator | OpenAI

https://user-images.githubusercontent.com/83860778/215260868-985d1e42-e94d-4023-9a87-a325b1103f65.mp4

Note:This is a image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.


## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm i express openai dotenv
```

```bash
npm i -D nodemon
```

```bash
npm install
```

Run server

```bash
npm start
```

or (if doesnt work)

```bash
npm run dev
```


Visit `http://localhost:3000` in your browser.

The endpoint is at `POST http://localhost:3000/openai/generateimage`.
