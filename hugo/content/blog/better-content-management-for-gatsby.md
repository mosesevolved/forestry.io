---
title: Better Content Management (CMS) for Gatsby
description: ''
date: 2018-11-21 23:22:29 -1100
authors:
- Sebastian Engels
publishdate: 2018-12-05 17:00:00 -1100
expirydate: 2030-01-01 04:00:00 +0000
headline: ''
textline: ''
images: []
categories:
- CMS
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
private: false
weight: ''
aliases: []
menu: []
draft: true

---
With Gatsby you can create anything from Progressive Web Apps to content-driven blogs. It is one of the most flexible and most popular static site generators. With that flexibility we face tougher design challenges especially surrounding how to structure our data. That doesn't mean we should make compromises on our workflow and how we store our code, content and data.

Forestry now supports Gatsby and makes content management a lot easier for your Gatsby projects without having to learn an entirely new workflow.

_How to store content with Gatsby?_  
We've been closely watching the hype around Gatsby and are happy to see that Markdown has become the format of choice to edit, update and store your content-heavy Gatsby site (see Gatsby’s [tutorial](https://www.gatsbyjs.org/tutorial/part-six/#transformer-plugins) or [gatsbyjs.org](https://gatsbyjs.org)). With separating content from code layout, it is not interrupted by obtrusive markup, can be organized easily in your filesystem and edited with any code editor. This is the most frictionless way to work with content from a developer's perspective.

_What is the conflict?_
As with any other website or project, most of the time we work in teams or for teams. These teams usually include non-tech people and clients, these types of users need to be able to edit content on a regular basis as well. However, most marketers, writers and clients don’t feel at home with Markdown. Navigating the file system and using the code editor can easily feel foreign. However, to be able to do what they do best, they need to feel comfortable making changes. 

To enable other users to make edits to sites we use content management systems (CMS). Using a CMS usually takes over handling our content, data and forces us (at least partially) to use a specific workflow. However, as developers direct access to our data and seeing how it's structured speeds up our workflow and makes our lives easier. Moving content to a third-party vendor removes data one step, cuts-off that direct access and is detrimental to our own workflow.

_How do Developers keep their workflow and enable Editors to edit content?_
Forestry solves this issue simply by adding a UI layer on top of your data files that shows editors only what they need without having to be afraid of breaking anything and provides them with a WYSIWYG (visual) editor, toolbar and Media library to make changes to their content the way they are used to. All while leaving your code base completely untouched and the way you've planned it out.

{{% tip %}}
Other structured data formats such as JSON, YAML or TOML can also be edited via Forestry. 
{{% /tip %}}

By adding a layer on top of your existing code base, Forestry allows developers to stick to their favorite tools and workflow. We don’t believe content management systems (CMS) should dictate your workflow. Forestry simply ensures your non-tech team can make changes to your Gatsby site’s content without a developer’s help.

\[Forestry Screenshot\]

Button → Try Gatsby with Forestry

## Forestry’s Content Management

### Git-Priority

Git has proven to be the most popular tool for developers to store their code today and we believe your code, content and data is yours and should be stored with access to modern technologies in. Hence, Forestry takes a Git-backed approach to content management pushing all changes back to your Git repository and pulling updated code directly into the content manager as it is updated. This way your Gatsby site is always in-sync, you can take advantage of all the tools in the Git environment and editors can edit and preview the latest version of the site.

\[Screenshot of Editor Change and Markdown diff\]

\[Cheering / raised hand emojis for Git providers \]

### Easy integration

Forestry directly connects to your Git repository to manage your content files. All you need to get started with Forestry is to import the repository that contains your Gatsby site and point Forestry to directories that hold content which you want to access.

If you want users to be able to create brand new content you can create content models that we call Front Matter Templates. These come with an abundance of different fields from simple text fields and color pickers to the ability of creating modular layouts with [Blocks](https://forestry.io/docs/settings/fields/blocks/).

{{% tip %}}
Check out a guide on how to get started with Forestry and Gatsby or simply import the starter above to begin exploring.
{{% /tip %}}

\[Sidebar Screenshot\]

### **Code Cleanliness**

There’s no need for lengthy authorization setups, plugins or deep integrations into your codebase. Forestry’s entire site configuration lives in a well-contained .forestry directory and will not pollute your codebase. Having all settings inside the .forestry directory gives you the flexibility of configuring Front Matter Templates with the Forestry UI or directly in the code editor.

Lastly, Forestry does not lock you into its system and the costs of transitioning an existing system are minimal. If you decide to switch the content manager, simply remove your site from Forestry and delete the .forestry folder in your repository. No unpleasant surprises of finding Forestry snippets in your code.

\[.forestry settings are separate from rest of the code base\]

### **Out-of-the-Box Previews**

Content creators need an immediate feedback loop to create great content. Seeing what the text or copy looks like _before_ it is published is a crucial step to successful content editing. While setting up a preview with other systems can be cumbersome, Forestry has integrated previews and ships them out-of-the-box, all you need to do is to declare the command that should be run for your Gatsby site.

### **Updates and Deployments in the Cloud**

Forestry lives in the cloud and is accessible everywhere. No need to start-up your computer or pull the repository to deploy an update to your Gatsby site. This can be handled easily from your mobile phone or any other computer. Simply login and hit save, Forestry uses your [Build Commands](http://Build Commands) to deploy the compiled site to a variety of possible [Hosts](http://Hosts).

This Gatsby tutorial shows you [step-by-step](http://Link to Gatsby Docs) on how to set up a Gatsby site with Forestry.