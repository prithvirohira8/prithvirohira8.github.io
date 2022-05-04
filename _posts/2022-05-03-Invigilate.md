# Invigilate
A web application to proctor students for online examinations.

![Home Page](https://github.com/prithvirohira8/prithvirohira8.github.io/blob/main/_posts/images/invigilate/home-page.png?raw=true "Home Page")

### About
- The application allows organizations (schools and colleges) to conduct their examinations on the platform using google forms.
- The platform proctors the students during the examination and informs the organization if any malpractices like tab switching, exiting full screen mode were performed during the test by the student.
- Face verification is carried out to verify the users.

### Why Invigilate?
- The pandemic in the last few years has shifted the mode of education from offline to online.
- Universities have subscribed/purchased proctoring applications which works accurately but is expensive
- Most schools in India use google forms as the examination portal for conducting online exams because they cannot affored proctoring applications
- Invigilate is a proctoring application that allows schools to continue to use google forms as the question paper with the integration of a proctoring application providing a cost efficient and easy to use solution.

### Demonstration

#### Organization Sign-up
- Organizations (Schools Colleges need to create their accounts from the home page as shown below)

### Tech Stacks used
- Tech Stack used: React JS, Node JS, Python and Firebase.

### How to clone the repository
- There are 2 servers. 
- The react server is set up for authentication and the dashboard of both teachers and students. On this server teachers can schedule exams on their dashboard and on the students dashboard students can enter the test code provided by the teachers and register for the tests.
- The node server is where the examination takes place and face verification takes place. (Face detection takes place every 5 seconds. If the user switches tabs the teacher will be informed on her dashboard.)

The master branch consists of the react server code which will run on localhost:3000.
The nodeServer branch consists of the node server code which will run on localhost:4000.

Clone and start both the servers before using the application.

