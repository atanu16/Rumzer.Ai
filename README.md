# Rumzer.Ai
Text to Image Generator | OpenAI


Note:This is a image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

<img src="public/img/screen.png" width="500">

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

or(if doesnt work)

```bash
npm run dev
```


Visit `http://localhost:3000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.
