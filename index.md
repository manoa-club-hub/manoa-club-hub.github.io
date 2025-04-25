<div class="container">
  <h1 id="project-club-hub">Project: Manoa Club Hub</h1>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/manoa-club-hub-logo.png" alt="Manoa Club Hub Logo" style="width: 50%;">
  </div>
  


  <h2>Table of Contents</h2>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#team">Development Team</a></li>
    <li><a href="#approach">Approach</a></li>
    <li><a href="#guide">User Guide</a></li>
    <li><a href="#dev-guide">Developer Guide</a></li>
    <li><a href="#history">Development History</a></li>
    <li><a href="#feedback">Community Feedback</a></li>
    <li><a href="#quality-assurance">Quality Assurance</a></li>
    <li><a href="#enhancements">Possible Enhancements</a></li>
  </ul>

  <h2 id="overview">Overview<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#overview" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p><em>The problem:</em> Many UH students who want to take part in active organizations at UH Manoa sometimes don't know where to look for them as there's no easy way to find clubs, registered or unregistered and how to get involved</p>

  <p><em>The solution:</em>  The Club Hub application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), and contact information for officers.</p>

  <h2 id="team">Development Team<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#team" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <b>
  Dominic Deuz <br>
  </b>
  <hr>

  <a href="/img/Musicians%20of%20Manoa%20-%20Team%20Contract.pdf"><b>Team Contract</b></a>
  <br>
  <a href="/img/Musicians%20of%20Manoa%20-%20Team%20Bonding.pdf"><b>Team Bonding</b></a>
  <br>
  <a href="https://github.com/musicians-of-manoa"><b>Github Organization</b></a>

  <h2 id="approach">Approach<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#approach" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>Once a profile is created, others can browse the profiles filtered by their interests or by name.</p>

  <p>Students can reach out to certain organizations and their officers in order to help get involved via providing the contact information.</p>

  <p>Admins can monitor the site for any misinformation or change in information, and create new pages for any new organizations that may come up.</p>


  <h2 id="guide">Website Guide<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#guide" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <h3>Landing Page</h3>
  <p>The landing page is presented to users when they first go to the top-level URL of the site. This page presents basic information about the project and buttons that will take them to other commonly used pages.</p>
  

  <h3>Sign In/Sign Up</h3>
  <p>Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" if you already have an account created, if not you can create an account by clicking "Sign up" instead.</p>
  
  
  <p>The "Sign up" page allows the user to customize their profile by providing attributes such as what kind of clubs they are interested in.</p>
  

  <h3>View/Edit Profile Page</h3>
  <p>Click on the "View/Edit Profile" button in the upper right corner of the navbar after logging in, User can see their own Profile page and can edit their information.</p>
  

  <h3>Search Page</h3>
  <p>There is also a "Search" link in the navbar. Hitting this link will take you to the Search page, where you can search for other clubs or organizations</p>

  
