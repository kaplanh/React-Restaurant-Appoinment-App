# React Restaurant Appoinment App

[:point_right: Click here to see on browser](https://restaurant-appointment.netlify.app/)

![restaurant appointment](https://github.com/kaplanh/React-Restaurant-Appoinment-App/assets/101884444/c9b040e8-917d-469a-9414-0cc958ff3c4c)


---

| **What's used in this app ?**                                                           | **How use third party libraries**          | **Author**                                                                       |
| --------------------------------------------------------------------------------------- | ------------------------------------------ | -------------------------------------------------------------------------------- |
| [lifting state up](https://react.dev/learn/sharing-state-between-components)            |                                            | [Take a look at my portfolio](https://kaplanh.github.io/Portfolio_with_CssFlex/) |
| [useState() Hook](https://react.dev/learn#using-hooks)                                  |                                            | [Visit me on Linkedin](https://www.linkedin.com/in/kaplan-h/)                    |
| [react-events](https://react.dev/learn#responding-to-events)                            |                                            |                    |
| [React-Conditional rendering](https://react.dev/learn#conditional-rendering)            |                                            |                                                                                  |
| [React-Bootstrap](https://react-bootstrap.netlify.app/)                                 | npm i / yarn add react-bootstrap bootstrap |                                                                                  |
| [React-icons](https://react-icons.github.io/react-icons/)                               | npm i / yarn add react-icons               |                                                                                  |
| [props-drilling](https://react.dev/learn#sharing-data-between-components)               |                                            |                                                                                  |
| [Semantic-Commits](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) |                                            |                                                                                  |
| Deploy with [Netlify](https://app.netlify.com/teams/kaplanh/sites)                                      |                                            |                                                                                  |

---

## How To Run This Project 🚀

<br/>

### 💻 Install React 👇

```bash
yarn create react-app .  or npx create-react-app .
```

### 💻 Install Sass 👇

```bash
yarn add sass  or npm i sass
```

## 🔴 Delete these files and delete the imports👇

    - App.test.js
    - reportWebVitals.js
    - setupTests.js
    - favicon.ico
    - logo192.png
    - logo512.png
    - manifest.json
    - robots.txt

### 💻 Start the project 👇

```bash
yarn start or npm start
```

OR

-   <strong>Clone the Repo</strong>

    ```sh
    git clone
    ```

-   <strong>Install NPM packages</strong>

    ```sh
    npm install or yarn
    ```

-   <strong>Run the project</strong>

    ```sh
    npm start or yarn start
    ```

-   <strong>Open the project on your browser</strong>

    ```sh
    http://localhost:3000/
    ```

-   ### <strong>Enjoy! 🎉</strong>

---

## Project Skeleton

```
React Restaurant Appoinment App  (folder)
|
|----readme.md         
|       
├── public
│     └── index.html
├── src
│    ├── components
│    │       ├── AddModal.jsx
│    │       │
│    │       ├── Appointment.jsx.jsx
│    │       │
│    │       ├── Restaurant.jsx
│    │
│    ├──────pages
│    │         ├── Home.jsx
│    │
│    │──────helper
│    │         ├── data.jsx
│    │
│    ├── App.js
│    ├── index.js
│    └── index.css
├── package.json
└── yarn.lock


```

---

### At the end of the project, the following topics are to be covered;

-   Lifting state up

  

-   conditional rendering + cconditional Css

  

-   tiklananin id sine göre objenin icindeki boolean degeri degiline cevirme toggle yapma

    ```jsx
        setApps(
                apps.map((item) =>
                    item.id === id ? { ...item, consulted: !item.consulted } : item
                )
            );
        };
    ```

-   tiklananin id sine göre filter ile silme

    ```jsx
        const handleDelete = (id) => {{
            setApps(apps.filter((item) => item.id !== id));
        };
    ```

-   Css ::after

    ```css
    .consulted::after {
        content: "CONSULTED";
        background-color: rgb(166, 18, 189);
        color: white;
        font-size: 2rem;
        border-radius: 1rem;
        position: absolute;
        left: 50%;
        top: 50%;
        padding: 0.5rem;
        transform: translate(-50%, -50%);
    }
    ```

-   Semantic Commit Messages
    See how a minor change to your commit message style can make you a better programmer.

    Format: <type>(<scope>): <subject>

    <scope> is optional

    -   Example

    ```
                feat: add hat wobble
        ^--^  ^------------^
        |     |
        |     +-> Summary in present tense.
        |
        +-------> Type: chore, docs, feat, fix, refactor, style, or test.
    ```

- More Examples:
       -   `feat`: (new feature for the user, not a new feature for build script)
      -   `fix`: (bug fix for the user, not a fix to a build script)
       -   `docs`: (changes to the documentation)
       -   `style`: (formatting, missing semi colons, etc; no production code change)
      -   `refactor`: (refactoring production code, eg. renaming a variable)
      -   `test`: (adding missing tests, refactoring tests; no production code change)
      -   `chore`: (updating grunt tasks etc; no production code change)

---

## Feedback and Collaboration

I value your feedback and suggestions. If you have any comments, questions, or ideas for improvement regarding this project or any of my other projects, please don't hesitate to reach out.
I'm always open to collaboration and welcome the opportunity to work on exciting projects together.
Thank you for visiting my project. I hope you have a wonderful experience exploring it, and I look forward to connecting with you soon!

<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>
