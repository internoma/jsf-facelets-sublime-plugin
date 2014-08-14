JSF & Facelets - Sublime Plugin
==================

A sublime plugin complete with JSF & Facelets snippets



## What's included - contents
- [Installation](#installation)
- [Snippets](#snippets)
- [License](#license)


### Installation

There are 3 methods for installing this plugin.

1. Search for "JSF & Facelets Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/internoma/jsf-facelets-sublime-plugin.git

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

### SNIPPETS

    <c: />
        jsf-if: <c:if />
        jsf-set: <c:set />

    <h: />
        jsf-panelgroup: <h:panelGroup />
        jsf-outputlink: <h:outputLink />
        jsf-outputtext: <h:outputText />

    <ui: />
        jsf-fragment: <ui:fragment /> 
        jsf-param: <ui:param />
        jsf-repeat: <ui:repeat />

    <fn: />
        jsf:upper: #{fn:toUpperCase([variable]/'texto')}
        jsf:lower: #{fn:toLowerCase([variable]/'texto')}


| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| this help                      | jsf-help                       |
|------------------------------- | :-----------------------------:|
| <c:if />                       | jsf-if                         |
| <c:set />                      | jsf-set                        |


### License

JSF & Facelets Snippets - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
