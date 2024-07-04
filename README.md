========================================-----------Home Page--------------=================================

HTML Structure -------:

1. Container for Services Section:
   A div with the class container contains the heading "OUR SERVICES" and a description of the services offered.

2. Main Services Section:
   A div with the class main includes three div elements (main1, main2, main3), each containing an image and a heading for different types of services (Residential, Commercial, Industrial).

3. Additional Services Section:
   A div with the class choose includes three more div elements (choose1, choose2, choose3), each with an image and a heading for additional services (Electrical Installations, Repairs, Solar Panel Installation).

4. Why Choose Us Section:
   A div with the class colom includes two main div elements (colom1, colom2). colom1 contains a heading and a description, while colom2 is meant to hold an image (currently commented out).
   Inside colom1, there are more div elements (box1, box2, box3, box4) for displaying specific advantages (Expertise, Safety, Transparent, Reliability).

5. Call to Action Section:
   A div with the class yummy includes an image and a call to action text with a button for contacting the service.

6. FAQ Section:
   A div with the class accordion contains multiple div elements (accordion-item), each representing a frequently asked question with its answer. Clicking on the header toggles the visibility of the answer.

JavaScript------------:

1. Toggle Accordion Function:
   toggleAccordion(element) is a function that toggles the display of the accordion content when the header is clicked. It hides all other contents and only shows the clicked one.

2. Animation Delay on Load:
   DOMContentLoaded event listener is used to set animation delays for elements with the class animate, creating a staggered animation effect when the page loads.

=========================================------------About Us--------------================================
CSS Styles-------:
Embedded within the <style> tag, the CSS styles define the appearance of various elements on the webpage. It includes settings for backgrounds,
dimensions, font sizes, margins, paddings, and other stylistic choices for different classes.

1. Body Content:
   Header Section (orange class):
   A div with an orange background containing the company's mission statement and a paragraph.

2. Image Section (ora1 class):
   An image spanning the full width of the section.
   Company Info Section (both class):
   Includes an icon, a heading, and a paragraph describing the company.

3. Content Section (content5 class):
   Divided into two sub-sections:
   content51: Contains a heading, paragraph, and a button.
   content52: Four boxes each containing a heading and a paragraph, highlighting reasons to choose the company.

4. Support Section (para5 class):
   Includes another div (para1) with an image and text about 24/7 support.
   Team Section (new class):
   Introduces the team with images and titles for four team members.

5. Services Section (main class):
   Three divs each representing a service (Residential, Commercial, Industrial) with an image and heading.

6. How We Work Section (function class):
   Describes the company's work process through a series of steps.
   Testimonials Section (abhi class):
   Contains customer testimonials in styled boxes.

7. Blog Section (full class):
   Promotes the company's blog with images, headings, and summaries of articles.

8. CSS Classes and Their Purposes:
   orange, para, content5, etc.: Define styles for various sections like background colors, dimensions, font sizes, margins, and paddings.
   imad, both, para1, etc.: Style specific content within sections, such as images, headings, and paragraphs.
   content51, content52, box: Layout and style the "Why Choose Us" section and its boxes.
   main, main1, main2, main3: Style the services section with specific layouts and colors.
   bot, bot1, bot2: Define the steps in the "How We Work" section.
   abhi, stars, star1: Style the testimonials section with different layouts and colors.
   full, drop, last: Style the blog section with images and text.

=========================================-----------Services--------------================================

HTML Structure-----------:

1. Container for Services Section:

   A div with the class container contains the heading "OUR SERVICES" and a description of the services offered.

2. Main Services Section:
   A div with the class main includes three div elements (main1, main2, main3), each containing an image and a heading for different types of services (Residential, Commercial, Industrial).

3. Additional Services Section:
   A div with the class choose includes three more div elements (choose1, choose2, choose3), each with an image and a heading for additional services (Electrical Installations, Repairs, Solar Panel Installation).

