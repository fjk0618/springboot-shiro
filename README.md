Nightwatch.js
npm Node.js CI codecov Discord

Nightwatch.js Logo

Homepage • Developer Guide • API Reference • About • Blog
Nightwatch is an integrated testing framework powered by Node.js and using the W3C Webdriver API. It is a complete testing solution developed at BrowserStack and which can be used for:

☑️ end-to-end testing of web applications and websites

☑️ component testing in isolation (React / Vue / Storybook / Angular)

☑️ Node.js unit, visual regression testing, accessibility testing & API testing

☑️ Native mobile app testing on Android & iOS

🚀 Nightwatch v3
What's New | Release Notes | Discussions

Nightwatch v3 is an all new generation that has been built around these three pillars:

Developer Experience : The entire experience from getting started, to writing and debugging tests, has been redesigned for speed, stability, and consistent non-flaky results.

Mobile first: Test your web or native, iOS and Android, mobile applications on simulators, real mobile devices or a cloud grid like BrowserStack.

One test automation framework: Run all types of tests from unit, component, and E2E to API, visual, and accessibility with a single framework.

The Nightwatch v3 is not just a new version, it’s the result of months of engineering effort to reimagine test automation for the future. Try it out in 60 seconds and see it in action.

⚙️ Get started in 60 seconds
1. Install Nightwatch from NPM
From your existing project's root dir:

npm init nightwatch@latest
or, if you want to initialize a new project:

npm init nightwatch@latest ./path/to/new/project
nightwatch-cli-gif

2. Answer a few questions about your preferred setup:
What is your Language - Test Runner setup?
Where do you want to run your e2e tests?
Where you'll be testing on?
Where do you plan to keep your end-to-end tests?
What is the base_url of your project?
Nightwatch will do the entire setup for you based on your answers.

3. Run a Demo Test:
Nightwatch comes with a few examples, which are automatically copied to your Nightwatch project during the setup and can also be used as boilerplate to write your own tests on top of them.

You can follow the instructions given at the end of the setup to run your first test with Nightwatch.

image

Nightwatch mobile app testing
Nightwatch enables automation testing of native mobile applications via Appium. It combines the robustness of Appium with the enhanced developer experience provided by Nightwatch. It enables end-to-end functional testing of native mobile apps on Android and iOS devices. Try it now

Go beyond E2E
Component testing
With Nightwatch you can test components in isolation by mounting them in the browser. Nightwatch 2 added support for component testing for popular web frameworks such as

React
VueJS
Angular
Storybook
Nightwatch unit tests
The tests for Nightwatch are written using Mocha.

Clone the project

git clone https://github.com/nightwatchjs/nightwatch.git

# change directory
cd nightwatch

# install the dependencies
npm install
Run tests

To run the complete test suite:

npm test
To check test coverage, run the command:

npm run mocha-coverage
and then open the generated coverage/index.html file in your browser.

See Unit testing guide for more details.

Other types of testing
Visual Regression Testing
Nightwatch v3 introduces visual regression testing as an in-house plugin. The plugin takes care of

Capturing screenshots
Comparison with baseline to highlight visual differences
Report to review the differences
Approve the changes
VRT can be done on real desktop & mobile browsers. Also, VRT can be run on components as part of component testing as well.

API Testing
API testing is now available with Nightwatch v3. The following functionality can be achieved with API testing

Request assertions
Response assertions
Viewing API tests in the HTML report
Mock server
Accessibility Testing
Nightwatch v3 packages the aXe-core package developed by Deque Systems as a plugin. It enables 90 different types of accessibility tests for WCAG compliance.

🦉 About Nightwatch
Nightwatch was initially built by @pineviewlabs - an independent software consultancy based in Oslo, Norway, with help from contributors. In mid 2021, Nightwatch has become a part of the @BrowserStack family and it is being developed further at the BrowserStack Open-source Program Office. Read more on our blog.

Contributing
We welcome any and all contributions from the community which can help improve Nightwatch. Please check out CONTRIBUTING.md for more extensive contributing guidelines.

Licence
MIT
