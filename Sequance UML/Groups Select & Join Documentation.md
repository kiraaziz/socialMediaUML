<p><a target="_blank" href="https://app.eraser.io/workspace/lhjY0Mr5PKru1Qhmbd4o" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

## Overview
This documentation outlines the sequence of actions involved in the "Groups Select & Join" feature of the React application using Firebase services. The primary functionalities include selecting a group, fetching group information, checking user membership status, and allowing users to join groups.

## Description
1. **Select Group:**
    - The user interacts with the React application to select a group.
2. **Fetch Groups:**
    - ReactApp sends a request to Firestore to fetch information about the selected groups.
3. **Return Groups:**
    - Firestore returns the group information to ReactApp.
4. **Get User ID:**
    - ReactApp uses FirebaseAuth to retrieve the user's ID.
5. **Check Membership:**
    - If the user is a member of the selected group or the group is public, ReactApp requests and receives post data from Firestore.
6. **Display Posts:**
    - ReactApp displays posts for the selected group.
7. **Join Group:**
    - If the user is not a member of the group, ReactApp displays a join button.
8. **User Clicks Join:**
    - If the user clicks the join button, ReactApp sends a join request to Firestore and saves the user's membership.
9. **Feedback Message:**
    - Firestore provides feedback to ReactApp regarding the join request, and ReactApp displays a feedback message to the user.
10. **End:**
    - ReactApp is deactivated, concluding the sequence.
## Notes
- This sequence diagram provides a high-level overview of the interactions between the user, ReactApp, Firestore, and FirebaseAuth during the process of selecting and joining a group.
- The diagram illustrates the different paths based on whether the user is already a member of the group or if the group is public.
- The sequence includes steps for fetching group information, displaying posts, and handling user interactions for joining groups.



<!--- Eraser file: https://app.eraser.io/workspace/lhjY0Mr5PKru1Qhmbd4o --->