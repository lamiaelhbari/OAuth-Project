## *Set Up GitHub OAuth Application*

*In this project, we will use GitHub to authenticate our web application. Before we start coding, we need to register an OAuth application on GitHub.*

### *Setup Steps*

1. **Register an OAuth application on GitHub**
   - *Go to [GitHub Developer Settings].*
   - *Click "New OAuth App" to create a new application.*
   - *Fill in the required information, such as the application name, application URL, and callback URL.*
   - *After registering the application, note down the `Client ID` and `Client Secret` provided by GitHub.*

2. **Implement OAuth in the project**
   - *We used the `express-session` module to manage user sessions.*
   - *The `passport` module was configured using GitHub credentials for authentication.*
   - *We set up the necessary URL routes for the authentication process.*

3. **Protect routes**
   - *A middleware function was implemented to protect routes and ensure that only authenticated users can access them.*

*By following these steps, you will be able to set up GitHub OAuth authentication in your web application.*
