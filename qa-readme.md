# RiskSmart QA Tech Test

Please do not fork this repo, submit your application (excluding dependencies) in a Zip file.

### **Objective**:
- Automate a basic flow on a public website using Playwright.
- Evaluate how well the candidate can automate browser interactions and assert the correct behaviour of a website.
- If you have limited access or resources please let us know we can help at any time for this test.

### **Public Site**:
You can choose any public website, such as a simple e-commerce site or a news site like [https://www.demoblaze.com/](https://www.demoblaze.com/) (a basic e-commerce demo site). 

### **Task**: 
Automate the following scenarios on the website using Playwright.

---

### **Scenario 1 example: Add Items to Cart and Verify Total**

1. **Go to Homepage**: The test should navigate to the home page of the website.
2. **Select a Category**: For example, in the demo store, select "Laptops."
3. **Select an Item**: Select a specific item, such as the "Sony Vaio i5."
4. **Add the Item to Cart**: Click the "Add to Cart" button.
5. **Navigate to Cart**: Click the cart button to go to the shopping cart page.
6. **Verify the Item**: Ensure that the item added to the cart is present and the price is correct.

#### Assertions:
- Ensure the item name and price are correctly displayed in the cart.
- Assert the total cost in the cart.

---

### **Scenario 2 example: Fill in Contact Form**

1. **Navigate to Contact Page**: Click on the "Contact" link from the menu.
2. **Fill in Form Fields**: Automate filling in the fields for:
   - Email (e.g., `test@example.com`)
   - Name (e.g., `John Doe`)
   - Message (e.g., `This is a test message.`)
3. **Send the Message**: Click the "Send Message" button.
4. **Verify Confirmation**: Capture and assert any confirmation message or alert that appears.

#### Assertions:
- Ensure that a confirmation alert or message is displayed after sending the form.

---

### **Scenario 3 example: Validate Search Functionality**

1. **Go to Homepage**: Ensure the script starts at the homepage.
2. **Search for an Item**: Enter a search term like "Laptop" in the search box and submit the search.
3. **Verify Results**: Ensure that the search results page shows items related to the search query.

#### Assertions:
- Verify that at least one result is returned for the search.
- Assert that the search term appears in the search results.

---

### **Test Requirements**:
1. **Environment**: Use Node.js and Playwright.
2. **Documentation**: The candidate should provide brief documentation on how to run the test and what is being tested.
3. **Code Quality**: Focus on the code structure, readability, and how well the tests are written.
4. **Edge Cases**: Encourage the candidate to think about edge cases and error handling (e.g., what happens if no items are found in the search).

---

### **Bonus Tasks (Optional)**:
- Use Playwright’s screenshot feature to capture screenshots on test failures.

---

### **Deliverables**:
  - Test code written in Playwright.
  - A README file with instructions on how to run the tests.
  - Any additional documentation or comments explaining the candidate’s thought process.

---

This test checks multiple aspects: automation scripting, interaction with web elements, assertions, and some optional aspects such as CI/CD integration for advanced candidates. Let me know if you'd like help with more details, or if you want to change anything!
