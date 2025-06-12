# Course Hub - ServiceNow Learning Management System

A comprehensive course subscription application built on the ServiceNow platform, designed to enable learners to browse, subscribe to, and manage educational courses through an intuitive user interface.

## 🎯 Project Overview

Course Hub is a template application developed using ServiceNow's UI Builder framework, providing a modern and responsive interface for course management. The application demonstrates the integration of ServiceNow's backend capabilities with contemporary frontend design patterns.

**Repository:** [https://github.com/FatlumGerguri/coursehubDCM](https://github.com/FatlumGerguri/coursehubDCM)

## 🚀 Features

### ✅ Implemented Features

#### PRD01: Course Listing (COMPLETED)

- **Course Display**: Dynamic listing of available courses with comprehensive details
- **Interactive Cards**: Each course presented in a visually appealing card layout
- **Real-time Data**: Live integration with ServiceNow backend tables
- **Responsive Design**: Optimized for various screen sizes and devices

**Technical Implementation:**

- **Database Table**: `x_quo_coursehub_course`
- **UI Components**: Built with ServiceNow UI Builder
- **Data Integration**: Real-time course data fetching and display

#### Displayed Course Information:

- **Title**: Course name and identifier
- **Description**: Detailed course overview and learning objectives
- **Delivery Mode**: Online, Offline, or Hybrid format indicators
- **Duration**: Comprehensive time commitment details
- **Subscription Action**: Interactive subscription buttons (UI ready)

### 🔄 Planned Features

#### PRD02: Course Subscription (IN DEVELOPMENT)

- **User Registration**: Complete subscription workflow
- **Status Management**: Real-time subscription status updates
- **User Dashboard**: Personalized course management interface
- **Notification System**: Course updates and reminders

_Note: This feature is currently in development due to platform learning curve and technical constraints._

## 🏗️ Architecture

### Technical Stack

- **Platform**: ServiceNow
- **Frontend**: UI Builder with modern components
- **Backend**: ServiceNow tables and business logic
- **Data Layer**: ServiceNow database with custom tables

## 👥 User Experience

### Application Access

1. **Login**: Users authenticate through ServiceNow platform
2. **Navigation**: Access via `/x/quo/qdx-course-hub/home`
3. **Interface**: Clean, intuitive course browsing experience

## 🛠️ Setup and Installation

### Prerequisites

- ServiceNow Personal Developer Instance (PDI)
- Git access and repository permissions
- Basic understanding of ServiceNow UI Builder
- Administrative access to ServiceNow instance

### Installation Process

1. **Clone Repository**

   ```bash
   git clone https://github.com/FatlumGerguri/coursehubDCM
   ```

2. **ServiceNow Integration**

   - Open ServiceNow Studio
   - Import application using Git integration
   - Configure repository connection

3. **Verify Installation**

   - Confirm table imports (`x_quo_coursehub`)
   - Validate data model structure
   - Test data resource connections

4. **Access Application**
   - Navigate to UI Builder
   - Open CourseHub experience
   - Launch Home page to view course listings

### Post-Installation Verification

- [ ] Course list displays correctly
- [ ] All course details render properly
- [ ] Subscription buttons are interactive
- [ ] Responsive design functions across devices

## 📸 Documentation

### Screenshots

All project screenshots are located in the `/screenshots` folder:

1. **`prd01-01-course-list.png`**: Complete course listing interface
2. **`prd01-02-component-layout.png`**: UI Builder component hierarchy
3. **`prd01-03-course-resource.png`**: Data resource configuration setup

### Conclusion

The coursehub project was developed as part of a take-home assigment. Main goals was to build a Course Subsription Application using ServiceNow platform, mostly focusing on user inteface through UI Builder.

I appriciate the opportunity to work on this challens
