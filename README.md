# DantanHospital Website

A multi-page hospital website built with plain **HTML** and **CSS**. It shows the hospital's services, doctors, patient reviews, and has login and sign-up pages. The design is clean and light, with blue and yellow colors, rounded cards, and a layout that works on computers, tablets and phones.

> Status: front-end only. The forms look and validate correctly, but they do not send data anywhere yet.

---

## Pages

| Page | File | What it shows |
|------|------|---------------|
| Home | `Home.html` | Hero with "Modern Medicine. Caring People.", key numbers, services, why choose us, how it works, opening hours, FAQ |
| About Us | `About.html` | Hospital story, mission, vision, values, journey, departments, opening hours |
| Services | `Service.html` | Services offered, how it works, what you get, opening hours, FAQ |
| Doctors | `doctor.html` | Medical team cards, departments, how to book a doctor |
| Appointment | `appointment.html` | Appointment booking page (planned) |
| Reviews | `review.html` | Patient review cards, rating breakdown, form to share an experience |
| Login | `login.html` | Login form with remember me and forgot password link |
| Sign Up | `signup.html` | Account form with name, email, phone and password |

Every page shares the same menu at the top and the same footer at the bottom.

---

## Features

- Sticky menu that stays at the top while scrolling
- Hero section with a background photo and rounded corners
- Cards with hover effects
- FAQ that opens and closes without JavaScript (`<details>` tag)
- Review cards, rating bars and a review form
- Login and sign-up forms with built-in checks (required fields, email format, minimum password length)
- Responsive design for desktop, tablet and phone, with no sideways scrolling

---

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, media queries)
- Google Font: Poppins (falls back to Arial when offline)

No frameworks and no JavaScript are needed.

---

## Folder structure

```
DantanHospital/
├── Home.html
├── Home.css
├── About.html
├── about.css
├── Service.html
├── services.css
├── doctor.html
├── doctor.css
├── review.html
├── review.css
├── login.html
├── login.css
├── signup.html
├── auth.css
├── Doctor.jpg       (hero background photo)
└── doctor.png       (doctor photo with transparent background)
```

Each page has its own CSS file. `auth.css` styles the Sign Up page, and `login.css` styles the Login page.

> The file names in the menu links must match your real file names exactly, including capital letters. For example, `Service.html` is not the same as `service.html`.

---

## How to run

**Option 1: open the file**

1. Download or copy the whole folder.
2. Double-click `Home.html` to open it in your browser.

**Option 2: Live Server (VS Code)**

1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `Home.html` and choose **Open with Live Server**.
4. The page opens at `http://127.0.0.1:5500/Home.html` and refreshes when you save.

---

## How to customize

**Colors.** The main colors are used in every CSS file:

| Color | Code | Used for |
|-------|------|----------|
| Page background | `#f1f9fc` | Behind all pages |
| Blue | `#1a9bd7` | Sign Up button, links, card headings |
| Steel blue | `#6894c2` | Hero and side panels |
| Yellow | `#f5cf47` | Main buttons and highlight bars |
| Dark | `#1a1a1a` | Footer |

Use your editor's find-and-replace to change a color everywhere.

**Text.** Open any `.html` file and change the words between the tags. The review texts, the doctor names, the opening hours and the FAQ answers are examples. Replace them with real information.

**Photos.** Put your own photo in the folder, then change the file name in the CSS:

```css
.hero {
  background: url(Doctor.jpg) center / cover no-repeat;
}
```

**Contact details.** The office address, email and phone number are in the footer of every page.

---

## Known limitations

- The forms (login, sign up, appointment, review) do not save or send data. A back end is needed for that.
- The two passwords on the Sign Up page are not compared with each other.
- The names, reviews, numbers and opening hours are sample text.
- The Appointment page is not built yet.

---

## Future improvements

- Build the Appointment page with a booking form
- Add a back end (for example PHP, Node.js or Python) to save accounts, appointments and reviews
- Add JavaScript to check that both passwords match
- Add real photos of the doctors and the hospital
- Add a map of the hospital location
- Add a Somali language version of the site

---

## Author

Your name here

## License

This project is for learning and personal use.
Abdullahi aadan Hassan
