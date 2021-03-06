## Solitaire

A very basic solitaire clone.
Demo available at https://js-solitaire.surge.sh


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), and has [tailwindcss](https://tailwindcss.com) wired up.

### Todo

- [ ] Add ruleset for only allowing alternating colors on tableaus
- [ ] Add config menu to allow for switching rulesets
- [ ] Implement drag and drop
- [ ] Keep score across multiple games
- [x] Add reset / config button somewhere - partially done (reset) - may also want config menu here
- [x] Fix Reset - ~~For some reason the deck initializes correctly the first deal - but on a reset the deck is completely broken - I cannot find a reason for this - it almost appears as if some values are being cached or something...~~ This may have just been a misunderstanding on my part about how the react reducer hook uses initialstate, but it seems that the values were being memoized or something.... I had to set initialState to functions to get it to calculate new values.
- [x] Implement using the stock
- [x] Fix stock visible pile rendering when # of cards changes.
- [x] Implement win condition - At least partially implemented
- [x] Display win condition
- [x] Fix piles re-rendering on every state change
      -- Had some odd issues where this seemed like it wasnt working
      -- but appears to be ok in chrome and firefox now.
      -- will continue to watch.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