4. Why Choose Us Section:
   A div with the class colom includes two main div elements (colom1, colom2). colom1 contains a heading and a description, while colom2 is meant to hold an image (currently commented out).
   Inside colom1, there are more div elements (box1, box2, box3, box4) for displaying specific advantages (Expertise, Safety, Transparent, Reliability).

5. Call to Action Section:
   A div with the class yummy includes an image and a call to action text with a button for contacting the service.

6. FAQ Section:
   A div with the class accordion contains multiple div elements (accordion-item), each representing a frequently asked question with its answer. Clicking on the header toggles the visibility of the answer.

CSS Styling ------:

1. General Styles:
   Styles for font sizes, background colors, margins, paddings, and text alignment for various sections and elements.
   Flexbox is used to arrange elements in a row (display: flex;).

2. Button Styles:
   Styles for buttons, including background color, font size, cursor, transition effects, and hover effects.

3. Accordion Styles:
   Styles for the accordion component, including header, content, hover effects, and active states.
4. Animation Styles:
   An animation is defined (slideUp) to make elements slide up and become visible. This is applied to elements with the class animate.

JavaScript------------:

1. Toggle Accordion Function:
   toggleAccordion(element) is a function that toggles the display of the accordion content when the header is clicked. It hides all other contents and only shows the clicked one.

2. Animation Delay on Load:
   DOMContentLoaded event listener is used to set animation delays for elements with the class animate, creating a staggered animation effect when the page loads.

=========================================------------Shop Page-------------================================
HTML ----:

1. Header and Metadata:
   The HTML starts with a standard document structure, setting the language and meta tags for charset and viewport.
   Links to CSS files and Font Awesome for icons are included.

2.Body Content:
Background Image Section: This section has a background image with some centered text.
Product Features Section: Three columns highlight key features like free shipping, high quality, and a 1-year warranty.
Product Listing Section: A two-part container:
Categories: A list of product categories with icons.
Products: Each product displays an image, name, price, and an "Add to Cart" button.
Promotion Section: Highlights a special offer with an image and text encouraging users to contact the store.
FAQ Section: A list of frequently asked questions with collapsible answers.

CSS ------------:
1.Basic Styles:
Sets default margins and padding to zero and applies a font family.
Defines a primary color variable.
Background Image Styles:
Sets the background image to cover the entire section and centers the content.

2.Product Features Styles:
Creates a section with three columns, each containing an icon, a title, and a description.
Product Listing Styles:

Styles the category list with icons and the product list with images, titles, prices, and buttons.
Promotion Section Styles:
A flexbox layout with an image on one side and text on the other.

3.FAQ Section Styles:
Creates an accordion-style FAQ with clickable headers that show and hide the answers.

4.JavaScript -------:
Accordion Function:
Defines a function toggleAccordion that toggles the display of the answer when a question is clicked.
Only one answer is displayed at a time, hiding others when a new question is clicked.

=========================================================================================================
-------------------------/////////////////////////////////////////////////////////-----------------------
========================== ========================== ===========================================

=============================-------Pricing Page-----------------========================================
HTML -------------:

1. Head Section:
   Includes metadata, title, and links to external stylesheets (FontAwesome for icons and a custom CSS file price.css).
   Links to an external JavaScript file price.js.

2. Body Section:
   2.1.Pricing Section:
   Contains three pricing cards (BASIC PLAN, PRO PLAN, and EMERGENCY PLAN).
   Each card includes a plan name, price, form with checkboxes for services, and a "Buy now" button.
   2.2.Comparison Section:
   Includes a heading and a table to compare different pricing plans.
   Big Lite Section:
   Contains an image and a content block with a heading, paragraph, and a "Contact Us" button.
   2.3.FAQ Section:
   Contains a heading and an accordion with four FAQ items.

CSS Styles ------:

1. Root Variables:
   Defines a primary color --primart-one used throughout the design.

