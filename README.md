# Simple-Browser-extension
This projects demonstrates how to build a simple browser extension for firefox or chrome browsers


--manifest file
A manifest file is a must have file in any browser extension. This file contains basic data about our extension like name, version, and so on.

Now inside the manifest.json file copy the following snippet:

```
{
  "manifest_version":2,
  "version":"1.0",
  "name":"<your_preferred_name",
}
```

--How to load the extension file
For Firefox users, follow these steps:

In the address bar, search for this:

```
about:debugging#/runtime/this-firefox
```

You will see an option to Load Temporary Add-on. Click on that option and choose the manifest.json file from the directory.

-- For chrome
In the address bar search for this:

```
chrome://extensions.
```
* Enable Developer Mode and switch into it.
* Click the Load unpacked button and select the extension directory.