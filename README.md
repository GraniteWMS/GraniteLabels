# GraniteLabels

The purpose of this repository is to have one central place for all Granite WMS production labels.
Take note that you can add a `Readme.md` file to any folder and that will display on the GitHub page, the purpose of this is to document the repository.

## Repository structure

- All labels (ZPL, bartender etc) is located in Labels folder.
- The label folder is purely for use for labels no documents and no install.
- All installs of software is located in DropBox.
- Any documentation that you feel should accompany the labels should be added to Docs folder

## Basic guidelines
- Never copy your GitHub folder and place it somewhere else (hidden files and folders in that folder will corrupt)
- Never work outside the GitHub folder and then replace files inside GitHub, always work on the original file from GitHub
- On your local machine try to not have any duplicate files, don't copy files to work `offline` this is a bad practice 

## Basic Workflow

1. **Pull** latest before you begin working on any file
2. Make the change on the original file (do not copy and replace files, work on the file in GitHub that is checked out)
3. **Commit** as soon as you done (don’t leave checked out)
4. When committing add meaningful **comment** *see below: Best practices comment* 
5. **Push** straight after you have Commit the change

## Best practices comment
- Comment on what you did to the single file that you are about to **Commit** and **Push**
- Prefix the comment with **Change, Fix, New*** depending on what you have done 
- You do not have to comment the reason behind what you did, or who instructed you to do it, we are only interested to view the change on the single file and the comment you made for that change
- **Examples**
-- Change (add SerialNumber to label)
-- Change (remove ExpiryDate)
-- New (new label for TrackingEntity)

