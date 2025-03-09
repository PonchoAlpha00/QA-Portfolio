## 📌 **Gherkin Test Scenarios**

### **Scenario 1: Search Functionality on E-commerce Website**
**Given** I am on the homepage  
**When** I enter "iPhone 13" in the search bar  
**Then** I should see relevant products displayed  

### **Scenario 2: User Registration Process**
**Given** I am on the registration page  
**When** I enter valid details and submit the form  
**Then** my account should be created successfully  
**And** I should receive an email confirmation  

### **Scenario 3: Password Reset Functionality**
**Given** I am on the login page  
**When** I click on 'Forgot Password' and enter my registered email  
**Then** I should receive a password reset link via email  
**And** I should be able to reset my password successfully  

### **Scenario 4: Adding Items to Shopping Cart**
**Given** I am viewing a product page  
**When** I click on 'Add to Cart'  
**Then** the item should be added to my shopping cart  

### **Scenario 5: Checkout Process**
**Given** I have items in my cart  
**When** I proceed to checkout and enter valid payment details  
**Then** my order should be successfully placed  
**And** I should receive an order confirmation  

### **Scenario 6: Logout Functionality**
**Given** I am logged into my account  
**When** I click on the 'Logout' button  
**Then** I should be logged out  
**And** I should be redirected to the login page  

### **Scenario 7: Responsive Design Test**
**Given** I open the website on a mobile device  
**When** I navigate through different pages  
**Then** the layout should be responsive and user-friendly  

### **Scenario 8: Payment Gateway Validation**
**Given** I am on the checkout page with items in my cart  
**When** I enter valid payment details and confirm the payment  
**Then** the payment should be processed successfully  
**And** I should receive a transaction confirmation  

### **Scenario 9: Invalid Login Attempt**
**Given** I am on the login page  
**When** I enter incorrect login credentials  
**Then** I should see an error message indicating invalid credentials  

### **Scenario 10: Wishlist Functionality**
**Given** I am viewing a product page  
**When** I click on 'Add to Wishlist'  
**Then** the item should be added to my wishlist  
**And** I should see it under my wishlist section  