---
title: "Navigating multiple projects with IntelliJ & MacOS"
date: 2022-08-03
lastmod: 2022-08-03
draft: false
garden_tags: ["tooling"]
summary: "... I'm glad it's better now"
status: "evergreen"
---

Microservices are pretty common nowadays, and often services gets their own repo. That has pros and cons, but one of the biggest cons you see day-to-day is that navigating multiple projects in IntelliJ ~~isn't~~ wasn't a great experience.

- Do you switch between projects/folders in **IntelliJ**?
- Do you hate janky, slow UI reloads when switching projects?
- Are you on **MacOS**, and are on (or can get to) Big Sur or later?

If you answered yes to all of these questions, this post will interest you. Your IntelliJ can look like this:

{{< figure src="intellij_project_tabs.jpg" width="100%" >}}

You can even close/re-order tabs 😍

# How do I get this setup?

According to JetBrains, [this is a Big Sur only IntelliJ feature](https://intellij-support.jetbrains.com/hc/en-us/community/posts/360010142139/comments/360002541180). I guess it should also work on other JetBrains products, like WebStorm or PyCharm.

- Go to IntelliJ's preferences
- Go to Appearance & behaviour, then System Settings
- Choose "New window" or "Ask" (it's counter intuitive, I know!)
    - If you choose "Ask" and want a project to appear as a tab, choose "New window" in the popup dialogue when you open a project

{{< figure src="intellij_preferences.jpg" width="100%" >}}

- Go to MacOS System Settings
- Go to General
- Choose "always" for Prefer tabs

{{< figure src="macos_general_settings.jpg" width="100%" >}}

# Closing notes

- Thanks to a few Stack Overflow posts/answers/comments [1](https://stackoverflow.com/a/65451682/4261132), [2](https://stackoverflow.com/a/69350085/4261132), [3](https://stackoverflow.com/a/71495096/4261132). They helped clarify how the confusing setup should be done.
- Don't question why my default browser is Microsoft Edge