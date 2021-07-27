# MDINA - THE SILENT CITY WITH A STORY TO TELL

‘Mdina – The Silent City with a Story to Tell’ is a site that hopes to introduce people to some of the historically significant locations found around Mdina, Malta.  The site will be targeted towards history enthusiasts and travellers looking for more information about the various locations found in Mdina.  

![Website Banner](assets/images/readme-images/hero-image-with-title-mobile.jpg)

## FEATURES

### Existing Features

* Navigation Bar
    - Fixed at the top of the screen.
    - As site is a single page site, this will allow users to navigate between sections without having to return to the top of the page.

SCREENSHOT

* Title Hero Image
    - Includes a full-screen photograph with a text overlay to allow the user to see what this site contains. 
    - The image was chosen as it is representative of Mdina’s history and present.
    - The text does not obscure the key details of the picture.

SCREENSHOT

* History Section
    - Site’s only text-heavy section containing a brief history of the city as a whole.  As site is focussed towards history enthusiasts and travellers, having accurate historical content first establishes credibility. 
    - Contains two images for decorative purposes.

SCREENSHOT – history-section-desktop.jpg / history-section-mobile.jpg

* Notable Buildings Section
    - Contains eight images of different buildings around Mdina.  Each image serves as a link to the building’s dedicated Wikipedia page (which opens in a new window).  Using the building’s image allows users to quickly access the building’s information when they are physically present in Mdina – thus using it as a reference.
    - In the desktop view, a transition effect will be visible.  When the user hovers over an image, the image will turn grey and the building name will appear.
    - In the mobile view, there is no hover effect, each building name will be present on the image.

* How to Find Us Section
    - Does not contain information on how to find Mdina, but does contain links to a tourist information site on how to get there by bus, bu car and on foot.
     - As the site is primarily designed with a focus on history, it was decided that this information should be simple with few details.
    - There are three sections each with a button to an external page which opens in a new tab.

SCREENSHOT – how-to-find-us-section-desktop.jpg / how-to-find-us-section-mobile.jpg

* Contact Section
    - Contains a form and a video about Mdina.  
    - This section allows users to get in touch if they have any questions about Mdina or the content displayed on the page.
    - This feature is currently inactive (see below)
     - The video is present to give users an alternative view of Mdina which can be watched while filling in the form on the desktop version.  For mobile devices, the video is below the form.

SCREENSHOT – contact-us-section-desktop.jpg / contact-us-section-mobile-1.jpg / contact-us-section-mobile-2.jpg


![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome dougiemath,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. The last update to this file was: **July 2, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
