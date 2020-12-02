---
title: "What I've learned"
---

## Step 1: 
Create an `index.md` file for the *homepage*

## Step 2:
Congirure `_config.yml` file to set metadata in the header

## Step 3:
Learn GitHub flow -> commit changes to new branch for editing, then merge back to main when all changes are complete.

## Step 4:
Add *Front Matter* to an individual page to control variables on that page.

## Step 5: 
Observing how new pages are added to the layout. 
* Observations:
  * How to change the rendered navigation?
  * How and where are certain variable being carried over to? I noticed some repetition I didn't add.
    * The page header and duplicates from the `index.md` file. Deletion causes a build error.
  * How to create/format my own links?
    * Posts/pages are referenced my name and converted to **html* files so I can use that to link.
    * Any dashes used in the file name between numbers were converted to backslashes.
    * Dashes between words were left in place.
  * Would creating new folders create new website navigation, such as an images folder to act as a photo album? Or is the folder structure strict?
