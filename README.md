# Live Sound Compound

user ui experience:
user goes to website, navigates pages, becomes interested, looks at social media, looks at photos, looks at photos of the studio,
end goal - user contacts LSC for more info, and/or books studio time. The booking form allows the user to select a package(example - 1hr $150, 2hr $250, 5hr $450); time, and date(fom available slots), and submitt a booking request.

admin ui experience:
The admin will recieve email notifications when a user requests a booking. The admin will then goto the web ui, login and be able to see requested bookings, and scheduled bookings. The admin will be able to contact the user to clear details and confirn the booking, and collect payment. When a booking is confirmed it will be moved into the scheduled bookings(making those slots no longer available). The admin will also be able to directly schedule a booking without the user needing to use the booking form.

features required:

- home page
- contact page
- booking page
- authentication
- a backend to store the users private data
- user booking form
- admin ui
  - login
  - add, edit, delete, approve booking interface

recommended features:

- studio page - this is like an about or bio page - with a detailed description and pictures of the studio.
- news page
  - this is a blog essentially
  - will automatically post to social media sites like -> facebook pages, twitter, tumblr.
  - here you will post articles, sales or promotions.
- photos page
  - this is a photo gallery
  - will automatically post photos to social media sites like -> instagram, twitter, and facebook pages.
- contact page - phone, address, social media sites, contact form, and link to booking page.

---

navigation example:

LSC ---------- STUDIO - BOOK - NEWS - PHOTOS - CONTACT

---

extended features

- integrated payment
  - as the booking becomes steady, we implement cc payment in the booking.
  - when a user calls to get information, the admin can goto the site see if the time slot is available, and direct the user to the web page to book and pay directly themselves, with no need for an admin to approve if a payment was made.
  - this relieves the admin from dealing with payments, and approving requests if a payment was made directly by the user through the web site.
  - if the user does not pay at the time of booking, the admin will contact the user to collect payment, and then schedule the booking request.
