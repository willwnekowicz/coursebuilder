This is not Google's course-builder and I haven't updated the source code here for quite some time now.

Google's course-builder project is http://code.google.com/p/course-builder/

The features of our current system is different, user documentation can be seen here
http://flexiblelearning.auckland.ac.nz/coursebuilder_support/

---

# CONTEXT  OF Coursebuilder #
CourseBuilder(CB), online software for teachers (with no computer coding skills) to create educational websites, has been developed in the Centre for Academic Development’s Elearning Group at the University of Auckland by WenChen Hol, with interface expertise contributed by Craig Housley. Teachers can use the software collaboratively. .  We are probably all familiar with working to find technical and pedagogical solutions that address teaching and learning needs in the online environment.  CB aims to make these technical solutions available to the teachers (and students, more recently) to promote sustainability and build capacity by encouraging independence.  Users work in an editing environment.  When they publish, the edit link url is replaced with the published link.
CourseBuilder is designed to work with tools like Learning Management systems (eg Cecil or Moodle), peer assessment software (Peerwise, Aropā), social networking software (eg elgg, wikis, blogs) or hand-coded customisations of the Elearning Group’s Content Management System.

Primarily, CB supports credit-bearing courses delivered through the UoA learning management system (Cecil), but staff also use it to develop sites supporting workshops, student projects, international collaborations, and central services. These may serve audiences beyond the university like schools, professionals and the community. Currently we have about 500 active sites (according to Google analytics) and over 1000 site instances (the extra sites being backups, templates, surveys, prototypes, trials etc.)
MOTIVATION for Coursebuilder development and support

CB aims to provide   effective learning experiences and to encourage continued improvements arising from teaching/learning requirements and users’ developing experience and expertise.  Traditional resource-intensive one-off web development processes led to issues with sustainability and scalability in a tertiary education context.  We needed an easy-to-use tool to empower people, build capacity, allow rapid prototyping and encourage good design.  There was also a need to provide flexible delivery for students; either in different LMS’s (CECIL/Moodle), on CD’s, or as standalone websites.

