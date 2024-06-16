Project Video Link: https://drive.google.com/file/d/1vURURuLUCFyx9Q3X_dsgDNzjVahErsvT/view?usp=sharing

==================== Project Description ====================

![Screenshot 2024-06-16 151042](https://github.com/jay-228/React-Navigator_/assets/122542095/59316108-56fd-4365-bb3c-20e079bf11fb)
![Screenshot 2024-06-16 151054](https://github.com/jay-228/React-Navigator_/assets/122542095/b5b8cbc4-68bb-4e92-b20c-b385c852497c)
![Screenshot 2024-06-16 151120](https://github.com/jay-228/React-Navigator_/assets/122542095/cb7aea69-aeb7-4249-9e68-f05e699d7641)


**Objective:**
Build a web application using React.js that showcases a product catalog. Users should be able to navigate through different pages such as Home, About, and Products. The Products page will display a list of products fetched from a JSON Placeholder API. Additionally, there will be a Project page where users can view details of a specific product. The Products page should be private and accessible only to authenticated users. Axios will be used for making network requests.

**Tasks:**

1. Set up a new React.js project using Create React App.
2. Install React Router DOM and Axios dependencies using npm.
    
    ```bash
    
    npm install react-router-dom axios json-server@0.17.4
    
    ```
    
3. Create the following components:
    - `Home`: Display a welcome message and brief introduction to the application.
    - `About`: Provide information about the application and its purpose.
    - `Products`: Display a list of products fetched from the JSON Placeholder API. Make sure this page is private and accessible only to authenticated users.
    - `Project`: Display detailed information about a specific product selected by the user.
    - `Login`: Create a simple login form for users to authenticate themselves.
4. Implement routing using React Router DOM:
    - Define routes for Home, About, Products, Project, and Login components.
    - Set up private routes to ensure the Products page is only accessible to authenticated users.
5. Use Axios to make network requests:
    - Fetch a list of products from the JSON Placeholder API in the Products component.
    - Fetch details of a specific product when a user navigates to the Project page.
    
    > Use This Url:-https://fakestoreapi.com/products
    > 
    
    > use for token:https://reqres.in/api/login
    >
