# Hospital Management System Prototype

**Course / Group:** Group #3  
**Group Members:** Francis Charles Mbayo 22396/2023, Thomas Yorwartie 22067/2023, Edward Cole 25260/2024  
**Figma Prototype Link:** https://hospitalmanagement.figma.site
## 1. Project Overview

This project is a responsive **Hospital Management System prototype** built for a UI/UX assignment. It demonstrates how a hospital can digitize patient appointment booking, doctor access, medical records, notifications, settings, and administrative management using a clean blue/green/white healthcare interface.

The current prototype includes three main user flows:

- **Patient portal** — login/register, dashboard, doctor list, appointment booking, confirmation, profile/records, notifications, and settings.
- **Doctor portal** — doctor login, appointments, assigned patients, and doctor profile.
- **Admin portal** — live dashboard, doctor approval/rejection, patient records, appointments, and hospital settings.

## 2. Problem Statement

Many hospitals still rely on manual patient files, physical appointment books, and in-person queue management. This can lead to long waiting times, lost or duplicated records, poor visibility of doctor availability, and weak coordination between patients, doctors, hospital staff, and administrators.

The target users are **patients, doctors, hospital staff, and administrators**. Patients need to book appointments quickly and access their records. Doctors need to view appointments and patient information. Administrators need to approve doctors, manage patients, monitor appointments, and update hospital settings.

The system matters because it improves healthcare efficiency, accessibility, communication, and record accuracy. A digital flow reduces waiting time, keeps information organized, and gives each user role a clear interface for their responsibilities.

## 3. Primary User Persona

| Field | Details |
|---|---|
| Name | Francis Charles Mbayo |
| Age | 20 |
| Email | mbayocharles26@gmail.com |
| Patient ID | RW-2026-420 |
| Goals | Book appointments quickly, view medical records, receive updates, and manage profile settings |
| Frustrations | Long queues, unclear doctor availability, slow record access, and repeated paperwork |
| Needs | Mobile-friendly booking flow, clear confirmations, secure records, notifications, and accessible navigation |

## 4. Demo Login Credentials

### Patient

| Field | Value |
|---|---|
| Email | mbayocharles26@gmail.com |
| Password | francis2026 |

### Doctor

| Field | Value |
|---|---|
| Email | Doctor@#26@gmail.com |
| Password | Doctor2026 |

### Admin

| Field | Value |
|---|---|
| Email | mbayocharles26@gmail.com |
| Password | ADMIN2026 |

## 5. User Flow

### Patient Flow

```text
Login/Register → Dashboard → Doctor List → Appointment Booking → Confirmation → Profile/Records
```

Additional patient screens:

```text
Dashboard → Notifications
Dashboard → Settings
```

### Doctor Flow

```text
Doctor Login → Doctor Dashboard → Appointments → Patients → Profile
```

Doctor registration flow:

```text
Register → Select Doctor Role → Add License/Specialty/Hospital/Experience → Submit → Admin Approval → Doctor Login
```

### Admin Flow

```text
Admin Login → Admin Dashboard → Doctor Management → Patients → Appointments → Settings
```

## 6. Wireframes

Low-fidelity wireframe exports are stored in `/wireframes`.

Included wireframes:

- `login-register-wireframe.svg`
- `dashboard-wireframe.svg`
- `doctor-list-booking-wireframe.svg`
- `service-list-booking-wireframe.svg`
- `patient-profile-records-wireframe.svg`

## 7. High-Fidelity UI Design

High-fidelity screen exports are stored in `/high-fidelity-designs`.

Included high-fidelity screens:

- `login.svg`
- `dashboard.svg`
- `doctor-list.svg`
- `service-list.svg`
- `appointment-booking.svg`
- `appointment-confirmation.svg`
- `patient-profile.svg`

The design uses a hospital-themed color palette:

- **Blue** for trust, professionalism, and primary actions.
- **Green** for health, success states, and confirmation feedback.
- **White/light surfaces** for readability and clean medical UI presentation.

## 8. Interactive Prototype

The interactive prototype is available through the Figma link above and is also represented in the React implementation.

Prototype interactions include:

- Patient login to dashboard.
- Patient booking from doctor list to confirmation.
- Appointment editing/booking interactions.
- Profile, notifications, and settings navigation.
- Doctor login and doctor dashboard flow.
- Admin login and doctor approval/rejection flow.
- Smooth transitions, responsive navigation, and mobile bottom tabs.

Prototype support files:

- `/prototype/user-flow-diagram.svg`
- `/prototype/figma-prototype-link.md`

## 9. Accessibility Considerations

The prototype includes:

- Readable font sizes, generally 16px or larger for body content.
- High-contrast text and buttons.
- Clear navigation labels and consistent icon usage.
- Touch-friendly mobile controls and bottom navigation.
- Responsive layouts for mobile, tablet, and desktop screens.
- Consistent button styles and visual feedback for actions.
- Dark mode support for improved viewing comfort.

## 10. Technology Used

- React
- TypeScript
- Tailwind CSS
- Lucide React icons
- Motion animations
- Recharts for admin dashboard charts

## 11. Repository Structure

```text
/
├── assets/
├── docs/
│   └── report.md
├── high-fidelity-designs/
│   ├── appointment-booking.svg
│   ├── appointment-confirmation.svg
│   ├── dashboard.svg
│   ├── doctor-list.svg
│   ├── login.svg
│   ├── patient-profile.svg
│   └── service-list.svg
├── prototype/
│   ├── figma-prototype-link.md
│   └── user-flow-diagram.svg
├── src/
│   ├── app/
│   │   └── App.tsx
│   └── styles/
│       ├── fonts.css
│       └── theme.css
├── wireframes/
│   ├── dashboard-wireframe.svg
│   ├── doctor-list-booking-wireframe.svg
│   ├── login-register-wireframe.svg
│   ├── patient-profile-records-wireframe.svg
│   └── service-list-booking-wireframe.svg
└── README.md
```

## 12. How to Run / Review

1. Open the project in the development environment.
2. Run the app using the available React/Vite command for the workspace.
3. Use the demo credentials above to test patient, doctor, and admin flows.
4. Open the Figma link to review the design/prototype deliverable.
5. Review `/docs/report.md` for the written design report.

## 13. Conclusion

The Hospital Management System prototype demonstrates a complete digital healthcare workflow across patient, doctor, and admin roles. It supports appointment booking, records access, doctor approval, admin monitoring, and responsive mobile-friendly usage while meeting the core UI/UX assignment deliverables.
