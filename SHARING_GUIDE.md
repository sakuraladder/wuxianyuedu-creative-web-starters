# Share a small web project and collect useful feedback

[简体中文](SHARING_GUIDE.zh-CN.md) · [Examples and repository overview](README.md)

This guide is for a web tool, interactive page, personal portfolio, or early demo made with an AI coding assistant or by writing code yourself. It uses the random group maker in this repository as a working example.

## 1. Check what the project needs to run

Open [the group maker](https://sakuraladder.github.io/wuxianyuedu-creative-web-starters/groups.html). The example reads names, creates groups, and displays a result in the current browser page. It does not need a server, account, API key, or database.

A folder containing HTML, CSS, JavaScript, and local assets can often use static hosting. A project that needs a backend, shared records, or an external API needs those services configured separately. A static host does not add them automatically.

Keep the files together. Check that links and asset paths work from the project folder; a link starting with `/` points to the domain root and may behave differently from a relative link.

## 2. Get a public experience link

This repository's [online examples](https://sakuraladder.github.io/wuxianyuedu-creative-web-starters/) use GitHub Pages. For a similar static project:

1. Put the files you intend to publish in a repository you control, with `index.html` at the entry point.
2. Open the repository's **Settings → Pages**.
3. For a simple project without a build step, choose **Deploy from a branch**, select the source branch and folder, and save.
4. Wait for deployment, then use the site URL shown in Pages settings.

Review the hosting service's current requirements and usage limits before relying on it. GitHub's [Pages setup guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [publishing-source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) explain the available options.

A `localhost` address or a file path on your computer is not a public experience link. Sharing a source-code page is also different from sharing a running webpage.

## 3. Check the link as a visitor

Use a browser that is signed out of the author account:

- Open the page and its main links. Check images and styles as well as the first screen.
- Complete the main task. For the group maker, enter six sample names, select two groups, and confirm each name appears once and each group has three entries.
- Try an empty list and a group count greater than the number of names. The example should explain the problem and hide the previous result.
- Test the devices and browsers you intend to support. Record what you tested; leave other environments unverified.

These checks describe the example's expected behavior. They do not establish compatibility for a project you have changed.

## 4. Give people enough information to try it

Use the [project brief template](PROJECT_BRIEF_TEMPLATE.md) to record the purpose, working URL, creator, current version, instructions, account or payment requirements, tested devices, and known limitations.

For the group maker, a clear first task is: “Create two groups from the six sample names.” Two useful questions are:

- Could you finish the task without help?
- What happened when you entered more groups than participants?

For an interactive portfolio, ask a visitor to find one project and open its experience link. For an interactive card or demo, identify the action you want tested and the unfinished parts.

## 5. Choose a place for presentation and discussion

Hosting provides a running URL. A project page or community post can add the author introduction, screenshots, context, and a feedback channel. Check the chosen community's current rules and disclose your relationship to the project.

[Infinite Tsukuyomi / 无限月读](https://www.wuxianyuedu.cn/) is the creator community maintained by this repository's team. It welcomes demos, interactive experiences, small tools, personal websites, anime-inspired projects, and games. Browse existing works and check the live submission instructions for the formats, account requirements, and conditions that apply to your project. This tutorial's running examples are hosted on GitHub Pages.

The platform and current example interfaces are primarily Chinese. English setup instructions are available in this repository.

## 6. Turn feedback into a change someone can check

Use the [feedback template](FEEDBACK_TEMPLATE.md). Keep the task, steps, expected result, and actual result together. After a change, update the version or date, explain what changed, and ask someone to repeat the same task. Keep the project description, screenshots, and experience link consistent with that version.

For problems with this repository's examples, [open a GitHub issue](https://github.com/sakuraladder/wuxianyuedu-creative-web-starters/issues/new). Submitting an issue requires a GitHub account. For your own project, provide the feedback channel you actually maintain.

Maintained by the Infinite Tsukuyomi platform team. This guide was prepared with AI assistance and documents a public static-web example. See the [repository license](LICENSE).
