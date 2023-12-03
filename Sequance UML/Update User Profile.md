<p><a target="_blank" href="https://app.eraser.io/workspace/8dUnVp48U2nFfwLNfxyQ" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

## Overview
The "Update User Profile" functionality allows users to update their profile information, including the option to insert new data, such as textual details and images. The entire process is orchestrated by the WebApp, with interactions involving user authentication, cloud storage for image handling, and Firestore for storing and retrieving user profile data.

## Sequence Diagram
The sequence diagram illustrates the flow of events during the "Update User Profile" process:

## Step-by-Step Explanation
1. **User inserts new data:**
    - The process begins when a user interacts with the WebApp to insert new data into their user profile.
2. **WebApp requests user ID from Authentication (AWS Cognito):**
    - The WebApp initiates user authentication by requesting the user ID from AWS Cognito.
3. **Authentication provides user ID:**
    - AWS Cognito responds by providing the user ID to the WebApp.
4. **WebApp checks for image data:**
    - If the inserted data includes an image, the WebApp proceeds to handle the image upload.
5. **Image Upload (Conditional):**
    - a. **WebApp uploads image to Storage (GCP Storage):**
        - If image data is present, the WebApp initiates the upload of the image to Google Cloud Storage.
    - b. **Storage provides image URL:**
        - Upon successful image upload, Google Cloud Storage provides the WebApp with the URL of the uploaded image.
6. **Firestore document update:**
    - The WebApp then proceeds to update the user profile document in Firestore by sending the new data, including the optional image URL.
7. **Firestore confirms document creation:**
    - Firestore processes the update and confirms the creation of the updated document in the 'userProfiles' collection.
8. **Process Completion:**
    - The entire "Update User Profile" process is completed, and the user profile information, including any newly inserted data or updated images, is now stored in Firestore.
## Components Used
- **User Interface:** The WebApp provides the interface for users to interact and insert new data into their profiles.
- **Authentication (AWS Cognito):** Responsible for authenticating users and providing user IDs.
- **Cloud Storage (GCP Storage):** Handles the optional upload and retrieval of user profile images.
- **Firestore (GCP Firestore):** Stores and retrieves user profile data, confirming the creation of updated documents.
## Notes
- **Image Handling:** The process includes conditional steps for handling images, allowing users to update their profile pictures.
- **Scalability:** The architecture leverages AWS Cognito for user authentication, GCP Storage for image handling, and GCP Firestore for scalable and reliable data storage.
- **User Feedback:** The WebApp can provide user feedback based on the confirmation received from AWS Cognito, GCP Storage, and GCP Firestore to ensure a smooth user experience.
This documentation provides an overview of the "Update User Profile" functionality, including the components involved and the step-by-step process. Developers can refer to this documentation for understanding the integration and implementation details of this feature.


<!--- Eraser file: https://app.eraser.io/workspace/8dUnVp48U2nFfwLNfxyQ --->