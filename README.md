# alfred cowsay workflow
This is an Alfred workflow. It integrates cowsay ASCII image generator command with [alfred productivity tool](https://www.alfredapp.com/) for Mac OS X.

This workflow triggers the cowsay command with user provided message and displays the output as a large banner which covers the entire screen. Additionally the cowsay output gets copied to clipboard. 

**Prerequisite:**

This workflow assumes that **cowsay** is already installed and available at **/usr/local/bin/cowsay**. If its not already installed, please [install it using brew](http://macappstore.org/cowsay/ "install cowsay in Mac") and then import this workflow.

**Installation Instruction**

Just download **cowsay.alfredworkflow** from this repository and click on it. Assuming alfred is already installed, it will prompt you to  install this workflow. Follow the instructions and this should get installed without any issues.

**See it in action:**

[![alfred cowsay workflow in action](https://img.youtube.com/vi/B4kz8WVHQWU/0.jpg)](https://www.youtube.com/watch?v=B4kz8WVHQWU)



**Troubleshooting**

If it does not display the cowsay output, it means the workflow did not find cowsay executable at **/usr/local/bin/cowsay**. In that case, you have two options:
1. Make sure to install cowsay at **/usr/local/bin/cowsay**
2. If you are comfortable editing alfred workflow, then edit the workflow and goto `\bin\bash` step and edit the script to point to the installation location of cowsay executable as depicted in following two screenshots.
    - STEP 1 - choose the `/bin/bash` step
     ![choose the step](https://github.com/rajasenapati/alfred_cowsay_workflow/blob/media/workflow_screen.png?raw=true)
    - STEP 2 - edit the script to point to cowsay executable location and save the workflow
     ![edit the screipt to point to cpwsay location and save](https://github.com/rajasenapati/alfred_cowsay_workflow/blob/media/script_screen.png?raw=true)  