2. Global Styles:
   Applies a box-sizing, margin, and padding reset, and sets the default font family to sans-serif.

3. Section Styles:
   Sets the background color, dimensions, and text alignment for the main section.
   Styles the heading and cards with padding, colors, and box-shadow for cards.

4.Card Styles:
Sets background, padding, dimensions, and border-radius for cards.
Styles for form elements, buttons, and card-specific elements.

5. Comparison Table Styles:
   Styles the table, headers, and rows, including alternating row colors.

6. Big Lite Section Styles:
   Defines styles for the content section, including text alignment, padding, and button styles.

7. FAQ Section Styles:
   Styles for the accordion and FAQ items, including the header, content, and hover effects.
   Animation Styles:
   Defines a keyframe animation slideUp to animate elements on page load.
   Adds the animate class to elements to trigger the animation.

8. JavaScript Code------:

9. Accordion Functionality:
   The toggleAccordion function handles the opening and closing of the accordion items.
   It checks if the accordion content is already displayed; if so, it hides it and removes the "active" class.
   Otherwise, it hides all other contents and headers, then displays the clicked content and adds the "active" class.

2.Animation Initialization:
On DOM content load, it selects all elements with the animate class.
Sets an animation delay for each element based on its index to create a staggered animation effect.
Explanation of the toggleAccordion Function

3. This function toggles the display of accordion items:
   When an accordion header is clicked, the function checks if its associated content is currently visible.
   If visible, it hides the content and removes the "active" class from the header.
   If not visible, it first hides all other accordion contents and removes the "active" class from all headers.
   Then, it displays the clicked accordion's content and adds the "active" class to its header.
   Explanation of the Animation Initialization

4. This script runs when the DOM content is fully loaded:
   It selects all elements with the animate class.
   For each element, it sets a delay for the animation start based on the element's index. This creates a staggered animation effect where each element appears sequentially.

## ====================================///////////////////////////////////////////////=======================

==============================----------our Team Page----------=================================================
HTML------:
The HTML structure consists of different sections to display information about a team, a video, and FAQs.

1. Head Section :
   Includes meta tags, title, and links to external CSS (for styles) and JS (for functionality) files.
   Font Awesome is used for icons.
2. Body Section
   Team Section (team1 and team2):
   team1: Contains a heading and a paragraph introducing the team.
   team2: Displays individual team members, each with an image, name, role, and social media icons.
   Video Section (video):
   Contains an embedded YouTube video and a description with a quote from the CEO.
   3.FAQ Section (questions):
   Contains a FAQ section with accordion-style expandable items for different categories and questions.

CSS-------:

    The CSS provides styling for the HTML elements, including layout, colors, fonts, and animations.

1. Styles:
   Reset margins and paddings, set box-sizing to border-box, and apply a sans-serif font.
   Define a custom CSS variable --primart-one for a specific color.
   2.Team Section Styles:
   .team1: Background image, color, padding, and font sizes.
   .team2 .one: Styling for team member images and social media icons.
   .icons: Padding for the social media icon container.

3.Video Section Styles:

    .video: Flex layout to align items.
    .videoC: Background color, height, padding, and styling for the CEO section.
    FAQ Section Styles
    .questions: Padding for the FAQ section.
    .accordion: Styling for the accordion items, headers, content, and hover effects.

4. Animation Styles:

   .animate: Initial opacity and transform for animation effect.
   @keyframes slideUp: Defines the slide-up animation.

JavaScript---------:

    The JavaScript provides interactivity, mainly for the accordion functionality and animations.

1. Accordion Functionality
   toggleAccordion(element): Toggles the display of the accordion content when a header is clicked. If the content is visible, it hides it; otherwise, it shows it. It also ensures only one accordion content is open at a time by closing others.
2. Animation Initialization
   document.addEventListener('DOMContentLoaded', function() {...}): Adds a delay to the animation for elements with the class .animate to create a staggered animation effect
