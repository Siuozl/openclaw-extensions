# GreenBrew
## What is GreenBrew?
It's a powerful extension that can be added using a single prompt. It is extremely easy to use, as long as you have OpenClaw installed and have a way of communicating to it.
## Installation
Copy and paste the following prompt into your OpenClaw bot.
```
Read the file at this link: https://siuozl.github.io/openclaw-extensions/extensions/greenbrew.octweak and apply what is said in the file.
```
Easy, quick, that's all. It should either start a tutorial or say it has applied it, depending on the model you're using.

**POSSIBLE ERROR**
If it answers with "Extension Incompatible: Only supports OpenClaw" it either means that your agent is not OpenClaw-based, or that it *thinks* it isn't.

## How to use GreenBrew
**COMMANDS:**
greenbrew / gbrew / gb
**SUBCOMMANDS OF GREENBREW:**
new - Creates a new project in the directory you've chosen. It will ask you for a project name and description, then let it brew!
edit <project-name> - Edit a previous project.
del / delete <project-name> - Delete a previous project.
model / version - Displays the GreenBrew Version and the model your agent is running on.
list - Lists your current projects.
dir / cd - Set the default directory where GreenBrew projects should go.

**DISCORD ONLY SUBCOMMANDS:**
*Can only be used if your agent is in a discord chat with you (set up a discord application for it, it's very easy.)*
sim / simulate - Tries its best to simulate the project you made, whether it's in HTML, PYTHON or anything else. It will allow you to interact with it. This only works in Discord because it uses Markdown, which is a Discord exclusive feature; most other chatting apps do NOT support markdown.