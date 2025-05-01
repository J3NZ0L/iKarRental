# iKarRental
Simple car rental page project, with server-side logic using PHP.

---

### Current features:
- [x] Home Page: all cars and their basic data are listed
- [x] Home Page: clicking on a car’s card/name navigates to the corresponding car’s detail page
- [x] Car Page: the car’s data and image are displayed
- [x] Home Page: filtering works successfully – except for available time slots
- [x] Admin: a new car can be created with error handling, and is saved successfully if the data is valid
- [x] Authentication: Registration works with error handling
- [x] Authentication: Login works with error handling
- [x] Authentication: After successful login, it is visible across the pages that the user is logged in
- [x] Logout: Available on the profile page and all other pages

---

### Future tasks:
- [ ] Car Page: The selected car can be booked between two time points, and upon successful booking, the reservation is saved.
- [ ] Car Page: Upon successful or failed booking, the user is notified. In the case of success, the reservation and car details are displayed.
- [ ] Home Page: It is possible to filter by available time slots on the homepage.
- [ ] Profile Page: The user's previous bookings are displayed.
- [ ] Admin: When the admin is logged in, all bookings are displayed on their profile page, and these bookings can be deleted.
- [ ] Admin: Modification of car data (with error handling).
- [ ] Admin: Deletion of cars.

---

### Extra tasks:
- [ ] Car Booking: For a given car, only available time slots can be selected for booking — for example, visualized in a calendar view.
- [ ] Use of AJAX: After booking, the saving and feedback are handled using AJAX — instead of redirecting to a new page, a custom popup (not an alert!) provides feedback without refreshing the page.
