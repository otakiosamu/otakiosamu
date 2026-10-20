# Osamu Otaki | Aspiring Backend Engineer

Hi! I'm Osamu, an aspiring backend developer based in Japan. After 14 years in public-sector infrastructure project management, I studied English and web development in Cebu, Philippines. I'm looking for opportunities to build real-world software as a backend engineer.

## Tech Stack
- **Backend:** PHP, Laravel
- **Database:** MySQL / MariaDB
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Tools:** Git, GitHub, VS Code

## Featured Team Project — KKEnglish
**English School Reservation System | Three-person team | 2026**

[View KKEnglish source repository](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline)

An English lesson booking system supporting students, teachers, and administrators. The team built scheduling, reservations, point transactions, lesson records, and related administrative functions.

**My area of responsibility:** student- and teacher-side backend development, including reservation workflows, availability/business rules, point consumption/refunds, and lesson record handling.

### Selected features and code
| Area | What it does | Source |
| --- | --- | --- |
| Reservation workflows | Handles student lesson bookings and reservation logic | [Student ReservationController](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline/blob/master/app/Http/Controllers/Student/ReservationController.php) |
| Double-booking prevention | Validates scheduling conflicts as part of the reservation workflow | [Relevant commit](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline/commit/25ddfd73395a5c620d659709483abf6a00e8536e) |
| Point transactions | Manages point-related business logic for reservations | [PointService](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline/blob/master/app/Services/PointService.php) |
| Teacher-side lessons | Handles teacher reservation-related actions | [Teacher ReservationController](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline/blob/master/app/Http/Controllers/Teacher/ReservationController.php) |
| Data relationships | Connects reservations with point transaction history | [Reservation model](https://github.com/kredo-school/25th_Batch_KKEnglish_Offline/blob/master/app/Models/Reservation.php) |

### What I learned
- Translating business requirements into controllers, services, models, and database relationships
- Considering booking conflicts and consistency between reservation and point records
- Collaborating on a shared codebase using Git and GitHub
- Explaining development decisions and demonstrating the completed system in English

> **Team project note:** KKEnglish was developed collaboratively. The linked repository contains the team's collective work; the sections above describe my primary responsibilities, not sole authorship of the entire system.

## Career Goal
**First:** Gain professional experience writing, reviewing, testing, and maintaining backend code.

**Long term:** Combine technical expertise with my background in coordination and project management to contribute to system design and technical project leadership.

---
**日本語でのご連絡も歓迎します。** / Open to backend engineering opportunities in Japan.
