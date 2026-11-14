# Open Course Space – Converted to Docsify-This

> The three example courses from the [Grav Open Course Space skeleton](https://github.com/hibbitts-design/grav-skeleton-open-course-space), converted to plain Markdown pages for [Docsify-This](https://docsify-this.net/#/) by the [Open Publishing Course Space Converter](https://open-publishing-course-space-converter.hibbittsdesign.org).

View it as a website: https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-open-course-space-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&pagination=true&searchbox=true&name=Open%20Course%20Space

These pages are the converter's output as it is, shown like the courses in Open Course Space: the home page is the Courses page, with a card for each course, and each course is in a folder of its own, laid out like the [Docsify Open Course Starter Kit](https://github.com/hibbitts-design/docsify-open-course-starter-kit). A course's home page starts with its header image and name, a module's page with its title and header image, the sidebar starts with the course's name (a link back to its home page) and lists its modules (or weeks) and LMS links, the navbar has its course pages and a link back to All Courses, and Previous/Next buttons follow the modules in order.

The original courses are built with Grav Open Course Space at https://demo.hibbittsdesign.org/grav-open-course-space – this version uses the same content (CPT363-2 and CPT363-3 were switched on for the conversion):

- `home.md` – the Courses page
- `cpt363-basic/` – CPT363-1, organised by modules: `welcome.md`, `module-01.md` … `module-13.md`
- `cpt363-intermediate/` – CPT363-2, organised by modules
- `cpt363-advanced/` – CPT363-3, organised by weekly units: `week-01.md` … `week-13.md` (weeks not yet published in Grav aren't in the sidebar)
- in each course folder: its `home.md`, the course pages in the navbar (`schedule.md`, `syllabus.md` …), `contact.md` and `images/`

Only the modules, weeks and course pages are converted – each course's Read Me is about the Grav site, and pages such as a blog stay there.

Each page also keeps its Grav settings in a hidden note at the top, so the converter can turn these pages back into the same Open Course Space courses and Courses page.
