# 📱 JobEase Mobile App – Test Automation Suite

Automated testing framework for **JobEase**, a cross-platform (Android/iOS) mobile job search application that enables users to search, bookmark, and apply for jobs. The automation suite covers UI, functional, and API validation across multiple devices and network conditions.

---

## 🚀 Project Overview

- **App Type**: React Native Mobile App (Job Search)
- **Testing Scope**: End-to-end UI + API test automation
- **Platforms**: Android & iOS
- **Automation Framework**: Appium + Java + TestNG
- **CI/CD**: GitHub Actions
- **Cloud Testing**: BrowserStack, Firebase Test Lab

---

## 🎯 Objectives

- Automate key user workflows to reduce manual QA effort
- Ensure cross-device/platform compatibility
- Validate frontend–backend data consistency
- Simulate real-world usage conditions (offline mode, network fluctuations)

---

## 🔧 Tech Stack

| Category         | Tools / Tech Used                            |
|------------------|----------------------------------------------|
| **UI Automation**| Appium, Selenium WebDriver                   |
| **Language**     | Java                                          |
| **Test Framework**| TestNG                                      |
| **API Testing**  | Postman, REST Assured *(optional)*           |
| **CI/CD**        | GitHub Actions                               |
| **Device Testing**| BrowserStack, Firebase Test Lab             |
| **Design Pattern**| Page Object Model (POM)                     |

---

## ✅ Test Coverage

### 🔐 **Authentication Module**
- Sign up & Login (valid/invalid)
- Error handling & input validation

### 🔍 **Search & Filter**
- Keyword-based job search
- Location filter, remote toggle, and experience filters
- Bookmark and save jobs

### 👤 **User Profile**
- View/edit profile details
- Resume upload flow
- Job application tracking

### 🌐 **API Testing**
- Verify job listing APIs (`/jobs`)
- Application submission endpoint (`/apply`)
- Auth and session APIs

### 📱 **Device/Platform Testing**
- Android & iOS (emulated + real devices)
- Cross-device layout and UI consistency

### 🌐 **Network Simulation**
- Offline caching behavior
- Resume sync on reconnect
- Low-bandwidth UI responsiveness

---


