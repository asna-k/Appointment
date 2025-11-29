✅Online Appointment Booking System:

The Online Appointment Booking System is a user-friendly, multi-page web application designed to help users easily book and manage appointments. The system is implemented using HTML, CSS, and JavaScript, and it uses localStorage to transfer data between pages.

The project follows a four-step navigation flow, allowing the user to enter their appointment details, verify the information, confirm the booking, and optionally reschedule the appointment.

👉 🔹 Page 1: Appointment Booking (appointment1.html)

This is the first page of the system where the user enters the following details:

1. Name

2. Appointment Date

3. Appointment Time

4. Purpose of Appointment

Once the user fills out the form and clicks Next, all the entered details are stored in localStorage.
The user is then redirected to the verification page.

👉 🔹 Page 2: Verification Page (appointment2.html)

This page displays all the information that the user entered earlier.
The user must check a confirmation checkbox to verify that all the details are correct.

1. If verified, the user clicks Confirm

2. The system redirects to the Confirmation Page

This step ensures that users double-check their details before final submission.

👉 🔹 Page 3: Confirmation Page (appointment3.html)

This page displays the message:

“Your appointment is successfully booked!”

Along with this, all the stored appointment details are displayed again for reference.
The user also gets two options:

1. Reschedule → Goes to Page 4

2. Exit → Ends the process

👉 🔹 Page 4: Reschedule Appointment (Optional) (appointment4.html)

If the user chooses to reschedule, they are taken to a page where they can update:

1. Date

2. Time

After updating, the new details are saved back to localStorage, and the user can reconfirm the updated appointment.

👉 output:

<img width="1615" height="827" alt="Screenshot 2025-11-29 185352" src="https://github.com/user-attachments/assets/4a97ab8a-c661-40c1-980f-ba91fa3a96d7" />

