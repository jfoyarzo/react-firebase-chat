<a name="readme-top"></a>

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [📖 Firebase-Chat ](#-firebase-chat-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
    - [Deployment](#deployment)
  - [👥 Author ](#-author-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)


# 📖 Firebase-Chat <a name="about-project"></a>

**Firebase-Chat** is an app built as an exercise to understand how to integrate Firebase features with a react app. Uses Firebase authentication to implement Oauth and Cloud Firestore as the database to persist the chat history.


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>


<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://react.dev/">React</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://firebase.google.com/products/firestore">Cloud Firestore</a></li>
  </ul>
</details>


### Key Features <a name="key-features"></a>

- You can log in with your Google account.
- Chat history persisted in Firestore.
- Conditional render of components when a signed-in user is present.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

To run this project you need:
- Git
- Npm/Node.js

### Setup

Clone this repository to your desired folder using this command:

```
git clone git@github.com:jfoyarzo/react-firebase-chat.git
```

```
cd react-firebase-chat
```


### Install

Install this project's dependencies using:

  ```
  npm install
  ```

Since this project uses Firebase features, you need to supply your corresponding credentials by creating a `.env` file in the root of the app. You can use the provided `.env.example` file as a guide.

### Usage

To run the project, execute the following command from the root folder of the app:
```
npm start
```
this will start a development build on http://localhost:3000/


### Deployment

For production build use:

```
npm build
```


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Author <a name="authors"></a>

👤 **Felipe Oyarzo**

- GitHub: [@jfoyarzo](https://github.com/jfoyarzo)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/jorge-felipe-oyarzo-contreras)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page]([../../issues/](https://github.com/jfoyarzo/react-firebase-chat/issues)).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>


If you like this project please consider giving it a star!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

This project was built following the [How to Build a Real-time Chat App](https://www.freecodecamp.org/news/building-a-real-time-chat-app-with-reactjs-and-firebase/) Tutorial by [Timonwa Akintokun](https://www.freecodecamp.org/news/author/timonwa/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>