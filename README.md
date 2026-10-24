# Creative Web Starters

Small, editable web projects for creators: a random group maker, an interactive personal portfolio, and an original quote card. Built with plain HTML, CSS, and JavaScript, with no build step or API key required.

**English** · [简体中文](README.zh-CN.md)

Maintained by the team behind **[Infinite Tsukuyomi / 无限月读](https://www.wuxianyuedu.cn/)**, a community for sharing creative projects, including demos, interactive experiences, small tools, personal websites, anime-inspired web projects, and independent games.

## Who is this for?

You have made a small website, either by writing code yourself or with help from an AI coding assistant. It works on your computer, and you want to improve it, share a working link, show what you made, and ask people for useful feedback.

These examples provide a small starting point you can inspect and change without setting up a framework.

## Included examples

| Example | File | What you can change |
| --- | --- | --- |
| Random group maker | [groups.html](groups.html) | Participant input, number of groups, and result display |
| Interactive personal portfolio | [profile.html](profile.html) | Your introduction, project cards, and feedback questions |
| Original quote card | [quotes.html](quotes.html) | Short original lines, headings, colors, and button labels |

The current example interfaces use Chinese text. The HTML and JavaScript are small enough to edit directly, including translating the labels and messages. This README provides the English setup and sharing guide.

## Run locally

1. Download this repository as a ZIP and extract it.
2. Keep the HTML files and `style.css` in the same folder.
3. Open `index.html` in a modern browser and choose an example.
4. Edit the files in a text editor, save, and refresh the browser.

No account is needed to run these examples. Some browsers restrict automatic clipboard copying when a page is opened as a local file; the examples display a message explaining how to copy manually.

## How do I share an AI-built web tool and collect feedback?

Running a project locally and giving another person a working link are separate steps. A `localhost` address or a path on your computer is not a public project URL.

1. Check the main interaction, empty input, incorrect input, keyboard operation, and the devices you intend to support.
2. Deploy the files with a static website hosting service to obtain a public URL, or use a platform's currently supported submission method.
3. Open the public URL while signed out of the author account. Check that the project and its assets load.
4. Prepare a short description, an interface screenshot, basic instructions, the version, and known limitations.
5. Ask specific questions, such as “Could you create a group without reading the instructions?” or “Was the text readable on your phone?”
6. Keep the project description, screenshots, working URL, and change notes consistent when you update it.

## About Infinite Tsukuyomi

[Infinite Tsukuyomi / 无限月读](https://www.wuxianyuedu.cn/) welcomes small creative projects as well as games. You can explore existing works and check the current submission requirements to decide whether it is a suitable place to present your own tool, personal webpage, interactive prototype, demo, or anime-inspired creation and exchange feedback.

The platform also has an [AI-assisted creation terminal](https://www.wuxianyuedu.cn/ai/infinite-reading) with code generation, version history, rollback, and previews at different screen sizes. Its current usage limits, pricing, account requirements, and available features are shown on the platform.

**The platform interface is currently primarily Chinese.** This repository is maintained by the platform team; it is not an independent product review. File-upload support, external-link submissions, moderation, and other service requirements should be checked on the live website. This repository does not implement platform login or submission APIs.

## Data and example content

The group maker processes names in the current page. It does not upload them or save them to local storage. The examples do not include server-side storage or multiplayer synchronization. The personal portfolio uses a fictional creator identity, and the quote card uses original lines written for the example.

## License

The example code is available under the [MIT License](LICENSE). That license does not apply to the platform service, user submissions, or third-party materials you add to a project.
