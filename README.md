# Jeevashwan Suraksha – Stray Dog Monitoring and Public Safety Portal

Welcome to the **Jeevashwan Suraksha** GitHub repository! This project is a comprehensive web-based application designed to address growing community concerns regarding stray dog incidents, public safety, and animal welfare management[cite: 2].

---

## 🚀 Project Overview

Stray dog overpopulation and related incidents pose significant challenges to urban safety and animal welfare. The **Jeevashwan Suraksha** portal provides a centralized platform that bridges the gap between citizens, municipal authorities, and animal welfare organizations (NGOs)[cite: 2]. 

By integrating **real-time incident reporting**, **interactive geographic mapping**, and **data analytics**, the system empowers stakeholders to track, analyze, and manage stray dog populations and bite cases efficiently while promoting humane animal treatment[cite: 2].

---

## 🛠️ Main System Modules

The platform is role-based, ensuring dedicated workflows for different types of users:

1. **Admin Module**
   - **System Management:** Oversees overall application operations and user accounts.
   - **Incident Management:** Views, manages, and assigns reported cases to relevant NGOs[cite: 2].
   - **Records Management:** Updates and tracks vaccination and sterilization metrics[cite: 2].
   - **Hotspot Monitoring:** Monitors high-risk concentration zones and aggressive behavior areas[cite: 2].
   - **NGO Verification:** Approves or rejects newly registered NGOs[cite: 2].
   - **Analytics:** Generates comprehensive operational and analytical reports[cite: 2].

2. **User Module**
   - **Authentication:** Secure user registration and login[cite: 2].
   - **Incident Reporting:** Report stray dog concentrations, aggressive behavior, or dog bite cases[cite: 2].
   - **Media & Location Upload:** Attach real-time images and precise geographical location details[cite: 2].
   - **Complaint Tracking:** Monitor the live status of submitted reports[cite: 2].
   - **Public Safety:** Access designated hotspot zones and safety guidelines[cite: 2].

3. **NGO Module**
   - **Case Management:** View and accept assigned rescue or intervention cases[cite: 2].
   - **Activity Updates:** Log and update rescue operations, vaccination programs, and sterilization statuses[cite: 2].
   - **Coordination:** Coordinate seamlessly with municipal authorities and maintain comprehensive animal welfare logs[cite: 2].

---

## 💻 Tech Stack

- **Backend:** Java, Spring Boot, Apache Maven[cite: 2]
- **Frontend:** HTML5, CSS3, JavaScript (Responsive dashboards)[cite: 2]
- **Database & Mapping:** Relational Database management with interactive spatial mapping tools (GeoJSON integrations)[cite: 2]

---

## 📂 Project Structure

```text
jeevashwan-surakhsh/
│
├── .github/                 # Workflows and modernizations
├── apache-maven-3.9.6/      # Build tool binaries and configurations
├── src/
│   └── main/
│       ├── java/            # Spring Boot backend application code
│       └── resources/
│           ├── static/      # Frontend HTML, CSS, JavaScript, and mapping assets
│           └── application.properties # App configuration settings
├── pom.xml                  # Maven project object model configuration
└── README.md                # Project documentation
