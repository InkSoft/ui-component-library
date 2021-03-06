# SourceJS - Living Style Guide Platform

**The most advanced tool for documenting, testing and managing Front-end Components achieving productive team work.**

SourceJS powered workflow allows developers to **code new components directly in the documentation.** Combining web components development with documentation and team communication processes, makes SourceJS a powerful tool for Front-end developers and designers.

Check out short video overview:

[![image](http://d.pr/i/7Ax4+)](http://youtu.be/y4KHmX8vCc0)

Our main goal is to provide flexible, modular environment for managing reusable Front-end components library. We don't focus on specific technologies, allowing to seamlessly integrate SourceJS workflow with your existing codebase.

___


[**Source engine project page**](http://sourcejs.com) &nbsp;&nbsp;&nbsp; [**Documentation**](http://sourcejs.com/docs) &nbsp;&nbsp;&nbsp; [**Quick Start**](http://sourcejs.com/docs/base) &nbsp;&nbsp;&nbsp; [**Examples**](http://sourcejs.com/docs/base/#examples) &nbsp;&nbsp;&nbsp;[**FAQ**](https://github.com/sourcejs/Source/issues?q=is%3Aissue+label%3Afaq+) &nbsp;&nbsp;&nbsp;

___

SourceJS component management engine was originally developed in [OK.ru](http://corp.mail.ru/en/communications/odnoklassniki) front-end development team and is recommended for big and middle sized projects. Especially for fast growing web portals, outsource teams with similar project and companies with multiple services.

## Things that SourceJS is NOT

### Static site builder

**SourceJS is a dynamic Node.js application**, and does not build static website as Pattern Lab, KSS, StyleDocco are doing. Dynamic environment allows to connect unlimited number of plugins and middlewares for compiling docs, styles, text right on the flight.

### CSS Documentation parser

Engine is based on gathering special documentation files (`index.src` by default), where you leave your HTML examples, template calls and description. All Specs are located in `sourcejs/user/specs` folder, and could contain any catalogue structure, with focus on component folders.

**But** engine will support [DSS](https://github.com/darcyclarke/DSS) as a plugin, which is universal CSS Documentation parser. So it will be possible to document your components both in CSS, Markdown and native `index.src`.

## Join the community

Many teams are already using SourceJS for building and managing Front-end components libraries for themselves and their clients. To join the community, you just need to follow few simple rules - check our docs about [Maintaining](MAINTAINING.md) and [Contribution](CONTRIBUTING.md).

If you notice some bugs, or need to help finding a better solution in your process, feel free to create an issue, and we will solve your problem together.

## Updates
* 15.03.15. New example [Specs showcase](http://sourcejs.com/specs/examples/) ([source code](https://github.com/sourcejs/examples)) 
* 15.03.15. CSS Documentation support with DSS https://github.com/sourcejs/sourcejs-contrib-dss
* 12.03.15. **[0.5.0](https://github.com/sourcejs/Source/releases/tag/0.5.0) release** with full Markdown support, GitHub auth, `info.json` watchers and other improvements
* 24.02.15. [0.4.1](https://github.com/sourcejs/Source/releases/tag/0.4.1) patch release
* 05.02.15. Mentioned at in-depth [Style Guides Tools overview talk](http://youtu.be/Fr23VpM6wl4ds)
* 18.01.15. Published an [intro video about SourceJS](http://youtu.be/y4KHmX8vCc0)
* 07.01.15. **[0.4.0](https://github.com/sourcejs/Source/releases/tag/0.4.0) stable release.** From now, we move to fast, semantic release cycle. No globally breaking changes till 1.0.0
* 08.10.14. 0.4.0-rc release, migration [instructions](https://github.com/sourcejs/Source/tree/master/docs/migration)
* 01.08.14. [Video review](http://youtu.be/ukFeZnJjrLs?list=PL20zJcC2wnX7RY1CDrKLhSvYxEe6jtMbB) of SourceJS engine and workflow example (RU with EN subtitles)
* 31.07.14. 0.4.0-beta release
* 01.05.14. Engine presentation from [Front-end Ops Conf](http://www.feopsconf.com/), San Francisco - [Taking Development Tools To The Next Level](http://rhr.me/pres/ime/) with [video](https://www.youtube.com/watch?v=cMIad0zl00I)
* 31.01.14. [Preview](http://youtu.be/cefy_U5NU4o) of Source companion tool for prototyping interfaces using existing components
* 31.12.13. **0.3.2** release
* 09.10.13. Engine [presentation](http://rhr.me/pres/source-min/) on [Fronteers Jam](http://fronteers.nl/congres/2013/jam-session) ([video](https://vimeo.com/77989211))
* 23.09.13. Published [video recording](http://www.youtube.com/watch?v=3HNW5Bru0Ws) of Source engine presentation from [RIT++](http://ritconf.ru/) 2013 (RU)

## Upcoming updates

* Support of multiple documentation projects in one environment
* Screencasts and engine usage demos
* Full english documentation stack for core API
* Test coverage
* Stable v1.0.0 version

## Useful information

### Browser support

SourceJS client-side part is supported in all latest major browsers and IE8+ in [Clarify](http://sourcejs.com/docs/clarify) for testing components.

___

Copyright © 2013-2015 [SourceJS](http://sourcejs.com)

Licensed under [MIT License](http://en.wikipedia.org/wiki/MIT_License), read more at [license page](http://github.com/sourcejs/source/wiki/MIT-License).
