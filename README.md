# Retail Pricing & Catalog Engine

## Project Overview
This is a **Spring Boot-based backend application** that simulates a real-world retail pricing system.  
It calculates product pricing dynamically using **GST, discount rules, and promotional logic**, similar to enterprise systems used in large retail companies.

---

## 🚀 Key Features

- ✅ Dynamic Pricing API (`/price?amount=2000`)
- ✅ 18% GST Calculation
- ✅ Smart Discount Engine:
  - Flat ₹100 discount (above ₹1000)
  - Flat ₹200 discount (above ₹2000)
- ✅ RESTful API Architecture
- ✅ Clean and scalable backend structure
- ✅ Business rule-based pricing system

---

## 🛠️ Tech Stack

- **Backend:** Java 21, Spring Boot  
- **Architecture:** REST APIs  
- **Tools:** Git, GitHub, Postman  
- **Optional:** MySQL  

---

## 📡 API Endpoints

### 🔹 Get Price
```
GET /price?amount=2000
```

### Sample Response
```json
{
  "basePrice": 2000,
  "gstRate": 18,
  "gstAmount": 360,
  "offerApplied": "Flat Rs.100 Discount",
  "finalPrice": 2260
}
```

---

## AI Usage

This project was developed with the help of:
- ChatGPT (for logic building & debugging)
- GitHub Copilot (for code assistance)

---

## How to Run

1. Clone the repository  
2. Open in IntelliJ IDEA  
3. Run `PricingEngineApplication.java`  
4. Open browser:

```
http://localhost:8080/price?amount=2000
```

---

## Real-World Use Case

This project simulates **retail pricing engines used in enterprise systems**, where:
- Product prices are calculated dynamically  
- Discounts and promotions are applied  
- APIs serve pricing data to frontend systems  

---

## Author

**Vijay R**  
Backend Developer | Java | Spring Boot | Full Stack Developer | AI Enthusiast  

---
