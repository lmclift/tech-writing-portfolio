# Sample 1: DLP Development Process Quick Start Guide
## Summary
**Business Requirements:** The customer needed a high-level document outlining the process of how a Desk Level Procedure (DLP) was developed and moved through the review, approval, and publication process.

**Target Audience:** This guide was designed primarily for new technical writers, but could also be used as a reference for business analysts and other internal stakeholders who were not familiar with the DLP development process.

**Writing Process:** Since this document outlined my job responsibilities, I primarily referenced my own notes and the existing training material I used while onboarding for the position. It was originally meant to be maintained as a MS Word document on the department's SharePoint site for easy reference.

---

## DLP Development Quick Start Guide
### Purpose
The Desk Level Procedure (DLP) development process exists to make the creation and publication of DLPs as smooth and efficient as possible while also ensuring that the end result is as accurate and complete as possible. This document aims to provide a high-level overview of this process.
### Process
#### Responding to a New Request
1. Assign the request to yourself using the **Assign** button.
2. Move to **In Business Requirements** when starting the research process.
#### Developing the DLP
1. Set the request status to In Development once you have the necessary information to begin developing the DLP.
2. Setting up the DLP file:
    1. **For a DLP revision:** Copy the DLP file from the main ORL folder into the corresponding folder in staging area (O:\MANGO\Staging Area)
    2. **For a new DLP:**
        1. Determine where the DLP needs to go (ex: for a new call center DLP, the file would be placed in **O:\CallCtr\groups**).
        2. Copy the DLP template file from the **_Templates** folder and paste into the folder where the DLP will be stored.
3. Make needed changes to the DLP.
    1. Save any images used in the DLP to the corresponding images folder.
    2. Save any external attachments that will be linked in the DLP (PDFs, Excel Spreadsheets, etc.) to the external folder.
4. Once DLP is complete, copy the DLP file and any image files or external attachments (linked PDFs, Excel spreadsheets, etc.) to the **_Test Area** folder.
5. Run the trigger file to push updates to the test site.
#### Requesting Peer Review
1. Once the peer review is complete, move the request to **In Review** status.
2. Enter a comment notifying the Reporter and Participants (if applicable) that the DLP is ready for review. Include the test link to the DLP and a timeframe for completion.
3. Add the individual who needs to provide final approval to the request as the **Business Approver**.
4. When the review is complete and the requested participants have provided their approval, move the status to **Awaiting Approval**.
5. Tag the Business Approver(s) in the comment requesting their final approval.
6. Once the Business Approver(s) have clicked the Approve button, the DLP is ready to be put into production.
#### Putting the DLP into Production
1. Move the Jira request to In QA Testing status.
2. Finish the DLP file:
    1. Add date to the updated/new DLP in the **_Test Area** folder.
    2. If the DLP is a revision, back up the current DLP in **Back-Ups** folder.  
    3. Copy updated DLP from **_Test Area** into production folder.
    4. Copy any images or external files into the appropriate folders (images, external, etc.).
3. **If publishing a new DLP:** Run the Zoom Indexer.
    1. Back up Zoom Index files in personal back-up folder.
    2. Delete the trigger file from drive.
    3. Run the indexer (should take about 45-60 minutes).
    4. Once the indexer has finished, paste the trigger file back into the drive.
4. Run the trigger file to push the updated DLP.
#### Closing Out the Request
1. Complete the following in Jira:
    1. T-shirt size
    2. Select the request type (New DLP, Revise DLP, Delete DLP)
    3. Mark the request as **Done**.
2. Draft an ORL Update email for the DLP update.  

### Final Notes
1. To back up a file:
    1. Go to the folder for the current year.
    2. Create a folder with a date for the current week, if one has not been made already.
    3. In this folder, create a file path that mirrors how the DLP is stored on the drive. The file path should look something like this: **O:\Back-Ups\2022\0905\CallCtr\groups\DLP.html**
2. DLP updates are sent on Fridays using the **Update email template**. If the DLP is being completed and closed out on a day other than Friday, start a draft email template and enter the relevant information.