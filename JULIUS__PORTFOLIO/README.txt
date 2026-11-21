MY PORTFOLIO WEBSITE — COMPUTER SCIENCE STUDENT

FILES
- index.html: website content and structure
- style.css: colors, layout, responsive design, and illustration styles
- script.js: mobile menu, current year, and active navigation
- assets/: optional folder for your own images

HOW TO RUN
1. Extract the ZIP file.
2. Open the cs_student_portfolio folder in Visual Studio Code.
3. Open index.html in a browser by double-clicking it.
   Optional: install the Live Server extension in VS Code, then right-click
   index.html and choose "Open with Live Server".

PERSONALIZE BEFORE PUBLISHING
- Replace "Your Name" in index.html with your name.
- Replace "Your School / University" with your school.
- Replace your.email@example.com and github.com/yourusername with your links.
- Update the sample projects and skills to match your actual experience.
- The hero profile is a CSS illustration, so no photo file is required.
  To use your own photo, place it in assets/ and replace the avatar-art div
  in index.html with:
  <img class="real-profile-photo" src="assets/profile.jpg" alt="Your Name">
  Then add this CSS:
  .real-profile-photo { width: 100%; height: 100%; object-fit: cover; border-radius: 50%; }

NOTES
- Google Fonts is used for the Inter typeface when internet access is available.
- The contact links are examples. The email link opens the visitor's email app;
  this static website does not send or store form submissions.
- The resume button currently points to the Contact section. Replace its href
  with a PDF path when you have a resume file.
