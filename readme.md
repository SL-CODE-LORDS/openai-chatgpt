<p align="center">
  <a href="" rel="noopener">
 <img width=100px height=100px src="https://1000logos.net/wp-content/uploads/2023/02/ChatGPT-Logo.png" alt="YT5S"></a>
</p>


<h2 align="center">OpenAI chatGPT - API</h2>






## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

API <a href="https://openai.com/" > [https://openai.com/] </a>

## 🏁 Getting Started <a name = "getting_started"></a>

This project was created using chatgpt 3.5 edition

### Installing


```sh
yarn add @sl-code-lords/openai-chatgpt
```

or

```sh
npm i @sl-code-lords/openai-chatgpt
```

## 🎈 Usage <a name="usage"></a>

```ts
const openai = require("@sl-code-lords/openai-chatgpt")

```

```ts
var result = await openai.chatgpt({api_key: "your_chatgpt_api", message: "Hello World!"})
```


```ts
//result

{
  status: true,
  code_creator: { name: 'Sisula Welgamage', github: '@sisula' },
  result: {
    model: 'gpt-3.5-turbo-0613',
    created: 1690112224,
    message: 'Hello! How can I assist you today?'
  }
}

```
## New Chat | Reset Session 

```ts
await openai.reset_session()
```
## ✍️ Authors <a name = "authors"></a>

- [@sisula welgamage](https://github.com/sisula) - project author

See also the list of [contributors](https://github.com/SL-CODE-LORDS/openai-chatgpt/contributors) who participated in this project.