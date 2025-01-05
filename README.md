# Fandom Zine Website Template

Hi hey hellooo! Welcome to the product of my ADHD, spite against Carrd, and a LOT of mental illness. 🎉 WE ALL CHEERED HUZZAH!!

Anyways: this template's here to help you easily create a website for your zine! It's got pages for **Guidelines**, **Schedule**, **Mods**, and **Questions**, and I've done my best to make it easy to customize. You don't need to be an expert in coding or anything like that (but you'll definitely learn a thing or two by the end of this!)
This lil guide here is gonna walk you through everything you need to get your zine sit up and running. 

(Also, yes, I will be putting visuals in this lol dw.)

## Table of Contents
1. [Getting Started](#getting-started)
   - [Fork the Repo](#1-fork-the-repo)
2. [Customizing Time](#2-customizing-time)
   - [Uploading Your Images](#upload-your-images)
   - [Change the Background](#change-the-background)
   - [Editing Your Pages](#editing-your-pages)
3. [Deploy GitHub Pages](#3-deploy-github-pages)
4. [Important Note](#important-note)

---
## Getting Started

### 1. **Fork the Repo**  
First, click the **Fork** button at the top-right of this page. This will create your own version of the repository (AKA the code), where you can make changes without affecting this original copy.

![Fork Button](https://github.com/user-attachments/assets/2c298e1c-b1b0-4846-af54-f8cbeeaf25df)

Then, you'll be taken to a page asking you to confirm that you want to make a fork. Feel free to change the repository name to anything you'd like. 

![Fork Confirmation](https://github.com/user-attachments/assets/ea3024a1-6947-4458-9266-880efc115397)

Do note that the full page will read as ***YourGitHubUserName.github.io/RepositoryName***. You CAN rename the "zinewebsitetemplate" part if you can't think of anything right away, so no stress! I'd recommend something short and simple like "zinepage" though, but that's just me :P.
> **Important**: Do NOT change/click/mess with anything except the repository name. Otherwise, things can and will get messy.
Once you click confirm, congrats! You've got yourself a copy of code.  

---

### 2. **Customizing Time, Woop Woop!**

If you're totally inexperienced with GitHub, no worries! You can make all the lil customizations and edits via the website. If you happen to have more experience with GitHub/coding in general, feel free to locally download the forked repository/edit the code in a text editor. 

These instructions will be going more in detail for people who will be making edits and stuff via the GitHub website, but in general, it's all the same stuff.

First thing you need to do is click on the docs folder. You'll find yourself inside the code: 

![Coding Center](https://github.com/user-attachments/assets/ccf396e6-ac06-4c54-96c9-6c90c908d57d)

You'll be spending most of your time inside the `index.html` file. We have two things we need to do first, though:

- **Upload Your Images:**  
    Click on the `images` folder, then on `Add files`. 
![Image Adding](https://github.com/user-attachments/assets/f23f1f2f-2dd5-476e-8f1b-a7d331dd0831)
Select `Upload files`, and you'll be taken to the page below. Drag and drop/download all the image files you'll be using.

> NOTE: I highly recommend using one-word names for all your files, or at least names without spaces (e.g., BackgroundPhoto, Logo, etc.). This helps reduce complications with the code.

![Image Change Commit](https://github.com/user-attachments/assets/0763c1c8-6093-4c3d-ba4f-97ebe7a84888)

When you finished uploading all your photos, put any lil blurb in your commit title and press the button. Do NOT change anything else.

- **Change the Background:**  
    Click on the `assets` folder, then on `css` folder, and finally, click on `main.css` file.
  
![Background Guide ](https://github.com/user-attachments/assets/1d0735e9-265d-4c79-87e7-c2ed4cb94647)
![Locating the File](https://github.com/user-attachments/assets/819d847a-1f16-4efc-b278-e6c4243f52fc)

Once you get to the file, click on the lil pencil icon at the top right corner so you can edit the file.

![Pencil to Edit Code](https://github.com/user-attachments/assets/5c734cac-e95d-4cb8-9353-47315710e223)

Once you click it and the code loads, use **Ctrl+F** (or **Cmd+F** on Mac) and search for `Generic`. 

![Ctrl Plus F](https://github.com/user-attachments/assets/d925eba4-08b4-4b28-852c-bf5df0e629eb)

#### (To be specific, **look for the instance of it on line `1161`.**)

![Modify the Background](https://github.com/user-attachments/assets/7d62914c-9687-4d58-be28-172a11d6de47)

Change the `Generic\ Background.png` part of the code to the name of the file you uploaded in the `images` folder. When you're done, click the `Commit Changes` button.

![Commit Background Changes](https://github.com/user-attachments/assets/19fdc2e3-9946-4845-9453-2f7f4b7586f3)

Press the `Commit Changes` button again. Feel free to add a lil blurb in the commit message/description, but do NOT change anything else.

And now for the GOOD part:

- **Editing your Pages:**  
    Go back to the `docs` folder and click on `index.html`. All the code for all the pages is here. Click on the pencil in the top right to edit the code.
  
  ![Pencil for the Main Page](https://github.com/user-attachments/assets/3d7483b3-b010-49b2-834f-e69b7275f55a)
  
Use **Ctrl+F** (or **Cmd+F** on Mac) to search for sections you want to edit. Every section has these lil comments for you to use as guides with the **Ctrl+F** (or **Cmd+F** on Mac) to navigate more smoothly. 

![Page Navigation](https://github.com/user-attachments/assets/d953cd56-69d2-4655-b6d9-830a347c04f7)

For the hyperlinks (ex. in the mods page, or the "find us at our socials!" page), replace the highlighted portion with the link you'd like someone to end up at when they click on a specific button.

![Mod Social Media Links](https://github.com/user-attachments/assets/cf1b6b8d-144e-4983-82cd-746b97ef782c)

For example, here, you'd replace twitter.com with that mod's Twitter account link, so when someone clicks on the Twitter hyperlink, it will lead them to that mod's page.
  
In specific areas of the code, you might finds lines of code that look like they should be doing something, but aren't. If they're prefaced by `<!--`, then that's a comment. There are a handful of lines of code that are commented out throughout. If you would like to see what your template would look like WITH them, just delete the `<!--` portion at the start and the `-->` portion at the end.

![Comments](https://github.com/user-attachments/assets/9ddec3e4-4210-4797-aeb3-4118edc69d29)


I've lableled all the sections as clearly as possible, so you should have no trouble finding the part you need to update. I also added a bunch of documentation and comments to help you out with what to replace/modify. If you're ever still confused/would like help, feel free to reach out to me on Discord. My @ is **pleasejustcallemz.**
  
---
### 3. **Deploy GitHub Pages**

Now that you've basically become a programmer and experienced half a percent of the insanity I've dealt with for the past four years of my life (lolz) it is TIME TO DEPLOY!!

1. Click on the **Settings** page, then click on the **Pages** subcategory.
   ![To Deploy Your Page](https://github.com/user-attachments/assets/14f73d5c-2c80-4c44-b665-d463a56b5936)
3. You'll see a little something like this. Under the **Branch** subsection, click on the button that says `None`, and click on `main`.
    ![Click main](https://github.com/user-attachments/assets/5bfd3aa7-025d-4f26-a289-04dddca9e584)
4. Click on the button next to `main`, and click on `/docs`. **THIS IS VERY IMPORTANT!!** If you save with it set on `/roots`, the pages will not deploy.
   ![Click docs](https://github.com/user-attachments/assets/3b50bb1a-1f80-4713-8874-9835a34dd853)
5. Click **Save**.
    ![Save](https://github.com/user-attachments/assets/4ac2dfd5-1876-434d-8360-e45411bf9028)
6. Now, head back to the main page of your repo. You should see something like this:
    ![The Dot](https://github.com/user-attachments/assets/eb61e3db-3798-409e-871d-1c23328df4c3)
  This dot means that GitHub is compiling the pages and preparing to deploy them. If you click on the button, you might see something like this:
![Clicking on the Dot](https://github.com/user-attachments/assets/178efbd2-f134-46aa-9fee-0f3555a23dad)
  Don't worry if it seems to be taking a while--sometimes GitHub needs a second! If over 30-40 second pass without any sort of visible change, go ahead and refresh the page.
8. Eventually, you'll see something like this:
    ![The Check](https://github.com/user-attachments/assets/52e8af66-2035-4ce7-b8da-278a6fdc693c)
  This means that the compiling process was a success, and your page has been deployed! You'll also see this pop up:
    ![Deployment Success](https://github.com/user-attachments/assets/da6b634d-bf94-46c1-bf4a-82294e6e71c7)
9. If you click on that, you'll be taken to this page, which will show your most recent deployments. Click on the link.
    ![Most Recent Deployment](https://github.com/user-attachments/assets/d3ecfc06-f6ea-412d-8e76-a9cdc002ad77)
10. Your zine page will open in a new tab and TADA!! YOU HAVE DONE IT!!!
![Updated Deployment Website Page](https://github.com/user-attachments/assets/c93127b0-274a-468e-a218-c87b5d21bb9c)
11. Any time you make changes to your files after this, GitHub will automatically compile and deploy your pages after you commit your changes. If your page seems like it's behind on the changes, don't worry! If you got the check mark on the GitHub repository page, then all you have to do is refresh your Zine page, and all the updates should show up.
---

## Important Note

- Once you commit a change for the first time, you'll see something like this on the home page of your GitHub repository:

  ![Ahead is Normal](https://github.com/user-attachments/assets/36924fd3-7be8-44a4-83e0-7f495105b189)

This is completely normal!! Feel free to ignore it and go about your zine page editing!

---

UHHHHHHH I THINK THAT'S IT???? I'M PRETTY SURE I COVERED EVERYTHING LOL. You're all set to create your very own zine website. If you need any more help, just reach out. Have fun and happy zining! ✨

If you'd like to see what the template looks like, feel free to check it out: https://panpanicatmha.github.io/zinewebsitetemplate/
