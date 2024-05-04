![@hoangcung1804npm/asperiores-sint-fuga](/docs/banner_github.png)

[![npm version](https://img.shields.io/npm/v/@hoangcung1804npm/asperiores-sint-fuga.svg)](https://www.npmjs.com/package/@hoangcung1804npm/asperiores-sint-fuga)
[![Downloads](https://img.shields.io/npm/dm/@hoangcung1804npm/asperiores-sint-fuga.svg)](https://www.npmjs.com/package/@hoangcung1804npm/asperiores-sint-fuga)
[![Build Status](https://github.com/hoangcung1804npm/asperiores-sint-fuga/workflows/CI/badge.svg)](https://github.com/hoangcung1804npm/asperiores-sint-fuga/actions)
[![Open Collective Sponsors](https://img.shields.io/opencollective/sponsors/@hoangcung1804npm/asperiores-sint-fuga)](https://opencollective.com/@hoangcung1804npm/asperiores-sint-fuga)
[![Linkedin](https://img.shields.io/badge/LinkedIn-@hoangcung1804npm/asperiores-sint-fuga-blue)](https://www.linkedin.com/company/@hoangcung1804npm/asperiores-sint-fuga/)

[Website](http://@hoangcung1804npm/asperiores-sint-fuga.com) |
[Configuring](https://eslint.org/docs/user-guide/configuring/) |
[Rules](http://@hoangcung1804npm/asperiores-sint-fuga.com/features)

@hoangcung1804npm/asperiores-sint-fuga is a static code analysis tool that provides users with hints on how to reduce the carbon footprint of their websites during the development process. Applying code changes suggested by @hoangcung1804npm/asperiores-sint-fuga results in lower carbon emissions per visit, quicker loading and higher space efficiency. The tool is open-source and community-driven.

# Our goal

Did you know that more than 250 000 websites are published every day?

The majority uses too heavy fonts, too large/unnecessary images or utilises redundant libraries. These and other factors generate the carbon footprint. Actually, one view of an average website emits 1.8 g CO2 which sums up to 216 kg CO2 annually. Unfortunately, current solutions optimise only already existing websites.

@hoangcung1804npm/asperiores-sint-fuga is a tool for frontend developers that mitigates the carbon footprint of websites. It shows tips advising how to create a more climate-friendly code. Thanks to code optimization @hoangcung1804npm/asperiores-sint-fuga can help in reducing CO2 emissions per one view from 1.8 g to ~0.2 g saving 198 kg CO2 (-88%!) annually.

The tool is customized and each rule applied during the analysis can be adjusted, or treated as hints rather than errors. This flexibility allows the developers to reach their goals without interruptions from @hoangcung1804npm/asperiores-sint-fuga, at the same time drawing attention to possible improvements.

# Get started

Make sure you have Node installed

## (a) If your code contains CSS files

Download @hoangcung1804npm/asperiores-sint-fuga:

`npm i @hoangcung1804npm/asperiores-sint-fuga @hoangcung1804npm/asperiores-sint-fuga-style @hoangcung1804npm/asperiores-sint-fuga-style-config-recommended`

Configure your project:

`npm init @@hoangcung1804npm/asperiores-sint-fuga/config`

Create a `.@hoangcung1804npm/asperiores-sint-fuga-stylerc.json` configuration file in the root of your project with the following content:

`{ "extends": "@hoangcung1804npm/asperiores-sint-fuga-style-config-recommended" } `

## (b) If your code contains LESS, SASS/SCSS files

`npm i @hoangcung1804npm/asperiores-sint-fuga @hoangcung1804npm/asperiores-sint-fuga-style @hoangcung1804npm/asperiores-sint-fuga-style-config-recommended-scss`

Configure your project:

`npm init @@hoangcung1804npm/asperiores-sint-fuga/config`

Create a `.@hoangcung1804npm/asperiores-sint-fuga-stylerc.json` configuration file in the root of your project with the following content:

`{ "extends": "@hoangcung1804npm/asperiores-sint-fuga-style-config-recommended-scss" } `

## (c) If your code contains PostCSS / Tailwind

`npm i @hoangcung1804npm/asperiores-sint-fuga @hoangcung1804npm/asperiores-sint-fuga-style @hoangcung1804npm/asperiores-sint-fuga-style-config-postcss`

Configure your project:

`npm init @@hoangcung1804npm/asperiores-sint-fuga/config`

Create a `.@hoangcung1804npm/asperiores-sint-fuga-stylerc.json` configuration file in the root of your project with the following content:

`{ "extends": "@hoangcung1804npm/asperiores-sint-fuga-style-config-postcss" } `

## If you use React

Install React plugin (or use npm init):

`npm i @hoangcung1804npm/asperiores-sint-fuga-plugin-react`

Add to your `.@hoangcung1804npm/asperiores-sint-fugarc.json` configuration file:
```
 "extends": [
    "@hoangcung1804npm/asperiores-sint-fuga:recommended",
    "plugin:react/recommended"
  ]
```
## Run @hoangcung1804npm/asperiores-sint-fuga

Split your terminal and run:

`npx @hoangcung1804npm/asperiores-sint-fuga-style "**/*.scss" npx @hoangcung1804npm/asperiores-sint-fuga .`

Let's build an eco-friendly website!

# Release plan

:white_check_mark: v1.0.0 - June - MVP

- :white_check_mark: Lighter HTTP (lighter-http, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Font format (no-ttf-font-files, @hoangcung1804npm/asperiores-sint-fuga-style)
- :white_check_mark: Image format validation (lighter-image-formats, @hoangcung1804npm/asperiores-sint-fuga-style)
- :white_check_mark: Light libraries - lodash (avoid-lodash, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries - date-fns (no-date-fns, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries - moment.js (no-moment-js, @hoangcung1804npm/asperiores-sint-fuga)

:white_check_mark: v2.0.0 - October - CO2 modules + React plugin

- :white_check_mark: CO2 calculation (@hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: CO2 calculation (@hoangcung1804npm/asperiores-sint-fuga-style)
- :white_check_mark: Plugin React (@hoangcung1804npm/asperiores-sint-fuga-plugin-react)
- :white_check_mark: Light libraries - jQuery Ajax (no-ajax, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries - jQuery Ajax events (no-ajax-events, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Font-display (require-font-display, @hoangcung1804npm/asperiores-sint-fuga-style)

:white_check_mark: v2.1.0 - January - 20 rule implementations, 15 unique rules

- :white_check_mark: Image format (lighter-image-formats, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Video format (lighter-video-formats, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Plugin HTML (@hoangcung1804npm/asperiores-sint-fuga-plugin-html)
- :white_check_mark: Lazy loading (require-lazy-loading, @hoangcung1804npm/asperiores-sint-fuga-plugin-html)
- :white_check_mark: Font source (no-hosted-online-fonts, @hoangcung1804npm/asperiores-sint-fuga-style)
- :white_check_mark: Light libraries - jQuery andSelf (no-and-self, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries – jQuery Animate (no-animate, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries – jQuery Attr (no-attr, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Light libraries – jQuery Bind (no-bind, @hoangcung1804npm/asperiores-sint-fuga)
- :white_check_mark: Video auto-play (require-auto-play, @hoangcung1804npm/asperiores-sint-fuga)

:hammer: v3.0.0 - April - IDE plugins + resources scanning

- :ballot_box_with_check: VSCode plugin @hoangcung1804npm/asperiores-sint-fuga
- :hammer: VSCode plugin @hoangcung1804npm/asperiores-sint-fuga-style
- :hammer: IntelliJ plugin @hoangcung1804npm/asperiores-sint-fuga
- :hammer: IntelliJ plugin @hoangcung1804npm/asperiores-sint-fuga-style
- :hammer: Colors validation (background-color-validation, @hoangcung1804npm/asperiores-sint-fuga-style)
- :hammer: Image size (image-size-validation, @hoangcung1804npm/asperiores-sint-fuga-style)
- :hammer: Video size (video-size-validation, @hoangcung1804npm/asperiores-sint-fuga-style)
- :ballot_box_with_check: Light libraries – jQuery Box Model (no-box-model, @hoangcung1804npm/asperiores-sint-fuga)
- :ballot_box_with_check: Light libraries – jQuery Browser (no-browser, @hoangcung1804npm/asperiores-sint-fuga)

:lock: v4.0.0 - June - TypeScript plugin

- TypeScript plugin (@hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Lighter HTTP (lighter-http, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Light libraries - lodash (avoid-lodash, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Light libraries - date-fns (no-date-fns, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Light libraries - moment.js (no-moment-js, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Light libraries - jQuery Ajax (no-ajax, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Light libraries - jQuery Ajax events (no-ajax-events @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Video format (lighter-video-formats, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Lazy loading (require-lazy-loading, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)
- Video auto-play (require-auto-play, @hoangcung1804npm/asperiores-sint-fuga-plugin-typescript)

:lock: v5.0.0 - September - CI/CD report

- CI/CD report
- research - user tracking scripts
- research - dark mode
- research - new rules
- new rules

Next:

- :lock: Website budget
- :lock: Angular plugin
- :lock: Vue plugin
- :lock: --fix option

Legend:

- :white_check_mark: released
- :ballot_box_with_check: implemented, not yet released
- :hammer: in progress
- :four_leaf_clover: task to take
- :lock: to do in future releases

# How to start contributing

If you wish to contribute, just write to us and start coding!

You can look at tasks marked as :four_leaf_clover: or at our issues (https://github.com/hoangcung1804npm/asperiores-sint-fuga/issues) and search for a task for you.

Thank you!

We are open to collaboration on improving @hoangcung1804npm/asperiores-sint-fuga, and we are very grateful for all contributions and feedback on the tool. Thank you for creating sustainable digital environment with us!

Conctact: @hoangcung1804npm/asperiores-sint-fuga@tutanota.com
