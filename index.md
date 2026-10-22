Here is the complete solution for Assignment 3.3 — Ordered, Unordered & Nested Lists, packaged as a clean, structured HTML file named college-info.html.

The college-info.html Code
Save the following code as college-info.html in your project folder:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College & Course Information</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>State Institute of Technology</h1>
        <p>Welcome to the official course portal. Explore our departments, admission steps, curriculum details, and faculty directory below.</p>
    </header>

    <hr>

    <!-- Departments Section (Unordered List) -->
    <section>
        <h2>Departments Offered</h2>
        <p>Our institute offers world-class education across multiple disciplines:</p>
        <ul>
            <li>Computer Science & Engineering</li>
            <li>Electronics & Communication</li>
            <li>Mechanical Engineering</li>
            <li>Business Administration</li>
        </ul>
    </section>

    <hr>

    <!-- Admission Process Section (Ordered List) -->
    <section>
        <h2>Admission Process</h2>
        <p>Follow these steps to apply for our undergraduate and postgraduate programs:</p>
        <ol>
            <li>Submit the online application form via our admissions portal.</li>
            <li>Upload academic transcripts and required identification documents.</li>
            <li>Appear for the entrance examination or interview round.</li>
            <li>Receive your acceptance letter and complete fee payment.</li>
        </ol>
    </section>

    <hr>

    <!-- Course Curriculum Section (Nested List) -->
    <section>
        <h2>B.Sc. Computer Science Curriculum</h2>
        <p>Here is an overview of the core subjects and their corresponding topics:</p>
        <ul>
            <li>
                <strong>Web Development</strong>
                <ul>
                    <li>HTML5 Semantic Tags & Attributes</li>
                    <li>CSS Layouts & Flexbox</li>
                    <li>JavaScript Basics & DOM Manipulation</li>
                </ul>
            </li>
            <li>
                <strong>Data Structures & Algorithms</strong>
                <ul>
                    <li>Arrays and Linked Lists</li>
                    <li>Stacks and Queues</li>
                    <li>Sorting and Searching Algorithms</li>
                </ul>
            </li>
        </ul>
    </section>

    <hr>

    <!-- Faculty Details Section (Description List) -->
    <section>
        <h2>Faculty Directory</h2>
        <p>Meet our distinguished professors and course instructors:</p>
        <dl>
            <dt><strong>Dr. Alan Turing</strong></dt>
            <dd>Professor of Computer Science — Specializes in algorithms and artificial intelligence.</dd>

            <dt><strong>Prof. Ada Lovelace</strong></dt>
            <dd>Associate Professor of Software Engineering — Specializes in web technologies and systems design.</dd>
        </dl>
    </section>

</body>
</html>
Key Requirements Checklist Met:
File Name: Saved as college-info.html.

Unordered List (<ul>): Used for listing departments.

Ordered List (<ol>): Used for outlining the step-by-step admission process.

Nested Lists: Used inside the curriculum section to break down subject topics.

Description Lists (<dl>, <dt>, <dd>): Used to display faculty names and their details.

Semantic Structure: Organized neatly using <header>, <section>, and appropriate heading tags (<h1>, <h2>).

Submission Requirements
HTML File: Submit your college-info.html file.

Browser Screenshot: Open college-info.html in your web browser, take a screenshot displaying the lists and sections, and submit it along with your file!