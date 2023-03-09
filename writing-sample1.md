# Sample 1: DLP Development Process Overview
## Summary
The customer needed a short document that outlined the broad overview of how a Desk Level Procedure (DLP) was developed and moved through the review, approval, and publication process. This document would be used as a quick reference for new technical writers, business analysts, and other internal stakeholders who were not familiar with the DLP development process.
## DLP Development Quick Reference Guide
### When a New Request is Submitted in Jira
1. Navigate to the Project.
2. Assign the request to yourself using the **Assign** button.
3. Move to **In Business Requirements** when starting the research process.
### Working on the DLP
1. Set the request status to In Development once you have the necessary information to begin developing the DLP.
2. Setting up the DLP file:
    1. **For a DLP revision:** Copy the DLP file from the main ORL folder into the corresponding folder in staging area (C:\MANGO\Staging Area)
    2. **For a new DLP:**
        1. Determine where the DLP needs to go (ex: for a new call center DLP, the file would be placed in **C:\CallCtr\groups**).
        2. Copy the DLP template file from the **_Templates** folder and paste into the folder where the DLP will be stored.
3. Make needed changes to the DLP.
    1. Save any images used in the DLP to the corresponding images folder.
    2. Save any external attachments that will be linked in the DLP (PDFs, Excel Spreadsheets, etc.) to the external folder.
4. Once DLP is complete, copy the DLP file and any image files or external attachments (linked PDFs, Excel spreadsheets, etc.) to the **_Test Area** folder.
5. Run the trigger file to push updates to the test site.
### Requesting Peer Review
1. Once the peer review is complete, move the request to **In Review** status.
2. Enter a comment notifying the Reporter and Participants (if applicable) that the DLP is ready for review. Include the test link to the DLP and a timeframe for completion.
3. Add the individual who needs to provide final approval to the request as the **Business Approver**.
4. When the review is complete and the requested participants have provided their approval, move the status to **Awaiting Approval**.
5. Tag the Business Approver in the comment requesting their final approval. Once they have clicked the Approve button, the DLP is ready to be put into production.
### Putting a DLP into Production
1. Move the Jira request to In QA Testing status.
2. Finish the DLP file:
    1. Add date to the updated/new DLP in the **_Test Area** folder.
    2. If the DLP is a revision, back up the current DLP in **Back-Ups** folder.  
    **Note:** Create folders to mirror how the DLP is stored on the drive (ex. C:\Back-Ups\2022\0905\CallCtr\groups)
    3. Copy updated DLP from **_Test Area** into production folder (ex: CallCtr\groups)
    4. Copy any images or external files into appropriate folders (images, external, etc.)
3. **If publishing a new DLP:** Run the Zoom Indexer.
    1. Back up Zoom Index files from **C:\CallCtr\search** folder into personal back-up folder.
    2. Delete the trigger file from drive.
    3. Run the indexer (should take about 45-60 minutes).
    4. Once the indexer is done, paste the trigger file back into the drive.
4. Run the trigger file to push the search updates.
### Closing Out the Request
1. Complete the following in Jira:
    1. T-shirt size
    2. Select the request type (New DLP, Revise DLP, Delete DLP)
    3. Mark the request as **Done**.
2. Draft an ORL Update email blast for the DLP update.  
**Note:** DLP updates are sent on Mondays in the Update email template. If the DLP is being completed and closed out on a day other than Monday, start a draft email template and enter the relevant information.