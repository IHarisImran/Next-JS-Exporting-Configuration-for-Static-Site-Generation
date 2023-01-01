## Note
This exporting configuration only works with Next.JS 12 and below. This setting is absolute for you if you are using Next.JS 13 or above.

# Next-JS-Exporting-Configuration-for-Static-Site-Generation
This code will help you to fix **URL routing problems** that occur when changing the URL after the website has been generated statically using **Static File Generating** rendering method. If you are getting a 404 page when changing the URL with the SSG rendering method, add the following code to your **next.config.js** file.

* *module.exports = { trailingSlash: true, }*

Full code in next.config.js file
