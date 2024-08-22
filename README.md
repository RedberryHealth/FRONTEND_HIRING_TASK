# **Task: Senior Next.js Developer Assessment**

### Important Instructions:


Please ***clone the provided GitHub repository, do not download it. After completing the task, push your changes to a fork of the repository on your GitHub account.*** Send the link to your forked repository in response to the email you received regarding this task. Execution time will be evaluated based on the timestamp of the email and your reply. Each step will be assessed, including execution time, understanding of the tasks, response quality, and code quality.

Refer to the provided assessment table carefully, as each criterion will be graded to compare applicants. Note that bonus points are awarded at double the rate, but only if all mandatory tasks are successfully implemented.

Additionally, please consider the logo and images included in the repository to showcase your UI capabilities and skills in using Tailwind CSS and styling. You may choose from the provided color templates or use a combination of them.

**Thorough documentation** of your work, including using markup documents and ClickUp to illustrate how you grasped the task and organized your subtasks, is optional but will be considered a strong bonus. Demonstrating your ability to manage and communicate your work effectively through detailed documentation can significantly enhance your evaluation.

The mandatory completion time for this task is 24 hours (8 hours per day). If you complete the task within this timeframe, you will meet the basic requirements. However, to earn additional points, you are encouraged to extend the execution time to a maximum of 3 days. To gain more points, you may need to dedicate more hours per day beyond the standard 8 hours to showcase your commitment and ability to tackle the task more thoroughly.

**Bonus points will also be awarded for deploying your application for testing purposes.** This deployment should be accessible and functional to demonstrate your ability to prepare the app for a real-world environment.

### **Objective**

Build a simplified e-commerce product application using **Next.js** within 24 hours. The application should focus on the main features, showcasing skills in authentication, API integration, state management, UI design, SSR/SSG, error handling, and SEO optimization.

### **Mandatory Tasks (24-Hour Core Features)**

1. **Authentication with JWT**
   * Implement secure JWT authentication with refresh and expiration logic.
   * Handle token storage (localStorage/cookies).
   * Ensure that users cannot access certain pages without being authenticated.
   * Duration: **4 - 6 hours**
2. **Product API Integration**
   * Build a simple product API using Next.js API routes with CRUD operations (Create, Read, Update, Delete) for products.
   * Integrate the API with the frontend to display a product list and allow for product management (adding, editing, deleting).
   * Duration: **4 - 6 hours**
3. **Global State Management (Redux)**
   * Use Redux for state management to handle global state, including user authentication status and product data.
   * Demonstrate asynchronous data handling (e.g., API calls) using Redux Thunk or Redux Saga.
   * Duration: **3 - 4 hours**
4. **UI/UX Design**
   * Create a responsive product page layout with a clean design.
   * Ensure good user experience on different devices, focusing on responsiveness and usability.
   * Duration: **3 - 4 hours**
5. **SSR and SSG**
   * Implement Server-Side Rendering (SSR) for product detail pages.
   * Use Static Site Generation (SSG) for static pages (e.g., homepage, product listing) to improve performance.
   * Duration: **3 - 4 hours**
6. **Error Handling**
   * Handle errors gracefully, both on the frontend (UI feedback for users) and in API routes (proper error responses).
   * Display error messages on invalid API requests or form submissions.
   * Duration: **2 - 3 hours**
7. **SEO Optimization**
   * Add proper SEO optimizations including meta tags, dynamic title and description based on product data, and structured data.
   * Ensure pages are SEO-friendly with correct URL structures.
   * Duration: **2 - 3 hours**

### **Bonus Tasks (Optional Challenges)**

1. **Map Integration**
   * Integrate a map (e.g., Google Maps or OpenStreetMap) that allows users to select their location during the product order process.
   * Implement location-based features like a store locator or delivery address selection.
   * Bonus: **3 - 4 hours**
2. **Image Optimization**
   * Implement optimized image handling using `next/image` to enhance page loading performance.
   * Ensure responsive images are properly displayed at different sizes based on the device.
   * Bonus: **1 - 2 hours**
3. **Advanced Error Handling**
   * Implement custom error pages (e.g., 404, 500) to handle unexpected errors gracefully.
   * Bonus: **1 hour**
4. **Performance Optimization**
   * Apply performance optimizations such as lazy loading of components and dynamic imports for improving loading times.
   * Bonus: **2 - 3 hours**
5. **Product Search and Filtering**
   * Add product search and filtering functionality on the product listing page.
   * Enable users to filter products by category, price range, etc.
   * Bonus: **2 - 3 hours**
6. **Deploy for Testing**
   * deploy to Vercel or other
   * Bonus: 2-3 hours
7. Documentation
   * using markup

---

### **Assessment Criteria**

| **Category**          |                                                                          **Evaluation Points**                                                                          | Degree |
| :-------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ------ |
| **Code Quality**      |                               Proper organization, readability, use of modern best practices,<br />clean architecture, and modular components.                               |        |
| **Algorithm & Logic** |                        Efficiency and correctness of the implementation,<br />particularly with authentication, <br />state management, and API calls.                        |        |
| **UI/UX Design**      |                                 User interface aesthetics, ease of use,<br /> responsiveness across devices, and clarity of error messaging.                                 |        |
| **State Management**  |                  Effective use of Redux to manage complex state,<br /> including proper usage of actions, reducers, <br />and middleware for async handling.                  |        |
| **API Integration**   |     Solid integration with API routes, error handling for API calls,<br />secure data flow between frontend and backend, <br />and JWT authentication/authorization flow.     |        |
| **SSR/SSG**           |           Effective implementation of Server-Side Rendering and Static Site Generation,<br />demonstrating the developer’s ability to improve performance and SEO.           |        |
| **SEO Optimization**  | Proper use of meta tags, dynamic page titles, and SEO-friendly URLs.<br /> Implement structured data and<br /> follow best practices to enhance visibility on search engines. |        |
| **Error Handling**    |               Clear user-friendly error messages for invalid inputs,<br /> API issues, and missing pages.<br /> Proper handling of JWT expiration and refresh.               |        |
| **Execution Time**    |                                       Efficient implementation within the allocated 24 hours, with timely completion of core features.                                       |        |
| **Bonus Features**    |                                                         Ability to implement extra features such as maps integration,                                                         |        |
| **Bonus Features**    |                                                                              image optimization                                                                              |        |
| **Bonus Features**    |                                                                            advanced error handling                                                                            |        |
| **Bonus Features**    |                                                                           performance optimizations                                                                           |        |
| **Bonus Features**    |                                                                product search/filtering as additional effort.                                                                |        |
| **Execution Time**    |                                                                               3days./ 24 hours                                                                               |        |
| **UI and  Styles**   |                                                                 colorful responsive Tailwind and or other css                                                                 |        |
| **Bouns Features**    |                                            Documentation using Markup or other /using clickup and show how you organize your tasts                                            |        |

---

### **Submission Requirements**

* Provide access to a **GitHub repository** with your code, organized in a way that highlights the architecture.
* Ensure that a **README** is included to guide through setup, installation, and any important notes on features implemented.
* Deploy the app on a platform like **Vercel** or  **Netlify** , if possible, and share the live link.

### **Conclusion**

This task focuses on the core areas essential to demonstrate the skills of a senior Next.js developer while offering bonuses for those who want to showcase more advanced expertise. The developer is expected to prioritize functionality, performance, and good coding practices within the provided 24-hour time frame.
