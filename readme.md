[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/drHIM5fX)
# a00-setup

This is an optional assignment and is worth 0 points. You will not be asked to write any code to complete this assignment, because it is intended only to verify that your development environment is properly set up. If you encounter configuration problems completing this assignment on your computer, please consider attending office hours to get them resolved before the first programming assignment is released.

By successfully completing a00-setup, you will:
1. Verify you can download assignment starter code from GitHub
2. Verify IntelliJ is properly set up to automatically format code according to the Google Java Style Guide
3. Verify you have permission to commit and push your coding changes to GitHub
4. Verify you know how to submit your work to Gradescope

> If you encounter problems with the autoformatter or the assignment submission process while working on this assignment, please visit office hours to get them resolved. This assignment is intended to identify configuration issues early, before the "real" assignments start

## Introduction

Successful completion of a COMP 301 programming assignment requires the following four independent tools to work together correctly:
1. IntelliJ
2. The Google Java Format Plugin
3. Git/GitHub
4. Gradescope

The goal of a00-setup is to make sure these four components are set up and ready to go on your computer before working on a "real" programming assignment. a00-setup is split into two parts: (1) configuring the IntelliJ autoformatter, and (2) submitting an assignment.


## Configuring the IntelliJ autoformatter

In COMP 301, all submitted code is expected to conform to [the Google Java Style Guide](https://google.github.io/styleguide/javaguide.html). Every time you submit an assignment throughout the semester, your code will be analyzed automatically by the autograder. Any style mistakes will be identified and will incur a penalty in your assignment grade.

The easiest way to avoid the penalty is to configure IntelliJ's autoformatter to automatically adjust your code so that it conforms to the Google Java Style Guide. Google has released an IntelliJ plugin which configures IntelliJ's autoformatter for you.

Your first task is to install and enable the plugin, called [the Google Java Format plugin](https://plugins.jetbrains.com/plugin/8527-google-java-format), on your computer. [This guide explains how to install plugins](https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_repo) using the IntelliJ plugin marketplace. When searching the marketplace for the plugin, type the words "google java format" as your search query, and the first result will be the one you want.

### Enabling the plugin on a per-project basis
On some computers, the Google Java Format Plugin is disabled by default for new projects. If you ever notice that the autoformatter isn't working for a particular assignment (even though the plugin is installed correctly in IntelliJ), try the following steps to make sure it is enabled for your project:
1. Open the IDE settings by clicking `CTRL + ALT + S` (Windows) or `⌘ ,` (MacOS)
2. In the left menu, look for "google-java-format Settings"
3. Check the box labeled "Enable google-java-format"


## Submitting your assignment

Now that the Google Java Format Plugin is installed and enabled on your computer, the remainder of this assignment tests that you can commit and push code to GitHub and submit it to Gradescope for autograding. You will use this process for every programming assignment throughout the semester.

To complete a00-setup, you need to clone the starter code, autoformat a provided file, commit and push your changes to GitHub, and submit your "work" to Gradescope. A [walkthrough video is available](https://youtu.be/KQ2v47r44NY) which illustrates the assignment submission process.

1. **Accept the assignment:** If you haven't already, navigate to the "Assignments" page in Sakai and click the "a00-starter" link at the bottom of the page to accept the a00-setup assignment.
2. **Copy the repo URL:** Clicking the link will produce a GitHub repository URL. Copy this URL to your clipboard.
3. **Clone the repo in IntelliJ:** Open IntelliJ and [create a new project from version control](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#clone-repo). Follow the onscreen instructions, pasting the repo URL in the input labeled "URL." Once complete, the assignment starter code will be downloaded to your computer and will be visible in IntelliJ. _Note: See the video walkthrough for instructions if you see an authentication error while cloning the project_
4. **Locate the file to be autoformatted:** In the project tree located in the left sidebar, navigate to the file `a00-setup -> src -> main -> java -> com.comp301.a00setup -> CFG.java -> CFG`.
5. **Autoformat code:** Once you have opened `CFG.java` in IntelliJ, simply press `CTRL + ALT + SHIFT + L` (Windows) or `⌥ ⇧ ⌘ L` (MacOS) to automatically reformat your code ([see this page](https://www.jetbrains.com/help/idea/reformat-and-rearrange-code.html) for more detailed instructions). The code in the active window should automatically be adjusted so that it conforms to the Google Java Style Guide.
6. **Commit and push your changes to GitHub:** [See this page](https://www.jetbrains.com/help/idea/commit-and-push-changes.html) for instructions.
7. Log in to [Gradescope](https://www.gradescope.com/) from a browser and submit your work to the autograder (see video walkthrough for instructions)
8. When the autograder finishes, verify there were no style guide formatting errors in your submission.