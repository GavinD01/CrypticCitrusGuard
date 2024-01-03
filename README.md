#########################################################################################################################################################################################################################################################################################################

This application was build to GET and POST user inputs aswell as securing the data during transport. Below were the requirements 
**Backend Development:**

1. **Setup MongoDB in the Cloud:**
   - Deploy a MongoDB database in the cloud environment, ensuring proper configuration and access controls.

2. **Generate SSL Certificate and Private Key:**
   - Obtain or generate an SSL certificate and private key to enable secure communication over HTTPS.

3. **CRUD Operations for Posts:**
   - Implement backend API endpoints for creating, reading, updating, and deleting posts.
   - Ensure all interactions with the database are conducted over SSL.

4. **User Registration/Login:**
   - Develop API routes for user registration and login.
   - Implement password encryption to securely store and compare passwords.
   - Use SSL for secure communication.

5. **CORS Handling:**
   - Implement Cross-Origin Resource Sharing (CORS) to allow secure communication between frontend and backend.

6. **Separation of Routes:**
   - Establish separate routes for handling posts and user-related operations.
   - Implement necessary authentication and authorization mechanisms.

7. **Persistent Login Information:**
   - Implement a mechanism to persist login information after authentication.

8. **Security Measures:**
   - Implement additional security packages such as `express-brute`, `helmet`, and `morgan` for enhanced security measures.

**Frontend Development:**

1. **Display/Create/Delete Posts:**
   - Develop frontend components to display, create, and delete posts.
   - Ensure secure communication with the backend API using services.

2. **User Registration/Login:**
   - Create frontend components for user registration and login.
   - Implement secure communication with the backend for these operations.

3. **Input Validation and Sanitization:**
   - Implement input field validation and sanitization to enhance security and prevent malicious inputs.

4. **Password Obscuring:**
   - Implement password obscuring techniques to enhance the security of user credentials.

5. **Error Messages:**
   - Create a custom component to display clear and informative error messages in case of issues.

6. **Persistent Login Information:**
   - Develop a mechanism to persist login information after successful authentication.

7. **Security Packages:**
   - Implement additional security packages like `express-brute`, `helmet`, and `morgan` to fortify the frontend against potential security threats.

###############################################################################################################################################################################################################################################################################################################################################################
