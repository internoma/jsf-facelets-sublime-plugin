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

    <helpers />
        jsf: #{value}
    
    <c: />

        jsf-if: <c:if />
        jsf-set: <c:set />

    <h: /> http://www.jsftoolbox.com/documentation/help/12-TagReference/html/index.jsf

        jsf-body: <h:body />
        jsf-button: <h:button />
        jsf-column: <h:column />
        jsf-commandbutton: <h:commandButton />
        jsf-commandlink: <h:commandLink />
        jsf-datatable: <h:dataTable />
        jsf-form: <h:form />
        jsf-graphicimage: <h:graphicImage />
        jsf-head: <h:head />
        jsf-inputhidden: <h:inputHidden />
        jsf-inputsecret: <h:inputSecret />
        jsf-inputtext: <h:inputText />
        jsf-inputtextarea: <h:inputTextarea />
        jsf-link: <h:link />
        jsf-panelgroup: <h:panelGroup />
        jsf-panelgrid: <h:panelGrid />
        jsf-outputlink: <h:outputLink />
        jsf-outputtext: <h:outputText />
        jsf-outputscript: <h:outputScript />
        jsf-outputstylesheet: <h:outputStylesheet />
        jsf-selectbooleancheckbox: <h:selectBooleanCheckbox />
        jsf-selectmanycheckbox: <h:selectManyCheckbox />

    <ui: /> http://www.jsftoolbox.com/documentation/facelets/10-TagReference/ui.jsf

        jsf-component: <ui:component /> The UI Component tag inserts a new UIComponent instance into the JSF component tree.
        jsf-composition: <ui:composition /> The UI Composition tag is a templating tag that wraps content to be included in another Facelet.
        jsf-debug: <ui:debug /> The UI Debug tag allows you to display helpful information about the JSF component tree and scoped variables in your browser when you test your JSF pages.
        jsf-decorate: <ui:decorate /> The UI Decorate tag is a templating tag that decorates content included from another Facelet.
        jsf-define: <ui:define /> The Define tag is a templating tag that defines named content to be inserted into a template.
        jsf-fragment: <ui:fragment /> The UI Fragment tag inserts a new UIComponent instance into the JSF component tree.
        jsf-include: <ui:include /> The UI Include tag is a server-side include tag for Facelets.
        jsf-insert: <ui:insert /> The UI Insert tag is a templating tag that declares a named content element to be defined by another Facelet.
        jsf-param: <ui:param /> The UI Param tag is used to pass objects as named variables between Facelets. 
        jsf-remove: <ui:remove /> The UI Remove tag is used to specify tags or blocks of content that should be removed from your page by the Facelets view handler at compile time.
        jsf-repeat: <ui:repeat /> The UI Repeat tag is used to iterate over a collection of objects exposed to the JSF page as a value-binding EL expression.

    <fn: />

        jsf:upper: #{fn:toUpperCase([variable]/'texto')}
        jsf:lower: #{fn:toLowerCase([variable]/'texto')}
        



###Following is the list of JSTL Functions:

        Function                Description
        ========                ===========
        fn:contains()           Tests if an input string contains the specified substring.
        fn:containsIgnoreCase() Tests if an input string contains the specified substring in a case insensitive way.
        fn:endsWith()           Tests if an input string ends with the specified suffix.
        fn:escapeXml()          Escapes characters that could be interpreted as XML markup.
        fn:indexOf()            Returns the index withing a string of the first occurrence of a specified substring.
        fn:join()               Joins all elements of an array into a string.
        fn:length()             Returns the number of items in a collection, or the number of characters in a string.
        fn:replace()            Returns a string resulting from replacing in an input string all occurrences with a given string.
        fn:split()              Splits a string into an array of substrings.
        fn:startsWith()         Tests if an input string starts with the specified prefix.
        fn:substring()          Returns a subset of a string.
        fn:substringAfter()     Returns a subset of a string following a specific substring.
        fn:substringBefore()    Returns a subset of a string before a specific substring.
        fn:toLowerCase()        Converts all of the characters of a string to lower case.
        fn:toUpperCase()        Converts all of the characters of a string to upper case.
        fn:trim()               Removes white spaces from both ends of a string.



| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| this help                      | jsf-help                       |
| '<c:if />'                     | jsf-if                         |
| '<c:set />'                    | jsf-set                        |


### License

JSF & Facelets Snippets - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
