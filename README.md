# hack-uva
##Inspiration
We wanted to work on a hack that would help make the web more accessible for everyone.

##What it does
It parses the user's HTML code and inline CSS and outputs the possible accessibility errors and warnings the code contains. These errors cause screen readers and other accessibility software to read misleading information to users of the website who have disabilities. Most web accessibility checkers audit websites after they are completed. Our site is designed for developers in the process of building a website so that fewer accessibility errors are present in the final product. Our errors and warnings are based on the Web Content Accessibility Guidelines (WCAG) 2.0 AA standards. These are the standards used by the Americans with Disabilities Act (ADA) and Section 508, both of which are American federal laws concerning accessibility.

##How we built it
We used a design template and customized the HTML elements to our needs to create the front end. We then wrote Javascript functions that would process the HTML code entered by the user searching for the most typical errors that affect the accessibility of websites when using the most common screen readers.

##Challenges we ran into
This project was relatively straightforward to complete. One strangely time-consuming feature was adding line numbers to user's code so that they would be able to refer to it since we attempted to implement it two different ways before we were successful.

##Accomplishments that we're proud of
We are proud that the project is ready on time and that it is just as functional as we wanted it to be when we first started coding. We are happy with the style and design of the different pages and we also put special care not to incur in our own website any of the accessibility errors that our own parser checks for! :)

##What we learned
This project was a lesson on teamwork, especially since we were racing against the clock. We had to communicate very clearly what we meant so other members of the team would be able to complete their work more effectively. Aside from the practice that we gained in web development techniques, this project also helped us hone our interpersonal skills.

##What's next for Web Accessibility Checker
There are lots of less common errors that the parser can be easily adapted to catch. A fairly significant feature that could be added is the option of processing HTML code with a separate style sheet instead of inline CSS.