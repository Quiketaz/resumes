AI-Powered Resume Portfolio
This project is a simple, elegant portfolio to showcase multiple resumes. It's built with HTML and Tailwind CSS, and uses the Gemini API to provide AI-powered features for improving resume content on the fly.

Features
Scalable Portfolio: Easily add multiple resumes to the main landing page, each in its own organized folder.

AI-Enhanced Content: Use the Gemini API to automatically rewrite and improve profile summaries and job descriptions.

Clean & Modern Design: A professional, two-column resume layout that's easy to read and print-friendly.

Fully Responsive: Looks great on desktop, tablet, and mobile devices.

How to Add a New Resume
Create a new folder: Inside the resumes/ directory, create a new folder. Name it appropriately (e.g., john-doe).

Create the index.html file: Copy the index.html file from another resume folder (e.g., from resumes/yaremi-flores-sotelo/) and place it inside your new folder.

Update the content: Open the new index.html file and replace the personal information, experience, skills, and education with the new resume's details.

Link to it from the main page: Open the root index.html file (the main portfolio page) and add a new list item (<li>) to the <ul> section, following the existing format. Make sure the href attribute points to your new folder.

<li>
    <a href="resumes/john-doe/index.html" class="flex ...">
        <div>
            <h3 class="text-xl font-semibold text-teal-700">John Doe</h3>
            <p class="text-gray-600">Software Developer</p>
        </div>
        <span class="text-teal-500 font-bold text-lg">&rarr;</span>
    </a>
</li>

Done! Your new resume will now appear on the portfolio's main page.

File Structure
.
├── index.html          # The main portfolio landing page
├── resumes/
│   └── yaremi-flores-sotelo/
│       └── index.html  # The first resume
└── README.md           # This file
