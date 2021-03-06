# Github Repositories Picking App

An angular app which uses github api to get basic user details and have an option to pick the repositories

## Screen Shots
| Default Page | Picked Repositories |
| -------|--------------|
| <img src="./src/assets/img/ScreenShots/Default_page.PNG" width="300"> | <img src="./src/assets/img/ScreenShots/picked_repos.PNG" width="300"> |

## Functionality
* Can get user details by username
* Can see all the user repositories with star_count, fork_count and language
* Option of pick repo with username, star_count, fork_count and language
* Can remove the repo from picked repositories

## Getting started

**Warning**

> Verify that you are running at least node 8.9.x and npm 5.x.x by running node -v and npm -v in a terminal/console window. Older versions may produce errors.

1. Go to project folder and install dependencies.
 ```bash
 npm install --save
 ```

2. Launch development server:
 ```bash
 npm start
 ```
3. Go to http://localhost:4200 in your browser

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
