# 🧺 Laundry Wallah 2.0

### Tutedude Assignment – 4

## 📌 Project Overview

**Laundry Wallah 2.0** is a fully functional laundry services web application built using **HTML, CSS, and JavaScript**.

The application allows users to:

* Explore available laundry services
* Add or remove services from the cart
* View total pricing dynamically
* Book appointments
* Receive order confirmation via **EmailJS**
* Subscribe to newsletters

The project focuses on creating a seamless and user-friendly experience while implementing real-world web development concepts.

---

## 🚀 Features

### 🔹 Responsive Navigation Bar

* Logo on the left
* Navigation links:

  * Home
  * Services
  * About Us
  * Contact Us
* User name displayed on the right

---

### 🔹 Hero Section

* Attractive heading and description
* “Book a Service Today” button
* Smooth scroll to booking section
* Laundry-themed image

---

### 🔹 Service Overview Section

Displays achievements:

* ✅ 15+ Laundry Services
* ✅ 240+ Happy Customers
* ✅ 2+ Years of Experience

---

### 🔹 Booking Services Section

#### Left Section

* List of available services
* Price for each service
* "Add Item" button
* "Remove" button
* Cart instructions

#### Right Section

* Dynamic cart display
* Real-time total calculation
* Booking form:

  * Full Name
  * Email
  * Phone Number
* "Book Now" button
* Confirmation message display

---

### 🔹 Email Confirmation (EmailJS Integration)

When the user clicks **Book Now**:

* Order details are sent via EmailJS
* Confirmation message appears:

> “Thank you For Booking the Service We will get back to you soon!”

---

### 🔹 Quality Description Section

Highlights service strengths:

* Premium Services
* Quick Support
* Timely Delivery
* Affordable Prices

---

### 🔹 Newsletter Subscription Section

* Full Name input
* Email input
* Subscribe button
* Encourages user engagement and updates

---

### 🔹 Footer

Includes:

* Brand logo
* About Us link
* Important links
* Contact Us link
* Social media reference
* Positioned at the bottom for accessibility

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* EmailJS API
* Flexbox Layout
* Smooth Scrolling

---

## 📂 Project Structure

```
Laundry-Wallah-2.0/
│
├── index.html
└── README.md
```

---

## 💻 How to Run the Project

1. Download or clone the repository.
2. Open `index.html` in a web browser.
3. Add services to cart.
4. Fill booking details.
5. Click **Book Now** to send email confirmation.

---

## 📧 EmailJS Configuration

The project uses:

* **Service ID:** service_zntqcue
* **Template ID:** template_8oullcq
* **Public Key:** Configured in script

Make sure your EmailJS template contains:

```
{{name}}
{{email}}
{{phone}}
{{order}}
{{total}}
```

---

## 🎯 Learning Objectives

* DOM manipulation
* Dynamic cart logic
* Real-time total calculation
* Smooth scroll navigation
* API integration using EmailJS
* Form validation
* UI structuring and layout design

---

## 🌟 Future Improvements

* Payment gateway integration
* Admin dashboard
* Database integration
* Backend using Node.js
* Authentication system
* Order history tracking

---

## 👨‍💻 Author

**Aaryan Kumar**
Computer Science & Engineering Student

