# GraniteLabels

The purpose of this repository is to have one central place for all our production labels.

## Repository structure

- All labels (ZPL, bartender etc) is located in Labels folder.
- The label folder is purely for use for labels no documents and no install.
- All installs of software is located in DropBox.
- Any documentation that you feel should accompany the labels should be added to Docs folder

## Basic guidelines
- Never copy your GitHub folder and place it somewhere else (hidden files and folders in that folder will corrupt)
- Never work outside the GitHub folder and then replace files inside GitHub, always work on the original file from GitHub
- On your locally machine try to not have any duplicate files, don't copy files to work `offline` this is a bad practice 
- Pull (fetch the latest file from GitHub)
- Commit (see this as saving a file locally on your machine, it is not yet updated to GitHub)
- Push (Push will update GitHub)

## Best practices comment
- Comments are important, comment on what you did to the file (the change)
- Prefix the comment with Change, Fix or New
- You do not have to comment the reason behind what you did, or who instructed you to do it
- Keep the comment relevant to the change in the file you made
- Examples
-- Change (add SerialNumber to label)
-- Change (remove ExpiryDate)
-- New (new label for TrackingEntity)

# Basic Workflow

1. Pull latest before you begin working on any file
2. Make the change on the original file (do not copy and replace files, work on the file in GitHub that is checked out)
3. Commit as soon as you done (don’t leave checked out)
4. Add with meaningful comment 
5. Push straight after you have Commit the change
