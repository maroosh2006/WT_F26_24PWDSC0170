# CS 224L Web Technologies Portfolio

A responsive portfolio and HTML lab exercise collection by **Maroosh Ishfaq**, a Data Science student in the Department of Computer Science at the University of Engineering & Technology, Peshawar. Prepared for CS 224L Web Technologies, taught by Mr. Mohammad, Lecturer.

## Pages

- `index.html` — portfolio landing page and links to the exercises
- `profile.html` — personal profile, portrait, and course details
- `schedule.html` — sample weekly schedule table with a merged lunch break
- `navigation.html` — semantic navigation, internal anchors, and UET link
- `registration.html` — sample student registration form
- `contact.html` — contact form with browser-side validation
- `404.html` — custom not-found page

Shared presentation and form validation live in `styles.css` and `script.js`. The portrait is in `assets/profile.png`.

## Run locally

Open `index.html` in a browser. The schedule is sample content and should be replaced with the student's official timetable. Contact details have not been published because no verified address was provided.

The registration form is a front-end exercise and does not store submissions. The contact form validates required fields in the browser but does not deliver messages until it is connected to Formspree, Netlify Forms, or another service with a configured endpoint.

## GitHub Pages deployment notes

1. Commit and push the repository contents to the `main` branch.
2. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Wait for the Pages build to finish; the published URL is shown in **Settings → Pages**.
4. Visit the published URL and check the landing page, all exercise links, the image, and the custom `404.html` page.
5. Capture a screenshot of the published page after it loads successfully.

The repository root contains the GitHub Pages landing page so it can be selected as the Pages source folder.
