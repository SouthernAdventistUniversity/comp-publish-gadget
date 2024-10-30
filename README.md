# comp-publish-gadget

Modern Campus sidebar gadget to publish all pages dependent on a specific component.
## Details
A single HTML file that is embeded in the MC Sidebar via an iframe. Modeled after Modern Campus' [Custom Gadgets](https://support.moderncampus.com/cms/technical-reference/custom-gadgets.html) setup.
Uses jQuery, MC's [gadgetlib.js](https://github.com/moderncampus/cms-examples/tree/main/gadgetlib.js) and [Basic Styles](https://a.cms.omniupdate.com/11/style.css).

Displays the progress and classifies attempts as successful or failed. Allows for a custom publish version message that is prepended with `[Script] Dependency Publish: ${comp}`


## Usage
- Cloned to and served on Devinci at: `/_resources-prod/gadgets/comp-publish/` 
- Linked to the CMS in the [MC Gadget Settings](https://a.cms.omniupdate.com/11/#oucampus/southern/www/setup/gadgets)
