# Invigilate
A proctoring web application for online examinations.

- Tech Stack used: React JS, Node JS, Python and Firebase.
- The application allows organizations (schools and colleges) to conduct their examinations on the platform using google forms.
- The platform proctors the students during the examination and informs the organization if any malpractices like tab switching, exiting full screen mode were performed during the test by the student.
- Face verification is carried out to verify the users.

### How to clone the repo
- There are 2 servers. 
- The react server is set up for authentication and the dashboard of both teachers and students. On this server teachers can schedule exams on their dashboard and on the students dashboard students can enter the test code provided by the teachers and register for the tests.
- The node server is where the examination takes place and face verification takes place. (Face detection takes place every 5 seconds. If the user switches tabs the teacher will be informed on her dashboard.)

The master branch consists of the react server code which will run on localhost:3000.
The nodeServer branch consists of the node server code which will run on localhost:4000.

Clone and start both the servers before using the application.