## Recent Coursebuilder INNOVATIONS ##
### Embedding ###
CB uses 'embedding' to make it easier to get the whole picture of a topic, to provide a seamless ‘book’ experience while incorporating features only available online, i.e. watching videos, presentations, doing course reading, practice questions, saving notes/journal entries/files, communication/comments/social networking/chat, all in the same space).  Its features enable you to embed designs with up to three levels of nested elements  You can embed various elements together (eg a page could contain an unlimited amount of. elements. In this way, you can easily develop pages that look concise but also contain very rich information.  You can embed subjects/information as required, using plug-ins from the rich text editor (eg tooltips,  the hide-show feature) and elements (eg image hotspots,).  This encourages cohesiveness and enables you to deliver sub-topics or important notes in context.
Most web applications use a modular approach.  Each module has its own control logic and scripts and does not support nesting of other modules within their control.  This allows the teaching ?community to contribute and grow hugely, but has the drawback that each page can contain only limited functions. For example,  a discussion page is only for discussion, a journal page is only for journals. Using the  ‘book’ metaphor what we see mostly is mixed designs of different functions. Many times a page/activity may require various functions together to fit the purpose. Like composing music, a musician may need to connect different notes together instead of one note at a time. Our 'embedding' designs allow such creativity.

### Reuse, capacity building and the power of cloning ###
CB allows you to easily reuse successful course designs, quality icons, styles, questions, pages or topics. This is especially important to promote wider use of the good websites that designers, developers and lecturers have built up over the years. It also  enables teachers to  improve and update their  design and content autonomously in response to student feedback, teaching requirements or emerging trends.
CB’s ability to replicate or ‘clone’ pages or entire sites is particularly powerful as it addresses the challenges of  time-consuming, resource intensive one-off web development processes. It enables a more sustainable approach to course design and delivery. CourseBuilder courses can be easily maintained, frequently updated and cloned for future use. It has the “modularity and plasticity” [1](1.md) that allows segmented changes without significant time and cost implications. This ‘rapid prototyping’ ability makes it popular with academics/teachers/learning designers interested in developing a website in a comparatively short period of time, with increasing independence.
This not only saves time, it also allows users to build on successful designs based on sound pedagogy to deliver material for their courses on similar principles; teachers who have only a vague idea of  what they want to do can benefit from being able to customise an existing template developed by other educators, to suit their needs. Over the years the growth in the number of high quality courses utilising CourseBuilder has supported this capacity-building concept. We often we see student feedback; people are asking for “more”.
Support has been scaled up to support the growing number of users: People interested in using CourseBuilder are directed to a user support website, Coursebuilder workshops or a project request form.  Users can also email the coursebuilder team with technical queries. ‘Alerts’  provide information on changes within CourseBuilder.

### The xml template-driven approach ###
The CB developers have found this approach to be the easiest way to adopt new designs or customisations to meet practical needs. There is  no database (add/delete/update/retrieve/update table schema etc.) coding during the development process.  This straight line approach (xml->form->output template->test) makes for quick development in each phrase. WenChen Hol, the CB developer says,  “I can quickly provide emerging designs for our academics; in the past it could be as early as the next day, more recently, in about a week from the original request. The CSS course map, audio image slideshow with sound track, YouTube play list, typing text, cross browser text drop shadow, sifr fonts and Google web fonts; various designs for a container (text/quiz/media/inline comment...) highlights, stylish quote element, image magnifier/gallery/slideshow, voice recorder, all are proof of the ease of using the xml-template-driven approach.”  However, you can have too much of a good thing.  Six years ago users could choose from 80 elements in CB’s selection list. CB has reduced the number of readily available elements to enhance usability and robustness.

### Media plugins ###
Media plugins are important CB ingredients. They allow you to add media in the same way as you would add a link, so that an image or text becomes a "click to play media button" (especially useful for language learning or media-rich courses or ebooks).  The plugins also enable you to author media rich questions, with question/survey editors allowing rich formats within questions, choices, feedback and even auto play audio/media for feedback on multiple choice questions.  You can drag around popup media/YouTube/Google video windows. This provides a good learning experience for easy study and question answering.  The plugs ins also allow in-context media and instruction with tooltips etc. CB also includes an image plugin with drop shadow and decoration designs inspired by various world leading designers.

## PEDAGOGICAL BENEFITS OF THESE INNOVATIONS ##
Inline comment/social networking (facebook comment, Yammer group) widgets allow students to share their thoughts, interact, and network within the learning context.
The hide/show plugin allows you to add interactivity almost anywhere in the content or navigation pane. Being able to click an image to hide or show information helps you author rich format and flexible questions. Students can use ‘sticky notes’ that use html5 local storage then cross browser for group notes or personal study notes. The ‘Student journal/note summary’ element allows students to save their notes/findings/files in context. This element could also be used for short answer/multiple choice questions enabling learners to see all their previous writing/choices from any computer, even beyond semester - a better learning experience than scattered attachments and paper/notes here and there;

Contextualising information is made easy via a sophisticated, media-rich image hotspot editor, or a tooltip embedded for text, link or media popup. CB supports css hover image to display a big image for extra information.  The Tinymce 3rd party 'tooltip' plugin enables these features. In 6 years WenChen still hasn’t found another richtext editor that provides such a plugin.

embedded web resource’ element allows easy embedding of resources like cd-rom media, articulate, ispring, and various presentation packages. It also enables developers to build and embed special designs; this is a way of allowing users to free flow their creativity with functions outside our scope.
The latex math equation/drop capital/pull quote/goTop/iframe plugins are all useful in an educational context, as are drag and drop and fill in the blank questions. The glossary can be accessed as a list as well as an auto glossary replacement with tooltip.

## IMPLICATIONS FOR FUTURE PRACTICE ##
CB enables staff to develop websites that meet their needs and has recently added elements to enable contributing student pedagogy.  It does this through the use of various widgets, plugins and elements.

CourseBuilder allows epublishing export for existing sites; it utilises the full ebook  concept for a seamless learning experience, bringing media, social and interactive elements into the learning space.

CB has the potential to contribute to the power of  Open education resource(OER) by enabling excellent courses to be cloned and customized for different institutions or translation into different languages;, question banks on a topic could be pooled from various sources; successful learning and course design could be easily reused and saving time and scaling up the quantity and  quality of other projects;

CB is easy to improve to align current designs with emerging web trends ( html5 and css3 ) and accommodate teaching practice and learning experience.


Some showcase sites:
http://www.clear.auckland.ac.nz/index.php?p=elearning_showcase