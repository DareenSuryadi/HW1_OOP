# Case Study: UKRIDA SISFO
## Requirement Analysis (FURPS):

**Functionality:**
- **Reusability:** Components like user authentication, data retrieval, and notification services should be designed for reuse across different modules.
- **Security:** User authentication, data encryption, and access control are essential. Sensitive data like student records and grades must be securely managed.

**Usability:**
- **Human Factors:** The interface should be intuitive for all user types, accommodating varied tech proficiency. It should have a responsive design for different devices.
- **Consistency:** The system should maintain a consistent look and feel across all modules and user roles.
- **Documentation:** Comprehensive user guides for each user role, FAQs, and system manuals are necessary.

**Reliability:**
- **Availability:** The system should be available 24/7, with minimal downtime.
- **Failure Rate & Duration:** It should have a low failure rate. Any system failures should be resolved quickly.
- **Predictability:** System behavior in response to user actions should be predictable and consistent.

**Performance:**
- **Speed:** Fast response times for user queries and actions.
- **Efficiency:** Optimized for minimal resource consumption without compromising functionality.
- **Resource Consumption:** Should be optimized to work smoothly on standard institutional hardware.
- **Scalability:** Capable of handling an increasing number of users and data volume.

**Supportability:**
- **Testability:** The system should be easily testable to find and fix bugs.
- **Extensibility:** It should be designed to allow easy updates and additions of new features.
- **Serviceability:** Problems within the system should be easy to diagnose and fix.
- **Configurability:** Allow easy configuration of features like user roles, permissions, and system settings.

## Use Case Stories:

**User Roles (Actors):**
1. **Student (Mahasiswa)**
2. **Professor (Dosen)**
3. **Operator (Tata Usaha)**
4. **Admin (PTI)**

**User Stories (Functionalities):**

**Student:**
- **Enroll Course:** As a student, I want to be able to enroll in courses for the upcoming semester.
- **View Grade:** As a student, I want to view my grades for the courses I am enrolled in.
- **Access Course Material:** As a student, I want to access course materials such as lecture slides, assignments, and reading materials.
- **View Schedule:** As a student, I want to view my class schedule for the semester.
- **Submit Assignments:** As a student, I want to submit assignments electronically through the system.
- **View Financial Information:** As a student, I want to view my financial information such as tuition fees and payment status.

**Professor:**
- **Upload Course Material:** As a professor, I want to upload course materials such as lecture slides, assignments, and readings for my students to access.
- **View Course Members:** As a professor, I want to view the list of students enrolled in my courses.
- **Add Grade:** As a professor, I want to add and update grades for assignments and exams.
- **Communicate with Students:** As a professor, I want to communicate with my students through announcements and messages.
- **View Academic Calendar:** As a professor, I want to view the academic calendar and important dates.

**Operator:**
- **Technical Support:** As an operator, I want to provide technical support to users experiencing issues with the system.
- **Support Dosen:** As an operator, I want to provide support to professors with technical issues or questions.
- **Support Mahasiswa:** As an operator, I want to provide support to students with technical issues or questions.
- **Daily Operation:** As an operator, I want to perform daily operational tasks such as system maintenance and backups.

**Admin:**
- **User Management:** As an admin, I want to manage user accounts, including creating new accounts, updating user information, and deactivating accounts as needed.
- **System Monitoring:** As an admin, I want to monitor system performance, check for errors or issues, and ensure the system is running smoothly.
- **Generate Reports:** As an admin, I want to generate various reports such as enrollment statistics, grade distributions, and system usage metrics.
- **Manage System Settings:** As an admin, I want to configure system settings such as course offerings, academic calendars, and access permissions.

## Use Case Diagram:
![Use Case SISFO.drawio](https://hackmd.io/_uploads/rJ73qYPZA.png)

## Class Diagram:
![Class diagram.drawio (1)](https://hackmd.io/_uploads/S1sYjivbR.png)
