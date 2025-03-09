## 📌 **Test Case 1: Search Functionality on E-commerce Website**

**Test Case ID:** TC-001  
**Title:** Validate Search Functionality with Different Inputs  
**Description:** Ensure the search bar returns correct results when searching for products using various input types.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Navigate to homepage | - | Homepage is displayed |
| 2 | Enter search term | "iPhone 13" | Relevant products appear |
| 3 | Enter a partial search term | "Smart" | Suggested items related to "Smart" appear |
| 4 | Enter a non-existing product | "abcdefg1234" | No results message displayed |
| 5 | Enter special characters | "!!@@##" | Error or validation message displayed |

### **Preconditions**
- User is logged in (if required)
- Website is online

### **Expected Outcome**
- Search results should be accurate and responsive.

### **Postconditions**
- Search bar remains functional.

### **Test Priority:** High  
### **Test Type:** Functional, UI  
### **References:** Req-001, Jira Ticket #123  

---

## 📌 **Test Case 2: User Registration Process**

**Test Case ID:** TC-002  
**Title:** Validate New User Registration  
**Description:** Ensure that a new user can register successfully.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Navigate to registration page | - | Registration page is displayed |
| 2 | Fill in mandatory fields | Name, Email, Password | Fields accept valid input |
| 3 | Submit the form | - | User account is created |
| 4 | Verify email confirmation | Email received | User can activate account |

### **Expected Outcome**
- User should be registered and activated successfully.

### **Test Priority:** High  
### **Test Type:** Functional  

---

## 📌 **Test Case 3: Password Reset Functionality**

**Test Case ID:** TC-003  
**Title:** Validate Password Reset via Email  
**Description:** Ensure users can reset their password through email.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Navigate to login page | - | Login page is displayed |
| 2 | Click 'Forgot Password' | - | Redirected to reset page |
| 3 | Enter registered email | valid@example.com | Password reset email sent |
| 4 | Open email and reset password | - | Password successfully changed |

### **Expected Outcome**
- User should be able to reset password successfully.

### **Test Priority:** High  
### **Test Type:** Functional, Security  

---

## 📌 **Test Case 4: Adding Items to Shopping Cart**

**Test Case ID:** TC-004  
**Title:** Validate Adding Items to Cart  
**Description:** Ensure users can add items to their cart.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Search for an item | "Laptop" | Relevant products appear |
| 2 | Click 'Add to Cart' | - | Item is added to cart |
| 3 | Check cart page | - | Item is displayed in cart |

### **Expected Outcome**
- Items should be added to cart and displayed properly.

### **Test Priority:** High  
### **Test Type:** Functional, UI  

---

## 📌 **Test Case 5: Checkout Process**

**Test Case ID:** TC-005  
**Title:** Validate Successful Checkout  
**Description:** Ensure users can complete a purchase.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Add items to cart | Product selected | Item appears in cart |
| 2 | Click 'Checkout' | - | Redirected to checkout page |
| 3 | Enter shipping details | Address, Payment Info | Valid details accepted |
| 4 | Confirm order | - | Order is successfully placed |

### **Expected Outcome**
- Users should be able to complete a purchase successfully.

### **Test Priority:** High  
### **Test Type:** Functional, UI  

---

## 📌 **Test Case 6: Logout Functionality**

**Test Case ID:** TC-006  
**Title:** Validate User Logout  
**Description:** Ensure users can log out of their accounts properly.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Log in to account | Valid credentials | User is logged in |
| 2 | Click 'Logout' button | - | User is logged out |
| 3 | Try accessing dashboard | - | Redirected to login page |

### **Expected Outcome**
- Users should be logged out securely.

### **Test Priority:** Medium  
### **Test Type:** Functional, Security  

---

## 📌 **Test Case 7: Responsive Design Test**

**Test Case ID:** TC-007  
**Title:** Validate Mobile Responsiveness  
**Description:** Ensure the website adapts properly to different screen sizes.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open site on mobile device | iOS/Android | UI adjusts correctly |
| 2 | Navigate through pages | - | No layout issues |
| 3 | Check interactive elements | Buttons, Forms | Clicks work as expected |

### **Expected Outcome**
- Website should be fully responsive.

### **Test Priority:** Medium  
### **Test Type:** UI  

---

## 📌 **Test Case 8: Payment Gateway Validation**

**Test Case ID:** TC-008  
**Title:** Validate Payment Processing  
**Description:** Ensure secure and successful payment transactions.

### **Test Steps**
| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Proceed to checkout | Items in cart | Redirected to payment page |
| 2 | Enter valid payment details | Credit card info | Payment is processed |
| 3 | Verify transaction status | - | Confirmation received |

### **Expected Outcome**
- Payment should be processed securely.

### **Test Priority:** High  
### **Test Type:** Functional, Security  
