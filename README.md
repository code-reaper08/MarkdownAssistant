# MarkdownAssistant
![version](https://img.shields.io/badge/version-1.0.0-yellow "initial release")

## Description:

+ MarkdownAssistant is a simple and powerful snippet provider,which provides handy snippets for easy creation of Markdown (.md) files.

+ With MarkdownAssistant ,editing .md files is easy and fast.

---
## Installation:
### Package Control ![recommended](https://img.shields.io/badge/method-recommended-blue "Use this")

The easiest way to install the MarkdownAssistant is by using [Package Control](https://packagecontrol.io/). Installing it [is documented here](https://packagecontrol.io/installation).


- Open Package Control (or hit Ctrl+Shift+P or Cmd+Shift+P)
- Type _install_ and hit enter
- Type MarkdownAssistant and hit enter again

---

## Downloading the Archive

>Use this method if you don’t have Package Control or Git

- Open [https://github.com/code-reaper08/MarkdownAssistant](https://github.com/code-reaper08/MarkdownAssistant) in your browser
- On the right hand side there is a _Download ZIP_ button – click it
- Go to _Preferences_ and _Browse packages…_ which opens the Packages directory
- Extract the archive inside the Packages directory

To find out where the Packages directory is, you can go to _Preferences_ and _Browse packages…_. This will open the directory in your file explorer.

## Functions:

| Trigger word      |  function           |
| ------------- |:-------------:|
| mdh1      | Creates a heading 1 |
| mdh2      | Creates a heading 2 |
| mdh3      | Creates a heading 3 |
| mdh4      | Creates a heading 4 |
| mdh5      | Creates a heading 5 |
| mdh6      | Creates a heading 6 |
| mdb      | Creates a bold text|
| mdit     | Creates a italics text|
| mdstrike      | Creates a strikethrough text|
| mdbq      | Creates a blockquote text|
| mdcs      | Creates a single line code|
| mdcb      | Creates a code block|
| mdimg     | Creates a image with hover text|
| mdlnkt      | Creates a link with title|
| mdmailto      | Creates a mailto link for easy mailing |
| mdol      | Creates an ordered list|
| mdul      | Creates an unordered list|
| mdt12      | Creates a 1X2 table|
| mdt13      | Creates a 1X3 table|
| mdt21      | Creates a 2X1 table|
| mdt22      | Creates a 2X2 table|
| mdt23      | Creates a 2X3 table|
| mdt31      | Creates a 3X1 table|
| mdt32      | Creates a 3X2 table|
| mdt33      | Creates a 3X3 table|
| mdcic      | Creates a checklist item(checked)|
| mdciu      | Creates a checklist item(Unchecked)|
| mdhl     | Creates a Horizontal line seperator|
| mdmention      | Creates an mention|

## Important ![important](https://img.shields.io/badge/-Important-red "read this")

MarkdownAssistant needs some settings changes to assist you flawlessly.
kindly go through the steps and set your user settings accordingly.

+ Go to `preferences -> settings`
+ In `Preferences.sublime-settings(User)` add these lines,

    ~~~ "auto_complete": true,
	"auto_complete_commit_on_tab": true,
	"auto_complete_selector": "source,text",
	"auto_complete_with_fields": true,
+ Save it and Restart SublimeText.

---

## License:
![License](https://img.shields.io/badge/License%20-MIT-brightgreen "MIT License")


Copyright 2021 Vishwa.R

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
