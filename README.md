# FoodForward – Digital Food Donation Matching System 

FoodForward is a full-stack web application designed to reduce food waste by efficiently connecting donors with recipients (e.g., NGOs, food banks, individuals in need). The system enables donation listings, intelligent recipient matching, real-time booking, and review-based feedback.

🛠️ Built with: Java • Spring Boot • MySQL •ReactJS • GCP • JDBC <br>
📊 Features advanced SQL procedures, triggers, and a matching algorithm for efficient distribution. 

## 🔍 Features
🧑‍💼 **Donor** Functionality <br>
- Create, update, and manage food listings with item details and pickup time
- View donation history and booking status
- Receive recipient reviews and ratings for feedback
  
🧑‍🤝‍🧑 **Recipient** Functionality<br>
- Search listings using filters (food type, location, expiry)
- View personalized donor recommendations
- Book food listings and leave reviews post-donation

---

## 💡 Creative Components <br>
1) *Pair Matching Algorithm*: Matches recipients to donors based on proximity, food type, and availability
2) *Review & Rating System*: Builds trust and ranks donors

## 🗃️ Database Architecture
Pre-computed matches stored in Recommendations table. Complex stored procedures and triggers handle booking workflows and validation. Integrated indexing and optimization for scalable query performance. For Detailed architecture, please refer the documentation.


---


## 📦 Technologies Used
| **Category**           | **Tools / Frameworks**                                   |
|------------------------|----------------------------------------------------------|
| Frontend               | ReactJS                                                  |
| Backend                | Spring Boot                                              |
| Database               | MySQL, datagrip, Stored Procedures, Triggers, Views      |
| Cloud Hosting          | Google Cloud Platform (GCP)                              |
| Collaboration & Tools  | Git, GitHub, Lucidchart (ERD), Google Docs,figma         |

🎨 Click here [Figma UI Mockups](https://www.figma.com/design/2AhkN4Ovsx88BsdG6vEbyD/Food-Donation-Matching?node-id=0-1&t=KAeXTQLaaxAl9X15-1) to see visual design of the FoodForward interface.


---


📁 Project Structure (Key Directories)
```
├── src/                         # Backend Java Code
├── static/                      # Frontend HTML/CSS/JS
├── sql/                         # SQL Schema, Triggers, Procedures
├── doc/                         # Project reports, ERD, design documents
└── README.md                    # You're here!
```


### 👥 Team Members
Omkar Dhekane | Sai Prakash Gorti | Nikunj Agarwal | Sai Krishna Rohith Kattamuri

### 📜 License
This project was developed as part of UIUC CS411 Fall 2024. For educational use only.




