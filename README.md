# Getting Started
___

This was a project I followed along with for the [Modern React and Redux](https://www.udemy.com/react-redux/learn/v4/overview) course on Udemy.

> ### 1. Clone the repo.

```shell
git clone https://github.com/bbcharlton/React_YouTube_Ripoff.git
```

> ### 2. Install dependencies.

```shell
npm install
```

This loads in all the dependencies used in the application.

> ### 3. Add your Google Developer key.

Register an API key from [Google Developers Console](https://console.developers.google.com) and add the key to line 9 in the **API_KEY** constant in `index.js`.

> ### 4. Run Server.

```shell
npm start
```

This will use webpack and Babel to compile all code into a `bundle.js` file that runs on the page.

> ### 5. Open localhost:8080

Navigate to **localhost:8080** in your browser. The page should load an application that replicates YouTube to a degree using React, Redux, and the YouTube API.
