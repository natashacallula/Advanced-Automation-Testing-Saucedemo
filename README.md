# 🌟 **Advanced Automation Testing for Saucedemo** 🌟

This updated project enhances the previous automation test of the Saucedemo e-commerce demo platform by validating the website’s functionality using **individual user accounts** (standard, problem, performance glitch, error, and visual user) to simulate different user behaviors and issues.

## 📋 **Project Overview** 📋

While the previous version only tested functionality using the `standard_user` account, this new version dives deeper by testing core features separately under each type of valid user. This helps uncover unique behaviors, bugs, or limitations tied to each user profile.

## ⚙️ **Tools and Technologies** ⚙️
- **Cypress**: End-to-end testing framework (JavaScript-based).
- **Visual Studio Code**: Code editor used for test development.
- **Spreadsheet**: Used for test planning and documentation.
- **GitHub**: Source control for project versioning.
- **YouTube**: Hosted video evidence of test execution.

## 🚀 **How to Run the Tests** 🚀
1. Clone the repository:

   ```bash
   https://github.com/natashacallula/Advanced-Automation-Testing-Saucedemo
2. Install dependencies: yarn install
3. Launch Cypress: yarn run cypress open
4. Select and run the desired test group (e.g., standard_user, problem_user, etc.)

## 🧪 **Key Test Scenarios (per user)** 🧪
🧑‍💼 Authentication Tests
Login with each user:
   - standard_user
   - problem_user
   - performance_glitch_user
   - error_user
   - visual_user
     
🛒 Functional Testing (Per User Role)
Each user has dedicated test flows:
- Product sorting
- Add/remove items to cart
- Checkout process
- Filling shipping informations
- Logout

Testing each user type separately ensures that the system behaves correctly under different access levels and user conditions.

## 📁 **Test Plan Documentation** 📁 
  [Test Plan documented on Google Document](https://docs.google.com/document/d/1zBmVjJvIW17-U6QTMFy7qCXKVVHix6I3/edit?usp=sharing&ouid=100639890315581854970&rtpof=true&sd=true)

## 📄 **Test Scenario Documentation** 📄
  [Test Scenario documented on Spreadsheet](https://docs.google.com/spreadsheets/d/1XI9BbrBrG3_k5f7qBq3_p8uTzB1vGkT8mXo9e61RnfE/edit?usp=sharing)

## 📊 **Testing Evidence** 📊
***Watch the automation run-through on YouTube***

[![Testing Evidence](https://img.youtube.com/vi/joFs1QI4HTU/0.jpg)](https://www.youtube.com/watch?v=L7t6LzmR1Sk)
