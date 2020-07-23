# Testing React Applications 🧐

👋 hi there! My name is [Kent C. Dodds](https://kentcdodds.com)! This is a
workshop repo to teach you about increasing your deploy confidence by using Jest
and React Testing Library to test your react components.

<div align="center">
  <h2><a href="https://epicreact.dev">EpicReact.Dev</a></h2>
  <a href="https://epicreact.dev">
    <img
      alt="Learn React from Start to Finish"
      src="https://kentcdodds.com/images/epicreact-promo/er-1.gif"
    />
  </a>
</div>

<hr />

[![Travis Build Status][build-badge]][build]
[![AppVeyor Build Status][win-build-badge]][win-build]
[![GPL-3.0 License][license-badge]][license]
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome][prs-badge]][prs] [![Code of Conduct][coc-badge]][coc]

## Pre-Workshop Instructions/Requirements

In order for us to maximize our efforts during the workshop, please complete the
following things to prepare.

- 📺 only necessary if the workshop is remote via Zoom
- 👋 specific to the material for this workshop

- [ ] 👋 Setup the project (follow the setup instructions below) (~5 minutes)
- [ ] 📺 Install and setup [Zoom](https://zoom.us) on the computer you will be
      using (~5 minutes)
- [ ] 📺 Watch
      [Use Zoom for KCD Workshops](https://egghead.io/lessons/egghead-use-zoom-for-kcd-workshops)
      (~8 minutes).
- [ ] 👋 Watch [The Beginner's Guide to React](https://kcd.im/beginner-react)
      (available free on Egghead.io), or have the equivalent experience with
      React (147 minutes)
- [ ] 👋 Go through my
      [Learn React Hooks Workshop](https://kentcdodds.com/workshops/hooks), or
      have the equivalent basic experience of using hooks. You should be
      experienced with `useState`, `useEffect`, and `useRef`.
- [ ] 👋 Go through my
      [Advanced React Hooks](https://kentcdodds.com/workshops/advanced-react-hooks),
      or have the equivalent basic experience of using advanced hooks. You
      should be experienced with `useContext`, `useReducer`, `useMemo`, and
      `useCallback`.

The more prepared you are for the workshop, the better it will go for you.

## System Requirements

- [git][git] v2 or greater
- [NodeJS][node] v10 or greater
- [npm][npm] v6 or greater

All of these must be available in your `PATH`. To verify things are set up
properly, you can run this:

```shell
git --version
node --version
npm --version
```

If you have trouble with any of these, learn more about the PATH environment
variable and how to fix it here for [windows][win-path] or
[mac/linux][mac-path].

## Setup

After you've made sure to have the correct things (and versions) installed, you
should be able to just run a few commands to get set up:

```
git clone https://github.com/kentcdodds/testing-react-apps.git
cd testing-react-apps
npm run setup --silent
```

If you get any errors, please read through them and see if you can find out what
the problem is. If you can't work it out on your own then please [file an
issue][issue] and provide _all_ the output from the commands you ran (even if
it's a lot).

## Running the app

To get the app up and running (and really see if it worked), run:

```shell
npm start
```

This should start up your browser. If you're familiar, this is a standard
[react-scripts](https://create-react-app.dev/) application.

You can also open
[the deployment of the app on Netlify](https://testing-react-apps.netlify.app/).

There's not much to it. The whole reason we have the app is just so you can see
examples of the components that we'll be testing.

## Running the tests

```shell
npm test
```

This will start [Jest](https://jestjs.io/) in watch mode. Read the output and
play around with it. All the tests will start out in a passing state. Your job
will be to follow the emoji's instructions to test the components using the
tools and patterns described.

## Workshop Outline

> Let's get some rock-solid confidence in our React Apps! 💎

👋 I'm Kent C. Dodds

- 🏡 Utah
- 👩 👧 👦 👦 👦 🐕
- 🏢 https://kentcdodds.com
- 🐦/🐙 @kentcdodds
- 🏆 https://testingjavascript.com
- 🥚 https://kcd.im/egghead
- 🥋 https://kcd.im/fem
- 💌 https://kcd.im/news
- 📝 https://kcd.im/blog
- 📺 https://kcd.im/devtips
- 💻 https://kcd.im/coding
- 📽 https://kcd.im/youtube
- 🎙 https://kcd.im/3-mins
- ❓ https://kcd.im/ama

### Schedule

- 😴 Logistics
- 💪 01. simple test with ReactDOM
- 💪 02. simple test with React Testing Library
- 😴 10 Minutes
- 💪 03. Avoid implementation details
- 💪 04. form testing
- 🌮 30 Minutes
- 💪 05. mocking HTTP requests
- 💪 06. mocking Browser APIs and modules
- 😴 10 Minutes
- 💪 07. testing with context and a custom render method
- 😴 10 Minutes
- 💪 08. testing custom hooks
- ❓ Q&A

### Questions

Please do ask! Interrupt me. If you have an unrelated question, please ask on
[my AMA](https://kcd.im/ama).

### Zoom (for remote workshops)

- Help us make this more human by keeping your video on if possible
- Keep microphone muted unless speaking
- Breakout rooms

### Exercises

- `src/__tests__/exercise/00.md`: Background, Exercise Instructions, Extra
  Credit
- `src/__tests__/exercise/00.js`: Exercise with Emoji helpers
- `src/__tests__/final/00.js`: Final version
- `src/__tests__/final/00.extra-0.js`: Final version of extra credit

The purpose of the exercise is **not** for you to work through all the material.
It's intended to get your brain thinking about the right questions to ask me as
_I_ walk through the material.

### Helpful Emoji 🐨 💪 🏁 💰 💯 🦉 📜 💣 👨‍💼 🚨

Each exercise has comments in it to help you get through the exercise. These fun
emoji characters are here to help you.

- **Kody the Koala Bear** 🐨 will tell you when there's something specific you
  should do
- **Matthew the Muscle** 💪 will indicate what you're working with an exercise
- **Chuck the Checkered Flag** 🏁 will indicate that you're working with a final
  version
- **Marty the Money Bag** 💰 will give you specific tips (and sometimes code)
  along the way
- **Hannah the Hundred** 💯 will give you extra challenges you can do if you
  finish the exercises early.
- **Olivia the Owl** 🦉 will give you useful tidbits/best practice notes and a
  link for elaboration and feedback.
- **Dominic the Document** 📜 will give you links to useful documentation
- **Berry the Bomb** 💣 will be hanging around anywhere you need to blow stuff
  up (delete code)
- **Peter the Product Manager** 👨‍💼 helps us know what our users want
- **Alfred the Alert** 🚨 will occasionally show up in the test failures with
  potential explanations for why the tests are failing.

## Workshop Feedback

Each exercise has an Elaboration and Feedback link. Please fill that out after
the exercise and instruction.

At the end of the workshop, please go to this URL to give overall feedback.
Thank you! https://kcd.im/tra-ws-feedback

## Contributors

Thanks goes to these wonderful people
([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://kentcdodds.com"><img src="https://avatars.githubusercontent.com/u/1500684?v=3" width="100px;" alt=""/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="https://github.com/kentcdodds/testing-react-apps/commits?author=kentcdodds" title="Code">💻</a> <a href="https://github.com/kentcdodds/testing-react-apps/commits?author=kentcdodds" title="Documentation">📖</a> <a href="#infra-kentcdodds" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/kentcdodds/testing-react-apps/commits?author=kentcdodds" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://relayr.io/"><img src="https://avatars1.githubusercontent.com/u/32642691?v=4" width="100px;" alt=""/><br /><sub><b>Gautam Pahuja</b></sub></a><br /><a href="https://github.com/kentcdodds/testing-react-apps/commits?author=gautam-pahuja" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://github.com/pom421"><img src="https://avatars1.githubusercontent.com/u/3749428?v=4" width="100px;" alt=""/><br /><sub><b>pom421</b></sub></a><br /><a href="https://github.com/kentcdodds/testing-react-apps/commits?author=pom421" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/kentcdodds/all-contributors)
specification. Contributions of any kind welcome!

<!-- prettier-ignore-start -->
[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[git]: https://git-scm.com/
[build-badge]: https://img.shields.io/travis/com/kentcdodds/testing-react-apps.svg?style=flat-square&logo=travis
[build]: https://travis-ci.com/kentcdodds/testing-react-apps
[license-badge]: https://img.shields.io/badge/license-GPL%203.0%20License-blue.svg?style=flat-square
[license]: https://github.com/kentcdodds/react-fundamentals/blob/master/LICENSE
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[coc]: https://github.com/kentcdodds/testing-react-apps/blob/master/CODE_OF_CONDUCT.md
[emojis]: https://github.com/kentcdodds/all-contributors#emoji-key
[all-contributors]: https://github.com/kentcdodds/all-contributors
[win-path]: https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/
[mac-path]: http://stackoverflow.com/a/24322978/971592
[issue]: https://github.com/kentcdodds/testing-react-apps/issues/new
[win-build-badge]: https://img.shields.io/appveyor/ci/kentcdodds/testing-react-apps.svg?style=flat-square&logo=appveyor
[win-build]: https://ci.appveyor.com/project/kentcdodds/testing-react-apps
<!-- prettier-ignore-end -->
