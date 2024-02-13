# JetBrains (IntelliJ) Quick Start Guide + Tips and tricks
<sup><sup>By Bas Calders v0.3.2

---

## Table of Contents

[TOC]

## Prerequisites
###### Disclaimer
<sup>Before we begin, let's get some things straight. This guide is intended to provide helpful tips and tricks for using JetBrains Products, IntelliJ in particular, a popular integrated development environment. The information presented in this guide is based on our own experience and research, and is provided for educational and informational purposes only. It is not to be distributed or sold for any form of payment, and should only be applied within a scholarly context. The information provided in this guide is mostly transferable to other JetBrains products, allowing users to apply the tips and techniques to a wide range of similar software.

<sup>While we strive to ensure the accuracy of the information presented in this guide, we make no guarantees or warranties regarding its completeness, reliability, or suitability for any particular purpose. Readers are encouraged to conduct their own research and due diligence, and to use the information presented in this guide at their own risk. Any mistakes found and/or suggested updates (e.g.: outdated links) or issues can always be sent to the [author](mailto:bas.calders@gmail.com) or any person of the [Ingenium UA Praesidium](https://www.ingeniumua.be).

<sup>Please note that this guide may contain copyrighted material, including screenshots, code snippets, and other intellectual property belonging to JetBrains, the creators of IntelliJ. We believe that our use of such material in this guide constitutes fair use under U.S. copyright law, as we are using it for the purpose of commentary, criticism, and education. However, if you believe that your rights have been infringed upon, please contact us and we will take appropriate action.

<sup>In short, while we believe that the information presented in this guide will be helpful to readers, we make no guarantees or warranties, and readers should use their own judgment when applying these tips and tricks in their own work.

### Version
Before proceeding with the tips and tricks in this guide, please note that at the point of writing this, the newest version of IntelliJ is `2023.3`, using the new and improved UI to ensure the maximum longevity of this guide. Additionally, this guide is tailored to users running IntelliJ on a Windows 11 machine. Please note that some tips and techniques may not be applicable to earlier versions of IntelliJ or different operating systems. In most cases MacOS users will be able to replace most usages of <kbd>CTRL</kbd> &harr; <kbd>⌘</kbd> and <kbd>Alt</kbd> &harr; <kbd>⌥</kbd>

## Cheat Sheet
Using a cheat sheet for shortcuts can greatly enhance your productivity and efficiency when using the software. With so many different features and functionalities available, it can be difficult to remember all of the keyboard shortcuts and menu options that are available to you. By using a cheat sheet, you can easily access a comprehensive list of shortcuts and other important information that you need to know, saving you time and effort in the long run.

Furthermore, a cheat sheet can help you become more proficient in using the software and can serve as a valuable reference tool as you continue to work with IntelliJ. By having a printed cheat sheet in front of you, you can quickly find the shortcuts and features you need to use, without having to navigate through menus or search for the information online.

A physical copy of a cheat sheet can be a valuable resource for learning and utilizing keyboard shortcuts in IntelliJ. Unlike a digital copy, a physical cheat sheet allows you to mark it up with notes and annotations, highlight frequently used shortcuts, and create mnemonic devices to help you remember the information more easily. So, printing is highly recommended

A plugin that can help you learn and integrate keyboard shortcuts into your workflow is the [`Key Promoter X`](https://plugins.jetbrains.com/plugin/9792-key-promoter-x) plugin. This plugin is designed to help you improve your productivity by reminding you every time you perform an action that could be done more efficiently using a shortcut. The plugin keeps track of your actions and prompts you with a notification every time an action has a corresponding keyboard shortcut available. This serves as a gentle reminder to use shortcuts and helps you to learn them more quickly by providing immediate feedback. With the help of this plugin, you can gradually integrate keyboard shortcuts into your workflow, leading to faster and more efficient use of IntelliJ.

### Sheets
**_//TODO: update links to work_**
<details>
<summary>Windows/Linux</summary>
<img src="cheatsheets/IntelliJIDEA_ReferenceCard_Windows-Linux.png"/>
Click [here](cheatsheets/IntelliJIDEA_ReferenceCard_Windows-Linux.pdf) to download PDF
</details>
<details>
<summary>MacOS</summary>
<img src="cheatsheets/IntelliJIDEA_ReferenceCard_MacOS.png"/>
Click [here](./cheatsheets/IntelliJIDEA_ReferenceCard_MacOS.pdf) to download PDF
</details>


## Navigation and Shortcuts

### Recommended shortcut changes: 
When pressing <kbd>CTRL</kbd>+<kbd>Y</kbd> for the first time, You will be prompted with the option to choose between `Redo` and `Delete Line`. I Recommend choosing the option you are most accustomed to in other programs: `Redo`. To fill this void in functionality we van bind `Delete line` to <kbd>Alt</kbd>+<kbd>Backspace</kbd>. This wil prompt the replacement of `Undo`. But this is no problem since this is also served by <kbd>Ctrl</kbd>+<kbd>z</kbd>.

The Keymap can be edited by pressing the <kbd>⛭</kbd>, then <kbd>Keymap...</kbd>, then <kbd>Configure Keymap...</kbd>

Another good change to make is to bind `Run`, `Build` and `Debug` to dedicated buttons. Macro or unused keys work the best for this, but if needed `AutoHotKey` can also help you with this.

## Customization 
- add build button to bar
- add vcs buttons to bar
- make project tree be "un-docked"

## Advanced Features 

## Integration and Interoperability
- use global settings

## Efficiency and Time-Saving
- plugins like key promoter
- some more ShortCuts

## Best practices and workflows

## Plugins - a List 
Welcome to the chapter on our top recommended plugins for enhancing productivity and introducing quality-of-life improvements in your development environment. As a developer, you understand the importance of having a well-configured workspace that enables you to write clean, efficient, and maintainable code. With countless plugins available, it can be challenging to identify the ones that truly make a difference. In this chapter, we have handpicked a selection of plugins that will not only boost your productivity but also provide those little quality-of-life changes that make coding more enjoyable and less error-prone.

- Key Promoter X
    >The Key Promoter X helps you to learn essential shortcuts while you are working. When you use the mouse on a button inside the IDE, the Key Promoter X shows you the keyboard shortcut that you should have used instead. This provides an easy way to learn how to replace tedious mouse work with keyboard keys and helps to transition to a faster, mouse free development. The Key Promoter X tool window shows you a hit-list of the mouse actions you use the most and directly provides you with the shortcut you can use instead. For buttons that don't have a shortcut, the Key Promoter X prompts you with the possibility to directly create one.

    https://plugins.jetbrains.com/plugin/9792-key-promoter-x
- Github Copilot
    >GitHub Copilot is an AI-driven code completion tool created through a partnership between GitHub and OpenAI. The IntelliJ plugin version of GitHub Copilot aims to support software developers by providing context-aware code snippets and function suggestions while they write code. This advanced tool is built on a deep learning model that has been trained on an extensive range of public code repositories, enabling it to generate pertinent code suggestions across multiple programming languages and frameworks.
    The GitHub Copilot plugin for IntelliJ enhances the coding experience by offering real-time recommendations, which can significantly improve productivity, decrease development time, and assist developers in writing higher-quality code. Although the AI-generated suggestions can be highly valuable, it's important to note that they may not always be perfect or adhere to best practices, so developers should review and adjust the suggestions as needed.

    https://plugins.jetbrains.com/plugin/17718-github-copilot
- Rainbow Brackets
    >Rainbow Brackets is a plugin for JetBrains IDEs, including IntelliJ IDEA, that enhances code readability by color-coding matching brackets, parentheses, and braces in your source code. This visual differentiation allows developers to quickly identify the structure and nesting levels of their code, making it easier to navigate and understand complex code blocks.
    By assigning unique colors to corresponding pairs of brackets, parentheses, or braces, Rainbow Brackets helps reduce the likelihood of syntax errors due to mismatched or missing delimiters. This simple yet effective plugin contributes to a more efficient and enjoyable coding experience, particularly when working with deeply nested code structures.

    https://plugins.jetbrains.com/plugin/10080-rainbow-brackets
- Productivity Bundle 
    >The JetBrains Marketplace Productivity Bundle offers a selection of carefully chosen plugins that aim to boost user experience and productivity within JetBrains IDEs, such as IntelliJ IDEA. By streamlining workflows and optimizing common tasks, the bundle enables developers to concentrate on coding while enjoying improved efficiency. The included tools promote the use of keyboard shortcuts, enhance code navigation, and provide advanced code generation and refactoring capabilities. Additionally, the bundle comes with valuable integrations, such as GitHub Copilot, which offers AI-powered code completion. Overall, the Productivity Bundle significantly enhances the development process within JetBrains IDEs by providing a comprehensive suite of tools to make coding faster, more efficient, and enjoyable.

    https://plugins.jetbrains.com/bundles/4-productivity-bundle
- codeGlance
