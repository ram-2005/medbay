
# Software Requirements Specification (SRS)

# Smart Medication Dispenser

---

# 1. Introduction

The Smart Medication Dispenser is an IoT-enabled healthcare system designed to improve medication adherence through automated reminders, secure dispensing, and remote monitoring. The system combines embedded hardware, cloud services, and a web application to assist patients in following prescribed medication schedules while allowing caregivers to monitor adherence remotely. There is no medication dispenser that are designed for the disabled

The project aims to provide a low-cost, modular, and scalable solution that can be deployed in homes, clinics, and elderly care facilities.

---

# 2. Problem Statement

Medication non-adherence is a significant healthcare challenge that can lead to treatment failure, disease progression, and avoidable hospitalizations. Existing pill organizers rely heavily on user memory and do not provide intelligent reminders, monitoring, or remote accessibility.

There is a need for an affordable smart system that automates reminders, securely controls medication dispensing, and enables caregivers to track medication adherence in real time.

---

# 3. Objectives

The primary objectives of this project are:

* Develop an IoT-enabled medication dispenser.
* Automate medication reminders based on predefined schedules.
* Provide visual and audio notifications.
* Enable secure dispensing using an electronically controlled mechanism.
* Allow caregivers to monitor medication adherence remotely.
* Maintain medication schedules using cloud storage.
* Design a modular hardware system that supports future enhancements.
* Create a System that will asist the people from the start to finish of the medication adherence process

---

# 4. Stakeholders

## Primary Stakeholders

* Patients
* Elderly users
* Individuals with chronic illnesses
* Individuals with Disability 

## Secondary Stakeholders

* Family members
* Caregivers
* Doctors
* Pharmacists
* Healthcare organizations

## Development Team

* Software Developers
* Embedded Systems Engineers
* UI/UX Designers
* Project Maintainers

---

# 5. Scope

## Included

* Medication scheduling
* Automated reminders
* ESP32-based controller
* Servo-controlled dispensing gate
* LED and speaker alerts
* Web dashboard
* Firebase backend
* User authentication
* Wi-Fi connectivity
* Medication history

## Excluded (Current Version)

* Automatic pill identification
* Computer vision
* AI diagnosis
* Robotic dispensing mechanisms
* Electronic health record integration
* Medical prescription validation

---

# 6. Functional Requirements

The system shall:

* Allow users to register and log in securely.
* Store medication schedules.
* Notify users at scheduled times.
* Activate LED indicators during reminders.
* Play audio alerts through the speaker.
* Open the dispensing gate upon authorization.
* Record medication events.
* Synchronize data with the cloud.
* Allow caregivers to monitor medication status.
* Operate in offline mode and synchronize when connectivity is restored.

---

# 7. Non-Functional Requirements

## Performance

* Reminder delay shall not exceed 2 seconds.
* Dashboard response time shall remain under 3 seconds.

## Reliability

* The system shall recover after power interruptions.
* Medication schedules shall persist after restart.

## Security

* User authentication shall be required.
* Communication shall be encrypted.
* User data shall be protected from unauthorized access.

## Scalability

* Support multiple users.
* Support additional medication compartments.
* Allow future integration with healthcare APIs.

## Usability

* Simple and intuitive interface.
* Easy medication schedule management.
* Accessible for elderly users.

---

# 8. Constraints

* Internet connectivity is required for cloud synchronization.
* Limited by ESP32 hardware resources.
* Battery backup is not included in the initial version.
* The first prototype supports only a simple servo-operated dispensing gate.
* Firebase free-tier limitations may restrict scaling.
* Prototype designed primarily for demonstration and research purposes.

---

# 9. Assumptions

The project assumes that:

* Wi-Fi is available during synchronization.
* Medication compartments are filled correctly.
* The ESP32 remains powered during operation.
* The dispensing mechanism is properly maintained.
* Caregivers have access to the monitoring dashboard.

---

# 10. Future Scope

Future enhancements include:

* Voice-guided medication instructions.
* AI-powered medication assistant.
* Missed dose prediction.
* SMS and WhatsApp notifications.
* Integration with healthcare providers.
* Electronic prescription support.
* Smart refill reminders.
* Computer vision-based medication verification.
* Multi-user and family account support.
* Analytics dashboard for medication adherence.
* Emergency alert system for missed critical medications.
