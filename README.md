A student-led innovation project
Transmit
=========================
A centralised repository for University of Edinburgh lectures slides

-----

### Overview
Transmit is a centralised university platform that provides a set of tools enriching the way students experience lectures and the way professors deliver them. Transmit is envisioned to be a main point of reference for hosting lecture slides and presentations. 

Technology innovation permeates countless aspects of our education experience. However, university lectures, which are a significant part of a university student’s learning experience, have gradually become a more and more outdated and largely obsolete way for students to learn.

Lecture slides often do not have a standardised way of being distributed to students, nor do instructors have a reliable way to access them in lectures theatres (corrupted USB drives, and unawareness of cloud storage have created, in our experience, huge obstacles for successful lecture delivery).

Transmit is not limited to hosting lectures slides, but will provide a modern and intuitive interface for students to follow and annotate concepts during the lecture. Presentations hosted on Transmit’s web application will be seamlessly broadcasted live to all devices who are connected to that particular lecture channel, and students will be able to follow the progression of the lecture instantaneously on their devices (laptops, tablets, etc). They will also be able to annotate the slides through Transmit’s integrated annotation tools, which they will be able to access and review after the lecture ends. Instructors will also have the option to record audio of their lectures through the platform and the recording will be deeply integrated to the lecture slides, so students will be able to listen once more to difficult concepts explained in lecture.

We believe that having a centralised proprietary platform allows us to cater the development of Transmit to the needs of the University community, for example when providing seamless integration with the university system (EASE). This provides a much more efficient and functional solution than a third-party web application which requires to be installed and setup for all courses. Also,  third-party virtual learning environments like *Learn* often restrict the availability of learning resources to the general public. Transmit is committed to provide access to these resources in a straightforward way, granted that the instructor provides permission. This follows the University Open Access policies and would make Transmit a great repository for multidisciplinary learning resources.
We do believe Transmit is the missing piece in establishing a more dynamic and interactive experience for students and instructors.

### Milestones and timeframe
1. **Start of project development** (1 Jun 2016): Laying out a plan,  capturing requirements, evaluating stakeholder inputs, technology and database design choices and start of development.
2. **First working prototype** (1 Jul 2016):  A prototype with limited features available and unpolished design.
3. **Project development ends** (1-10 Aug 2016): Fully developed web application with all requirements met and polished design.
4. **Project integration** (1-10 Aug 2016): Setting up the project on servers and integrating it with the existing university infrastructure. Reaching out to potential lecturers who might have an interest in piloting it.
5. **End of project** (10 Aug 2016)

### Technology stack
The technology stack for Transmit has not been finalised yet.
Here are different options that are being considered:

Technology    | Pros          | Cons
------------- | ------------- | -------------
Meteor + Blaze    | Reactivity, previous experience    | long-term support of the platform, scalability
Meteor + React    | Reactivity, previous experience (to a certain extent), opportunity to learn React    | same as before + initial React learning curve
Ruby on Rails| Previous experience, straightforward university integration with infrastructure| no native support for reactivity
Django/Flask| ... | ...
Laravel | ... | ...


### Project requirements
1. The system shall act as a centralised storage of lecture slide.
	- University courses shall be preloaded in the platform.
	- Instructors of each course shall be able to add new material that will be made available to enrolled students, as well as manage the uploaded content.
	- The system shall be able to support different types of materials, specifically common document formats for lecture presentations and decks (e.g .ppt, .pptx, .pdf, etc.)
	- The system shall incorporate a document viewer for students to visualise the material directly on the browser.
- The system shall allow instructors to specify the visibility permission of their uploaded material (public, university-wide, enrolled students).
	- The platform shall comply with University Open Access policies
- The system shall provide modern and intuitive interface for students to follow and annotate concepts during the lecture.
	- The system shall allow live broadcasting to all devices who are connected to that particular lecture channel.
	- Students shall be able to follow the progression of the lecture instantaneously on their devices (laptops, tablets, etc).
	- The system shall provide annotation tools to students following the lecture slides. These can include a text editor for text notes and basic formatting tools (e.g. highlighter)
	- Students shall be able to access their annotations at home after the lecture.
- The system design shall be responsive.
	- The design shall easily adapt to devices of different sizes (e.g. desktop, tablets and smartphones)
	- The design shall build on Bootstrap's front-end components.
	- The design shall conform to university branding guidelines.
	- The design shall be modern and elegant.
- The system shall integrate with EASE, which will act as the platform’s exclusive authentication system.
- The system shall be durable and sustainable.
	- The system shall have at least 3 year life span with further development.
	- The system shall be compatible with modern technologies
	- The system shall work on all University supported browsers.
	- The system shall have a backup copy for quick restoration in case of a loss of golden copy.
- The system shall include a tool for analytics of usage and event tracking (e.g. Google Analytics)
	- The analytics tool shall provide meaningful information for load testing.
- The system shall meet the University accessibility policy - comply with the AA standard of the Web Content Accessibility Guidelines (WCAG) 2.0.
- The system shall include an integrated feedback mechanism to get immediate feedback from users.

### Team overview
We are Martin and Giovanni and we lead Transmit's development. We are students in the School of Informatics and have a passion for developing solutions that have an impact within the University community.

Last summer we had the great opportunity to work with the University’s Student Systems department to actively shape the University community and improve the way students like us experience learning. We laid down a proposal for Ask, a centralised online platform and collaborative environment for students to ask and answer academic questions, get help and share ideas. Ask was selected by the Student Systems office as a winner of the university-wide student-led innovation competition. With their investment, we lead its development over the summer at their offices in Old College, with their support and supervision. Student Systems are considering a pilot of the platform in 2016/17. The prototype of Ask is available on <dev.ask.sli.is.ed.ac.uk> (you have to be on University network to access the page).

Last semester we worked part-time on a project with the Library Digital Development Team, part of Library and University Collections, Information Services. The Library Mapping project helps users locate books and services with the Main Library by integrating DiscoverEd search results with a web application showing the location of items within the Library. An item’s shelving bay will be pinpointed on an interactive map. The application will also highlight facilities within the Library on maps e.g. printing, study spaces, toilets, and computers for study.