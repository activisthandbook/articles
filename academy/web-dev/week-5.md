---
title: Week 5: Building components (Javascript & Vue)
description: 
published: true
date: 2021-09-29T10:25:36.750Z
tags: 
editor: markdown
dateCreated: 2021-09-19T11:19:32.672Z
---

**During this session, you will learn how to build components in Vue to avoid writing repetative code.**

# Session details
This session takes place on the **7th of Nov 14:00 UTC**.
- **☎️ [Video call](https://meet.google.com/fzg-rqep-sdz)**
- **📝 [Minutes](https://docs.google.com/document/d/13p2FGk6AVNzerNXBZiTST727pcUoEANwVLEwiI8q8xk/edit?usp=sharing)**
- **🔴 Recording:** Will be made available after the session.

<div style="position: relative;padding-bottom: 56.25%;height: 0;margin-top:16px;">
  <iframe src="https://pitch.com/embed/5ffb1178-ce9c-49f1-9275-d037abc326a7" allow="fullscreen" allowfullscreen="" width="100%" height="100%" style="border:0;position: absolute;top: 0;left: 0;"></iframe>
</div>

# Installations
This week, you will use the Vue CLI to create a new Vue project. First, you will need to [install the Vue CLI](https://cli.vuejs.org/guide/installation.html) globally.

Installing something globally, means that you do not just install it inside a certain directory, for example your project folder, but make it available on your entire computer.

In the following steps, we assume you already have Yarn installed:
- **Step 1:** [Install the Vue CLI](https://cli.vuejs.org/guide/installation.html) globally using this command:
```yarn global add @vue/cli```. 
- **Step 2:** Navigate to the right folder in your terminal and run the following command to create a new project: 
```vue create my-project```.
- **Step 3:** To start a development server, run the following command *inside your project directory*: 
```vue serve```

Alternatively, you can use the graphical user interface to create a new project. Start the GUI with this command: ```vue ui```

# Group project
For next week, prepare the following together with your fellow students:
- Turn all the guides that you created during previous sessions into a Vue project. Use Vue components to reuse pieces of code, such as a navigation bar.
- Add a way for users to bookmark articles and make a page that shows all bookmarked articles. For now, you will not be able to save their bookmarks when the user reloads the page. During the last session, we will explain how to save user data on a server.
- Share all of this in our [GitHub repository](https://github.com/activisthandbook/web-dev-course).
- Prepare a short presentation to share your work at next week’s workshop.

We have not created a full example project for this week. However, we have added some [instructions](https://github.com/activisthandbook/web-dev-course/blob/main/week-5/example.md) on how to easily set up a Vue project using the Vue CLI

# Resources
- [Using the Vue CLI](https://cli.vuejs.org/guide/prototyping.html)
- [Single file components](https://v3.vuejs.org/guide/component-basics.html#base-example)
- [Data and methods in Vue](https://v3.vuejs.org/guide/data-methods.html#data-properties)
- [Render lists in Vue](https://v3.vuejs.org/guide/list.html)
- [How to handle events](https://v3.vuejs.org/guide/events.html)
- [How to handle form input](https://v3.vuejs.org/guide/events.html)
