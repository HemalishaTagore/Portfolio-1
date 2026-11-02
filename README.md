# Ex01 Portfolio
## Date: 02/11/2026

## AIM
To create a Portfolio using HTML.

## ALGORITHM

**STEP 1**

Create an HTML file (index.html).

**STEP 2**

Define the basic HTML document structure using HTML tags.

**STEP 3**

Add the portfolio title and metadata inside the head section.

**STEP 4**

Create a heading to display your name and professional introduction.

**STEP 5**

Add an About Me section with personal and educational details.

**STEP 6**

Create a Skills section to display technical skills.

**STEP 7**

Add a Projects section to showcase completed projects.

**STEP 8**

Include educational details and certifications.

**STEP 9**

Add contact information such as email and GitHub profile links.

**STEP 10**

Use HTML headings, paragraphs, lists, images, and hyperlinks to organize the content.

**STEP 11**

Add navigation links to move between different sections of the portfolio.

**STEP 12**

Open the HTML file in a web browser and verify the content and navigation links.

**STEP 13**

Make necessary corrections and ensure all sections are displayed properly.

**STEP 14**

Upload the HTML file and related images to GitHub Pages for free hosting.

## PROGRAM
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <meta
      name="description"
      content="Personal portfolio of Hemalisha Tagore, Computer Science and Engineering student interested in Full-Stack Development, AI, Cloud and DevOps."
    />

    <meta name="author" content="HEMALISHA TAGORE" />

    <title>HEMALISHA T | Personal Portfolio</title>
  </head>

  <body>
    <!-- HEADER SECTION -->

    <header id="top">
      <nav aria-label="Main Navigation">
        <a href="#home">Home</a>  |
        <a href="#skills">Technical Skills</a> |
        <a href="#projects">Projects</a> | 
        <a href="#education">Education</a> |
        <a href="#certifications">Certifications</a> |
        <a href="#contact">Contact</a>
      </nav>

      <hr />
    </header>

    <main>
      <!-- HOME SECTION -->

      <section id="home">
        <div style="text-align: center">
          <h2>Welcome to My Portfolio</h2>

          <figure>
            <img
              src="profile.jpeg"
              alt="Hemalisha Tagore Profile Picture"
              width="200"
              height="200"
            />
          </figure>

          <p>Hello! This is <strong>HEMALISHA TAGORE</strong></p>

          <p>
            <strong>Computer Science and Engineering Student</strong>
          </p>

          <p>
            <em>
              Aspiring Full-Stack Development | Exploring AI, Cloud and DevOps
            </em>
          </p>

          <p>
            Passionate about Full-Stack Development and DevOps, with an interest
            in building scalable applications and exploring AI technologies.
            Currently strengthening my programming fundamentals, learning system
            design, and solving Data Structures and Algorithms (DSA) problems.
          </p>

          <p>
            <a href="#contact">Contact Me</a>
          </p>
        </div>
      </section>

      <hr />

      <!-- SKILLS SECTION -->

      <section id="skills">
        <h2>Technical Skills and Learning Areas</h2>

        <h3>Programming Languages</h3>

        <ul>
          <li>Java</li>
          <li>Python</li>
          <li>C</li>
          <li>C++</li>
        </ul>

        <h3>Frontend Development</h3>

        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>React (Learning)</li>
        </ul>

        <h3>Graphic Designing</h3>

        <h3>Databases</h3>

        <ul>
          <li>SQL</li>
          <li>MongoDB (Learning)</li>
        </ul>

        <h3>Cloud and Developer Tools</h3>

        <ul>
          <li>Amazon Web Services (AWS)</li>
          <li>Git</li>
          <li>GitHub</li>
        </ul>
      </section>

      <hr />

      <!-- PROJECTS SECTION -->

      <section id="projects">
        <h2>My Projects</h2>

        <!-- PAYPILOT -->

        <div class="project">
          <h3><b>PayPilot <em>(In Progress)</em></b></h3>

          <p>
            A smart SaaS platform designed to help freelancers and small
            businesses manage payments and automate payment reminders through
            Email and WhatsApp.
          </p>

          <p>
            <strong>Tech Stack:</strong>
            React | TypeScript | Tailwind CSS | Node.js | Express.js | MongoDB
          </p>
        </div>
        <hr>

        <!-- NOVAFORGE -->

        <div class="project">
          <h3><b>NovaForge</b></h3>

          <p>
            An AI-powered cloud IDE designed to provide developers with an
            intelligent coding environment and a seamless development
            experience.
          </p>
          <p>
            <strong>Tech Stack:</strong>
            React | TypeScript | Tailwind CSS | Node.js | Express.js | MongoDB |
            Zustand | Axios
          </p>
        </div>
        <hr>

        <!-- STUDYSPACE -->

        <div class="project">
          <h3><b>StudySpace</b></h3>

          <p>
            A student productivity dashboard that helps students organize tasks,
            track progress, and manage their academic activities efficiently.
          </p>

          <p>
            <strong>Tech Stack:</strong>
            HTML | CSS | JavaScript | React | Node.js | Express.js | MongoDB
          </p>
        </div>
      </section>

      <hr />

      <!-- EDUCATION SECTION -->

      <section id="education">
        <h2>Education</h2>

        <table border="1" cellpadding="6" cellspacing="0">
          <caption>
            Academic Details
          </caption>

          <thead>
            <tr>
              <th scope="col">Field</th>
              <th scope="col">Details</th>
            </tr>
          </thead>

          <tbody>
            <tr>
              <th scope="row">Institution</th>
              <td>Saveetha Engineering College</td>
            </tr>

            <tr>
              <th scope="row">Department</th>
              <td>Computer Science and Engineering (CSE)</td>
            </tr>

            <tr>
              <th scope="row">Current Year</th>
              <td>Second Year</td>
            </tr>

            <tr>
              <th scope="row">Expected Graduation</th>
              <td>2029</td>
            </tr>

            <tr>
              <th scope="row">Location</th>
              <td>Chennai, Tamil Nadu, India</td>
            </tr>
          </tbody>
        </table>
      </section>

      <hr />

      <!-- CERTIFICATIONS SECTION -->

      <section id="certifications">
        <h2>Certifications and Professional Learning</h2>

        <ol>
          <li>
            <strong>AWS Certified Cloud Practitioner</strong>
          </li>

          <li>
            <strong>OpenAI Prompt Engineering Certificate</strong>
          </li>

          <li>
            <strong>Microsoft Generative AI Certificate</strong>
          </li>

          <li>
            <strong>
              IBM DevOps and Software Engineering Professional Certificate
            </strong>
            <em>(In Progress)</em>
          </li>
        </ol>
      </section>

      <hr />

      <!-- CONTACT SECTION -->

      <section id="contact">
        <h2>Contact Me</h2>

        <p>
          Feel free to contact me about internship opportunities, project
          collaboration, or technical discussions.
        </p>

        <ul>
          <li>
            <strong>Email:</strong>

            <a href="mailto:hemalishatagore07@gmail.com">
              hemalishatagore07@gmail.com
            </a>
          </li>

          <li>
            <strong>GitHub:</strong>

            <a
              href="https://github.com/HemalishaTagore"
              target="_blank"
              rel="noopener noreferrer"
            >https://github.com/HemalishaTagore
            </a>
          </li>

          <li>
            <strong>LinkedIn:</strong>

            <a
              href="https://linkedin.com/in/hemalisha-tagore-7a88bb390/"
              target="_blank"
              rel="noopener noreferrer"
            >https://linkedin.com/in/hemalisha-tagore-7a88bb390/
              
            </a>
          </li>
        </ul>
      </section>
    </main>

    <hr />

    <!-- FOOTER SECTION -->

    <footer>
      <div style="text-align: center">
        <p>&copy; 2026 HEMALISHA TAGORE. All Rights Reserved.</p>

        <p>
          <a href="#top">Back to Top &uarr;</a>
        </p>
      </div>
    </footer>
  </body>
</html>

```
## OUTPUT

![alt text](<Screenshot (162).png>)
![alt text](<Screenshot (163).png>)
![alt text](<Screenshot (164).png>)
![alt text](<Screenshot (165).png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
