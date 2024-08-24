# **Task: Senior Next.js Developer Assessment**

### Important Instructions:

Please **clone the provided GitHub repository.** After cloning, set up the
project on your local machine and implement the required task according to the
provided assessment rubric. Once you've completed the task, you will
**demonstrate the project during a technical interview** , where we will review
your implementation together. During the interview, we will also assign a
**subtask** to be completed live within **1 hour** , using the project you've
implemented on your machine.

Make sure not to send your response until the task is fully completed and ready
for review. Your execution time will be calculated from the moment you received
the task via email until the time you respond, indicating that you are ready for
the interview. This time will be factored into your evaluation.

Please note, the **technical interview** will be held on the **same day** you
send your email indicating the task is completed and ready for review.
Therefore, only send your response when you are confident that your project is
ready for the next step.

You will be evaluated based on:

- **Execution time** (calculated from email receipt to response).
- **Code quality and understanding** of the task.
- **UI skills** using the logo, images, and color templates provided in the
  repository.
- **Live coding performance** during the 1-hour subtask implementation in the
  interview.

Additionally, bonus points will be awarded for:

- **Thorough documentation** of your task breakdown using markdown files and
  project management tools.
- **Deploying the application** for testing purposes to demonstrate its
  readiness for real-world use.

Remember, the project should be implemented locally on your machine following
the provided guidelines, and **your code and project setup will be reviewed
during the technical interview** .

### **Objective**

Build a simplified e-commerce product application using **Next.js** within 24
hours. The application should focus on the main features, showcasing skills in
authentication, API integration, state management, UI design, SSR/SSG, error
handling, and SEO optimization.

### **Mandatory Tasks (24-Hour Core Features)**

1. **Authentication with JWT**
   - Implement secure JWT authentication with refresh and expiration logic.
   - Handle token storage (localStorage/cookies).
   - Ensure that users cannot access certain pages without being authenticated.
   - Duration: **4 - 6 hours**
2. **Product API Integration**
   - Build a simple product API using Next.js API routes with CRUD operations
     (Create, Read, Update, Delete) for products.
   - Integrate the API with the frontend to display a product list and allow for
     product management (adding, editing, deleting).
   - Duration: **4 - 6 hours**
3. **Global State Management (Redux)**
   - Use Redux for state management to handle global state, including user
     authentication status and product data.
   - Demonstrate asynchronous data handling (e.g., API calls) using Redux Thunk
     or Redux Saga.
   - Duration: **3 - 4 hours**
4. **UI/UX Design**
   - Create a responsive product page layout with a clean design.
   - Ensure good user experience on different devices, focusing on
     responsiveness and usability.
   - Duration: **3 - 4 hours**
5. **SSR and SSG**
   - Implement Server-Side Rendering (SSR) for product detail pages.
   - Use Static Site Generation (SSG) for static pages (e.g., homepage, product
     listing) to improve performance.
   - Duration: **3 - 4 hours**
6. **Error Handling**
   - Handle errors gracefully, both on the frontend (UI feedback for users) and
     in API routes (proper error responses).
   - Display error messages on invalid API requests or form submissions.
   - Duration: **2 - 3 hours**
7. **SEO Optimization**
   - Add proper SEO optimizations including meta tags, dynamic title and
     description based on product data, and structured data.
   - Ensure pages are SEO-friendly with correct URL structures.
   - Duration: **2 - 3 hours**

### **Bonus Tasks (Optional Challenges)**

1. **Map Integration**
   - Integrate a map (e.g., Google Maps or OpenStreetMap) that allows users to
     select their location during the product order process.
   - Implement location-based features like a store locator or delivery address
     selection.
   - Bonus: **3 - 4 hours**
2. **Image Optimization**
   - Implement optimized image handling using `next/image` to enhance page
     loading performance.
   - Ensure responsive images are properly displayed at different sizes based on
     the device.
   - Bonus: **1 - 2 hours**
3. **Advanced Error Handling**
   - Implement custom error pages (e.g., 404, 500) to handle unexpected errors
     gracefully.
   - Bonus: **1 hour**
4. **Performance Optimization**
   - Apply performance optimizations such as lazy loading of components and
     dynamic imports for improving loading times.
   - Bonus: **2 - 3 hours**
5. **Product Search and Filtering**
   - Add product search and filtering functionality on the product listing page.
   - Enable users to filter products by category, price range, etc.
   - Bonus: **2 - 3 hours**
6. **Deploy for Testing**
   - deploy to Vercel or other
   - Bonus: 2-3 hours
7. Documentation
   - using markup

---

### **Assessment Criteria**

| **Category**          |                                                                             **Evaluation Points**                                                                             | Degree |
| :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ------ |
| **Code Quality**      |                               Proper organization, readability, use of modern best practices,<br />clean architecture, and modular components.                                |        |
| **Algorithm & Logic** |                        Efficiency and correctness of the implementation,<br />particularly with authentication, <br />state management, and API calls.                        |        |
| **UI/UX Design**      |                                 User interface aesthetics, ease of use,<br /> responsiveness across devices, and clarity of error messaging.                                  |        |
| **State Management**  |                  Effective use of Redux to manage complex state,<br /> including proper usage of actions, reducers, <br />and middleware for async handling.                  |        |
| **API Integration**   |     Solid integration with API routes, error handling for API calls,<br />secure data flow between frontend and backend, <br />and JWT authentication/authorization flow.     |        |
| **SSR/SSG**           |           Effective implementation of Server-Side Rendering and Static Site Generation,<br />demonstrating the developer’s ability to improve performance and SEO.            |        |
| **SEO Optimization**  | Proper use of meta tags, dynamic page titles, and SEO-friendly URLs.<br /> Implement structured data and<br /> follow best practices to enhance visibility on search engines. |        |
| **Error Handling**    |               Clear user-friendly error messages for invalid inputs,<br /> API issues, and missing pages.<br /> Proper handling of JWT expiration and refresh.                |        |
| **Execution Time**    |                                       Efficient implementation within the allocated 24 hours, with timely completion of core features.                                        |        |
| **Bonus Features**    |                                                         Ability to implement extra features such as maps integration,                                                         |        |
| **Bonus Features**    |                                                                              image optimization                                                                               |        |
| **Bonus Features**    |                                                                            advanced error handling                                                                            |        |
| **Bonus Features**    |                                                                           performance optimizations                                                                           |        |
| **Bonus Features**    |                                                                product search/filtering as additional effort.                                                                 |        |
| **Execution Time**    |                                                                               3days./ 24 hours                                                                                |        |
| **UI and  Styles**    |                                                                 colorful responsive Tailwind and or other css                                                                 |        |
| **Bouns Features**    |                                            Documentation using Markup or other /using clickup and show how you organize your tasts                                            |        |

---

### **Requirements**

- Ensure that a **README** is included to guide through setup, installation, and
  any important notes on features implemented.
- Deploy the app on a platform like **Vercel** or **Netlify** , if possible, and
  share the live link.
