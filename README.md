# Upsilon &upsih;
A proprietary chat server, &copy; 2017 LuzFaltex


## Purpose
Upsilon (formerly FloofChat) is a proprietary, closed source chat server. It built in Visual Studio and is designed to be run from a web server using IIS or Apache.

## Features
This is (or will be when completed) a fully-fledged chat server with the following:

1. Advanced Admin Control Panel
2. Advanced permissioning system
   - Optional tie-ins with Microsoft Active Directory to handle group membership and logins
3. Base design built in [Kube](https://imperavi.com/kube/)
4. [Redactor](https://imperavi.com/redactor/) WYSIWYG editor for chat
5. BBCode and Markdown support for chat formatting, static page creation, and more

## How to Contribute
If you would like to make a suggestion, feature request, or report a bug, please create an issue with details about your idea or how to replicate the bug, respectively. Discussion of particular ideas should happen in the [Discord server](https://discord.gg/PGCpM4q) or in the suggestion comments.

### Recommended suggestion format:
Set the title to a concise yet accurate description of the idea.
```
Name:
Controller name: [ Admin | User | Char | House | Room | Home ]
Page name: (if applicable)
Description:
```
### How to choose a Controller (and when to make a new one):
Controllers are separated zones in the web page and show up after the `/`. For example:

`https://www.example.com/Admin/Page`

Controllers can be renamed in the ACP, but suggestions should refer to the default controller names. This process is called Controller Aliasing. 

It should be noted that the Home controller does not show up in the path. The path is rewritten to exclude it.
```diff
- https://www.examle.com/Home/About
+ https://www.example.com/About
```

If you would like to optionally see the Home controller, add a suggestion.

Controller | Description
---------- | ------------
Admin | Anything related to the Admin Control Panel. 
User | Anything related to User Control Panel.
Char | Anything related to Character Pages
House | Anything related to House information pages, permissions, rooms, moderation, etc.
Room | Anything related to temporary rooms.
Home | Chat-based options such as @mentions, text formatting, static pages (home, privacy policy...), etc.


### To-do list
See [projects](https://github.com/LuzFaltex/Upsilon/projects)

