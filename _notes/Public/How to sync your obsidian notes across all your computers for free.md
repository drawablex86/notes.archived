---
title: How to sync your obsidian notes across all your computers for free 
notetype : lit
date: 2021-04-18
---



Hello, note taker, if you are here reading this, it is highly likely that you are in love with [[markdown]] and you are using [Obsidian](https://obsidian.md/) as the go to tool for taking your notes. 

I love obsidian for its local first storage option (all your notes are saved to your computer) and amazing graph feature. But what if you are like me and work on multiple computer on the same day; I jump from my desktop to laptop from time to time. Technically, you can use the [Obsidian Sync](https://obsidian.md/sync) feature that costs you 4 USD per month (billed annually)

But we want to do it for free, ie sync your notes for free. 
Enter ["Git Hub"](https://github.com/)

## Prerequisites
1. You must have an account in Git Hub. If you don't already here is [[How you can create a github account]]
2. You must have [github desktop](https://desktop.github.com/) installed 


## Here is how it is done
1. Load up and  connect  your Git hub desktop from **Computer A** to your Git hub account, if you have already done that.
2. Create a new repository and use your "Obsidian Vault" folder as your reposite directory. 
	1. Make sure you leave **make this repository private** check box marked so that your precious notes does not end up in the hands of every other random git surfer.
	2. As a tip try not to leave spaces for you fault names; ie if you vault is named *"Obsidian Private" *, change it to say for eg: *"Obsidian-Private"*. This is because git hub does not recognize spaces and automatically fill it up. By making the change early you will get the same vault name across all your computers.
3. Now that you have created the new repo, you need to upload the content to git hub online. But it's easy, in the Git hub desktop client, you can find an option to **"Push"** the contents and voila its set.
4. Now to access your vault in **Computer B** load up  Git hub desktop and connect to your Git hub account just like earlier
5. Once you are connected you can **"Pull"** your *"Obsidian-Private"* folder into the location of your choosing in  **Computer B**.
6. And with the step your syncing setup is done. Now all you have to do you open the vault folder using obsidian in **Computer B** and you can see all your files from **Computer A** there.
7. There is two more steps you will need to do every time you take or edit notes in Obsidian:
	1. After making changes, go back to your Git hub desktop "Press Commit" and "Push" it to cloud. *We don't have an option for auto sync as it is not "Git's" primary purpose. Ever time you Commit and Push, your files gets uploaded to your privte github account*
	2. Similarly when you hop on to **Computer B** remember to **"pull"** so that your fault in **Computer B** has all your latest notes.
8. Finally, you can add any number of computers to this setup using Git Hub desktop as long as don't forget to push and pull your files as needed.

**Note**: If you find all the terms like pull, push and commit confusing here is a  [video](https://www.youtube.com/watch?v=C69-s2o9wqw) to help you get up to speed. If you are more into text based guides, [here's that](https://docs.github.com/en/desktop)

*Alternatively, you can sync your files using one drive, google drive or any other cloud providers. The only problem is they come with limited storage you might be already filling it up with other documents and files if you are in the free tier*

See Also: [[How to sync, read and edit your obsidian notes in an android device]]




#obsidian