<h3>Admin Dashboard Page</h3>
  <p>By clicking on the "Admin" tab in the navbar, Admins have the ability to edit any change in information for an organization and see all signed in users.</p>

  
  <h2 id="dev-guide">Developer Guide<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#dev-guide" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>This section provides information of interest to Next developers wishing to use this code as a basis for their own development tasks.</p>

  <h3>Deployment</h3>
  <p>You can find a live deployment of the website at this link <a  href="https://manoa-club-hub.vercel.app/">https://manoa-club-hub.vercel.app</a>.</p>

  <h3>Installation</h3>
  First, make sure you have <a href="https://nodejs.org/en">Node</a> installed.
  <br>
  Second, visit the <a href="https://github.com/manoa-club-hub/manoa-club-hub">Manoa Club Hub</a> GitHub page, and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.
  <br>
  Third, after having installed your local copy of the application, cd into the musicians-of-manoa directory with a command terminal and install libraries with:
  <br>
  <code>$ npm install</code>
  <br>
  Fourth, run the system with: 
  <br>
  <code>$ npm run dev</code>

  If everything was successful, you will be able to view the application at <a href="http://localhost:3000">http://localhost:3000</a>

  <h2 id="history">Development History<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#history" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
  <p>The development process for the Musicians of Manoa project conformed to <a href="https://courses.ics.hawaii.edu/ics314f24/morea/project-management/reading-guidelines-idpm.html">Issue Driven Project Management</a> practices. These practices include:</p>

  <ul>
    <!--
    <li><b>Frequent Meetings:</b> Teams should meet at least twice a week to review progress and update tasks, with face-to-face meetings preferred for better coordination.</li>
    -->
    <li><b>Task Decomposition:</b> Work should be divided into small tasks taking approximately 72 hours to complete. Longer tasks must be broken into subtasks.</li>
    <li><b>Task Documentation and Ownership:</b> Each task is documented as a GitHub issue with a single owner responsible for its completion. Collaboration is possible, but accountability remains with the designated owner.</li>
    <li><b>Branch-based Task Execution:</b> Each task is associated with its own branch, named using the issue number ("issue-XX"), to reduce conflicts and ensure clear tracking. Completed branches are merged back into the main branch.</li>
    <li><b>Milestone Organization:</b> Tasks are grouped into milestones spanning 7-10 days, each producing a concrete deliverable. Each GitHub issue is assigned to exactly one milestone.</li>
    <li><b>Active Issues Per Member:</b> There should be at least two active issues in the current milestone to ensure steady progress and task availability.</li>
    <li><b>Progress Tracking via GitHub Projects:</b> A GitHub Project board with columns for ToDo, In Progress, and Done is created for each milestone to manage tasks visually and systematically.</li>
    <li><b>Effort Estimation:</b> Effort is estimated in hours for each issue, based on task complexity, dependencies, and resources. Estimates are refined as experience grows.</li>
  </ul>

  <p>The following sections document the development history of Manoa Club Hub</p>
  <h3>Milestone 2</h3>
  <p>The goal of Milestone 2 was to create as many mockup pages as possible of the necessary pages for our project, the group deciding building the pages using Nextjs from the start to be the easiest approach.<p>
  <p>Milestone 1 was managed using <a href="https://github.com/orgs/musicians-of-manoa/projects/1">Musicians of Manoa Project Board M1</a></p>

  <!--
  <h3>Milestone 3</h3>
  <p>The goal of Milestone 3 is to refine the database connections and clean up the overall UI. <p>
  <p>Milestone 3 was managed using <a href="https://github.com/orgs/musicians-of-manoa/projects/5">Musicians of Manoa Project Board M3</a></p>
  <div style="display: flex; justify-content: space-around;">
    <img src="/img/M3Board.png" alt="M3 Project Board">
  </div>
  -->


<h2 id="quality-assurance">Quality Assurance<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#quality-assurance" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>
<h3>ESLint</h3>
<p>Musicians of Manoa includes a <a href="https://github.com/bowfolios/bowfolios/blob/main/app/.eslintrc">.eslintrc</a> file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:</p>

<code>npm run lint</code>

<p>Here is sample output indicating that no ESLint errors were detected:</p>


> PS E:\ICS314\musicians-of-manoa> npm run lint
> 
> \> nextjs-application-template-1@0.1.0 lint
>
> \> next lint
> 
> =============
>
> WARNING: You are currently running a version of TypeScript which is not officially supported by @typescript-eslint/typescript-estree.
> 
> You may find that it works just fine, or you may not.
> 
> SUPPORTED TYPESCRIPT VERSIONS: >=4.7.4 <5.6.0
> 
> YOUR TYPESCRIPT VERSION: 5.6.3
> 
> Please only submit bug reports when using the officially supported version.
> 
> =============
> ✔ No ESLint warnings or errors

<p>
ESLint should run without generating any errors.

It's significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).
</p>

<h3>End to End Testing</h3>

<p>
Musicians of Manoa uses <a href="https://playwright.dev/">Playwright</a> to provide automated end-to-end testing.
<br>
To run the end-to-end tests in development mode, you must first start up a Musicians of Manoa instance by invoking `npm run dev` in one console window.
Then, in another console window, start up the end-to-end tests with:
</p>
<code>npm playwright test</code>

<p>
If the tests finish successfully, you should see the following in your second console window:
</p>

> PS E:\ICS314\musicians-of-manoa> npx playwright test                    
> 
> Running 6 tests using 6 workers
>  6 passed (8.4s)
> 
> To open last HTML report run:
> 
> npx playwright show-report

  <!--
  <h2 id="enhancements">Possible Enhancements<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="" href="#enhancements" style="font: 1em / 1 anchorjs-icons; margin-left: 0.1875em; padding-right: 0.1875em; padding-left: 0.1875em;"></a></h2>

  <p>Here are ideas for more advanced features:</p>

  <ul>
    <li>Support the organization of jam sessions. Provide information on scheduled jam sessions, including location, time, musical type, desired capabilities, and organizer contact information.</li>
    <li>Support a network of “who’s played with who”.</li>
    <li>Support reviews of musicians.</li>
  </ul>
  -->
