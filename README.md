# ALCOM Template NDMF Starter

## How to use

1) Install ALCOM
You can find the installation procedure on the official website <https://vrc-get.anatawa12.com/alcom>.

2) Ensure that you have all the required repositories
You can go to the "Resources/Repositories" tab of ALCOM, use the *top right* button to "Import a list of repositories", then select the [alcom/required-repositories.txt](./alcom/required-repositories.txt) file.

3) Import the template
You can go to the "Resources/Templates" tab, use the *top right* button to "Import a template", then select the [alcom/NDMF-Starter.alcomtemplate](./alcom/NDMF-Starter.alcomtemplate) file.

4) You can now create new project with that template.

## What is inside this template

You can find various NDMF packages that will help you kickstart your project.
For now this template doesn't enforce any version, so the last version of each tool will be installed.

||||
|---|---|---|
| **Package Name**      | **Usage** | **Description** |
| NDMF              | Core | Used to plug all modules together |
| Modular Avatar    | Menu/Structure | Used to plug all modules together |
| Gesture Manager   | Tool | Test avatar within Unity |
| Anatawa12 Gist    | Tool | Maily for the "Actual Performance" window |
| Anatawa12 AAO     | Optimization | Run various optimizations for avatar performances |
| TexTransTool      | Optimization/Customization | Used to improve performance on textures |
| Avatar Menu Creater For MA | Menu | Advanced menu creation based on objects, blendshapes & materials |

### Beyond this template

You can take a look at the associated listing of interesting NDMF packages at <https://github.com/Spokeek/awesome-ndmf>
## Context

### What is ALCOM

ALCOM (ALCOM - Alternative Creator Companion) is a graphical reimplementation of the [Creator Companion (VCC)](https://vcc.docs.vrchat.com/) from VRChat.

This package manager is maintained by the community and available as an OpenSource application and can be obtained on @anatawa12's website <https://vrc-get.anatawa12.com/alcom>

### What is NDMF / Modular Avatar

NDMF and Modular Avatar are modular systems to improve avatar developement with non destructive workflows and first developped by @bdunderscore.

The underlaying system is NDMF that glues everything together. The main package Modular Avatar provides compontents to create vrchat menus, merge armatures and more.
