<p><a target="_blank" href="https://app.eraser.io/workspace/C8YClxFWJBptQbxHGCQ9" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

## Application Feature: Create Document in Firestore Groups Collection
### Introduction
This feature enables users to insert data into the application, triggering the creation of a document in the 'groups' collection within Firestore. The process involves user interaction with the WebApp, authentication through the Auth service, and data storage in Firestore.

### Key Components
- **User:** Initiates the process by inserting data into the WebApp.
- **WebApp (Frontend):**
    - Responsible for rendering the user interface and handling user interactions.
    - Requests the user ID from the Auth service.
    - Communicates with Firestore to create a document in the 'groups' collection.
- **Auth (Authentication Service):**
    - Manages user authentication.
    - Provides the user ID to the WebApp.
- **Firestore (Database Service):**
    - Stores data in the 'groups' collection.
    - Confirms the creation of the document.
### User Workflow
1. **Data Insertion:**
    - Users initiate the process by inserting data into the WebApp.
2. **User ID Request:**
    - WebApp, hosted on GCP App Engine, requests the user ID from the Auth service.
3. **Authentication:**
    - Auth service, represented by AWS Cognito, authenticates the user and provides the user ID to the WebApp.
4. **Document Creation:**
    - WebApp communicates with Firestore to create a document in the 'groups' collection, incorporating the user-provided data.
5. **Confirmation:**
    - Firestore, represented by the GCP Firestore icon, processes the request and confirms the successful creation of the document.
### Sequence of Actions (Sequence Diagram)
The sequence diagram visually depicts the interaction between the User, WebApp, Auth service, and Firestore during the process of creating a document in the 'groups' collection.

### Conclusion
This feature enhances the application's functionality by allowing users to seamlessly insert data, which is securely stored in Firestore. The authentication process ensures that data manipulation is restricted to authorized users.

### Introduction
This feature enables users to insert data into the application, triggering the creation of a document in the 'groups' collection within Firestore. The process involves user interaction with the WebApp, authentication through the Auth service, and data storage in Firestore.

### Key Components
- **User:** Initiates the process by inserting data into the WebApp.
- **WebApp (Frontend):**
    - Responsible for rendering the user interface and handling user interactions.
    - Requests the user ID from the Auth service.
    - Communicates with Firestore to create a document in the 'groups' collection.
- **Auth (Authentication Service):**
    - Manages user authentication.
    - Provides the user ID to the WebApp.
- **Firestore (Database Service):**
    - Stores data in the 'groups' collection.
    - Confirms the creation of the document.
### User Workflow
1. **Data Insertion:**
    - Users initiate the process by inserting data into the WebApp.
2. **User ID Request:**
    - WebApp, hosted on GCP App Engine, requests the user ID from the Auth service.
3. **Authentication:**
    - Auth service, represented by AWS Cognito, authenticates the user and provides the user ID to the WebApp.
4. **Document Creation:**
    - WebApp communicates with Firestore to create a document in the 'groups' collection, incorporating the user-provided data.
5. **Confirmation:**
    - Firestore, represented by the GCP Firestore icon, processes the request and confirms the successful creation of the document.
### Sequence of Actions (Sequence Diagram)
The sequence diagram visually depicts the interaction between the User, WebApp, Auth service, and Firestore during the process of creating a document in the 'groups' collection.

### Conclusion
This feature enhances the application's functionality by allowing users to seamlessly insert data, which is securely stored in Firestore. The authentication process ensures that data manipulation is restricted to authorized users.

### Introduction
This feature enables users to insert data into the application, triggering the creation of a document in the 'groups' collection within Firestore. The process involves user interaction with the WebApp, authentication through the Auth service, and data storage in Firestore.

### Key Components
- **User:** Initiates the process by inserting data into the WebApp.
- **WebApp (Frontend):**
    - Responsible for rendering the user interface and handling user interactions.
    - Requests the user ID from the Auth service.
    - Communicates with Firestore to create a document in the 'groups' collection.
- **Auth (Authentication Service):**
    - Manages user authentication.
    - Provides the user ID to the WebApp.
- **Firestore (Database Service):**
    - Stores data in the 'groups' collection.
    - Confirms the creation of the document.
### User Workflow
1. **Data Insertion:**
    - Users initiate the process by inserting data into the WebApp.
2. **User ID Request:**
    - WebApp, hosted on GCP App Engine, requests the user ID from the Auth service.
3. **Authentication:**
    - Auth service, represented by AWS Cognito, authenticates the user and provides the user ID to the WebApp.
4. **Document Creation:**
    - WebApp communicates with Firestore to create a document in the 'groups' collection, incorporating the user-provided data.
5. **Confirmation:**
    - Firestore, represented by the GCP Firestore icon, processes the request and confirms the successful creation of the document.
### Sequence of Actions (Sequence Diagram)
The sequence diagram visually depicts the interaction between the User, WebApp, Auth service, and Firestore during the process of creating a document in the 'groups' collection.

### Conclusion
This feature enhances the application's functionality by allowing users to seamlessly insert data, which is securely stored in Firestore. The authentication process ensures that data manipulation is restricted to authorized users.


<!--- Eraser file: https://app.eraser.io/workspace/C8YClxFWJBptQbxHGCQ9 --->