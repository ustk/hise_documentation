---
keywords: Contribute to the HISE Docs
summary:  How to contribute to this documentation.
icon:     /images/icon_markdownpanel
index:    02
---

This documentation is based on the `hise_documentation` repository on [GitHub](http://github.com/christophhart/hise_documentation/). 
It uses the Markdown files from there and merges it with autogenerated API references in order to keep the amount of boilerplate documentation as low as possible.

If you would like to contibute to this documentation, the best way is to pull the repository, make edits and then submit a pull request.

## Setup

For the normal user, the documentation will be created from two binary files, `Content.dat` and `Images.dat`, which will be 
periodically updated and fetched from the server on HISE startup.

If you want to edit the documentation, you will have to bypass this and use the markdown files directly. In order to do so, you must:

1. Clone this repository `http://github.com/christophhart/hise_documentation.git`
3. Point the markdown editor to the folder (**Settings -> Doc Settings -> Doc Repository**), then restart HISE.

> The editor will autogenerate certain elements like the scripting API and the HISE module reference. Make sure that you have compiled the latest version from the repository when you edit something in there.

Alternatively, you can just edit the files directly on github and make pull requests there, but then you miss out all the nice features of the editor.

