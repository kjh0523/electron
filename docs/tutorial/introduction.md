---
title: 'Introduction'
description: 'Welcome to the Electron documentation! If this is your first time developing an Electron app, read through this Getting Started section to get familiar with the basics. Otherwise, feel free to explore our guides and API documentation!'
slug: /latest/
hide_title: false
---

# Electron은 무엇인가?

Electron is a framework for building desktop applications using JavaScript,
HTML, and CSS. By embedding [Chromium][chromium] and [Node.js][node] into its
binary, Electron allows you to maintain one JavaScript codebase and create
cross-platform apps that work on Windows, macOS, and Linux — no native development
experience required.

## 시작하기
우리는 Electron 앱을 만들고 사용자에게 배포하는 것을 설명하는 [tutorial][]과 함께 시작하기를 권합니다. 
[examples][]와 [API documentation][]도 새로운 것을 발견하기 위한 좋은 도구 입니다.

## Electron Fiddle과 함께 예제 실행하기

[Electron Fiddle][fiddle] is a sandbox app written with Electron and supported by
Electron's maintainers. We highly recommend installing it as a learning tool to
experiment with Electron's APIs or to prototype features during development.

Fiddle also integrates nicely with our documentation. When browsing through examples
in our tutorials, you'll frequently see an "Open in Electron Fiddle" button underneath
a code block. If you have Fiddle installed, this button will open a
`fiddle.electronjs.org` link that will automatically load the example into Fiddle,
no copy-pasting required.

```fiddle docs/fiddles/quick-start
```

## 문서에 무엇이 있는가?

All the official documentation is available from the sidebar. These
are the different categories and what you can expect on each one:

- **Tutorial**: An end-to-end guide on how to create and publish your first Electron
  application.
- **Processes in Electron**: In-depth reference on Electron processes and how to work with them.
- **Best Practices**: Important checklists to keep in mind when developing an Electron app.
- **Examples**: Quick references to add features to your Electron app.
- **Development**: Miscellaneous development guides.
- **Distribution**: Learn how to distribute your app to end users.
- **Testing And Debugging**: How to debug JavaScript, write tests, and other tools used
  to create quality Electron applications.
- **References**: Useful links to better understand how the Electron project works
  and is organized.
- **Contributing**: Compiling Electron and making contributions can be daunting.
  We try to make it easier in this section.

## 도움말 얻기

Are you getting stuck anywhere? Here are a few links to places to look:

- 만약 당신이 앱을 개발하는데 도움을 필요로한다면, 우리 [community Discord server][discord]는 다른 앱 개발자들로부터 조언을 얻을 수 있는 좋은 곳입니다. 
- If you suspect you're running into a bug with the `electron` package, please check
  the [GitHub issue tracker][issue-tracker] to see if any existing issues match your
  problem. If not, feel free to fill out our bug report template and submit a new issue.

<!-- Links -->

[tutorial]: tutorial-1-prerequisites.md
[api documentation]: ../api/app.md
[chromium]: https://www.chromium.org/
[discord]: https://discord.gg/electronjs
[examples]: examples.md
[fiddle]: https://electronjs.org/fiddle
[issue-tracker]: https://github.com/electron/electron/issues
[node]: https://nodejs.org/
