# Rubric Creator

Create and share rubrics for grading papers. Made for teachers by [The Graide Network](https://www.thegraidenetwork.com/).

<!-- Badges will go here
[ ![Codeship Status for thegraidenetwork/ngx-bing-spellchecker](https://app.codeship.com/projects/8c3e2310-a6c5-0135-9962-3a5d1d8055ee/status?branch=master)](https://app.codeship.com/projects/255625)
[![npm version](https://badge.fury.io/js/ngx-bing-spellchecker.svg)](https://badge.fury.io/js/ngx-bing-spellchecker)
-->

![](https://i.imgur.com/Q6xO1eV.gif)

## Development

While this product is freely available on the web, you may also want to customize it or submit improvements. The guide below should help you get started.

### Prerequisites
- Node 7.0+
- NPM 5.0+

### Installation

- Clone this repository: `git clone git@github.com:thegraidenetwork/rubric-creator.git`
- Install npm dependencies: `npm install`
- Run the development server: `ng serve`

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

If you want to test the service worker or offline functionality:

- Build the files for production: `ng build --prod`.
- Install Node HTTP Server globally (should just need to do once): `npm install -g http-server`.
- Navigate to the dist folder: `cd dist`.
- And run the server: `http-server -c-1 .`.

Your app should be running in production mode at `http://localhost:8080/`.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Linting

Run `ng lint` to execute the linter via [TSLint](https://palantir.github.io/tslint/).

### Building

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build and the `--aot` flag for ahead-of-time compilation (recommended).

## Contributing

Contributions are welcome and encouraged to this open source project. Please be sure to [submit an issue on Github](https://github.com/thegraidenetwork/rubric-creator/issues) to solicit discussion before jumping in as someone else might be working on the same thing.

## Deploying

Once you have built the files, you can copy them into a file hosting service like Azure's Blob Storage or Amazon S3.

- [Tutorial for Azure](https://blog.lifeishao.com/2017/05/24/serving-your-static-sites-with-azure-blob-and-cdn/)
- [Tutorial for S3](https://johnlouros.com/blog/host-your-angular-app-in-aws-s3)

## Special Thanks

This project was built on the back of many great open source projects. Here are a few of them:

- [Angular](https://angular.io/)
- [NGRX Store, Effects](https://github.com/ngrx/platform)
- [@ngx-pwa/local-storage](https://www.npmjs.com/package/@ngx-pwa/local-storage)
- [JSONbin.io](https://jsonbin.io/)
- [Bootstrap](https://getbootstrap.com/)
- [iconic icons](https://useiconic.com/open/)

## License

Copyright 2018, [The Graide Network](https://www.thegraidenetwork.com/)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
