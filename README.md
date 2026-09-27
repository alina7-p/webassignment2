# Assignment no2 — Advanced CSS: Flexbox & Grid

**Name:** Alina Ibadulla

**Group:** SE-2540

Project: NOVA — Creative Studio. NOVA is a creative digital studio website created to demonstrate the use of modern CSS layout techniques. The website combines Flexbox, CSS Grid, Grid Areas, responsive design, and hover effects.

! GitHub Pages Link: https://alina7-p.github.io/webassignment2/


Task 0 — Navigation Bar

The navigation bar was created using CSS Flexbox.

* The logo is positioned on the left.
* Navigation links are positioned on the right.
* `justify-content: space-between` is used to create space between the logo and navigation.
* `align-items: center` is used for vertical alignment.
* `gap` is used to create consistent spacing between navigation links.
* Hover effects are added to the links.

<img width="1367" height="747" alt="Screenshot 2026-09-27 at 19 58 32" src="https://github.com/user-attachments/assets/a2ab6353-c0e1-449c-95a4-76b17021861c" />


Task 1 — Card Row

Three service cards were created using Flexbox.

Each card contains:

* An image area
* A title
* A description
* A button

The cards are displayed in one row with equal widths and consistent spacing.

Flexbox properties used:

* `display: flex`
* `flex: 1`
* `gap`
* `align-items: stretch`
* `flex-direction: column`

A hover effect was also added to the cards.

<img width="1357" height="740" alt="Screenshot 2026-09-27 at 19 59 33" src="https://github.com/user-attachments/assets/03499ac0-87a2-4d2f-bd8a-5e45d06c781c" />

Task 2 — Page Layout with Grid Areas

The studio layout was created using **CSS Grid** and `grid-template-areas`.

The layout contains:

* Header
* Sidebar
* Main content
* Footer

The Grid structure is:

```text
Header
-------------------------
Sidebar | Main
-------------------------
Footer
```

The following CSS properties were used:

* `display: grid`
* `grid-template-columns`
* `grid-template-rows`
* `grid-template-areas`
* `grid-area`

The layout is also responsive and changes to a single-column structure on smaller screens.

<img width="1360" height="748" alt="Screenshot 2026-09-27 at 20 00 07" src="https://github.com/user-attachments/assets/0854edb0-a51f-43f4-9728-7a0c78fcc4b4" />

Task 3 — Image Gallery

A gallery containing **nine images** was created using CSS Grid.

The gallery uses:

* Three columns on large screens
* Two columns on medium screens
* One column on small screens
* Equal spacing between images
* Hover effects
* Image captions

When the user moves the mouse over an image, the image zooms slightly and the caption appears.

CSS Grid properties used:

* `display: grid`
* `grid-template-columns`
* `repeat()`
* `gap`

<img width="1358" height="745" alt="Screenshot 2026-09-27 at 20 00 49" src="https://github.com/user-attachments/assets/d670d457-a697-40e6-a403-11eb0c7620f0" />


Task 4 — Portfolio Page

The portfolio section combines CSS Grid and Flexbox.

The layout contains:

* A projects section
* A sidebar with additional information
* Four project cards
* Project titles, descriptions and links

CSS Grid is used to divide the page into the projects area and sidebar.

Flexbox is used inside the project cards to arrange the content vertically.

The project cards also include hover effects.

<img width="1356" height="739" alt="Screenshot 2026-09-27 at 20 01 30" src="https://github.com/user-attachments/assets/5b752127-67bf-415d-8a7a-cb9f01cae364" />


Responsive Design

The website was designed to work on different screen sizes.

Media queries were added for:

* Desktop
* Tablet
* Mobile

On smaller screens:

* The navigation becomes vertically organized.
* Cards are displayed in a column.
* The gallery changes from three columns to two and then one column.
* The portfolio layout becomes a single column.
* The Grid Areas layout changes to a vertical structure.


# Project Structure

```text
assignment2/
│
├── index.html
├── style.css
├── README.md
│
└── screenshots/
    ├── task0.png
    ├── task1.png
    ├── task2.png
    ├── task3.png
    └── task4.png
```

# Work Process

First, I created the basic HTML structure for the website and divided it into different sections corresponding to the assignment tasks.

Then, I created the main styles in CSS and used Flexbox for the navigation bar and service cards.

After that, I implemented CSS Grid for the studio layout and used `grid-template-areas` to organize the header, sidebar, main content and footer.

For Task 3, I created a nine-image gallery using CSS Grid and added hover effects for the images and captions.

For Task 4, I combined CSS Grid and Flexbox to create the portfolio layout and project cards.

Finally, I added responsive design using media queries so that the website works on smaller screens. I tested the layout and checked that the project runs without errors.

Conclusion

This assignment helped me understand how Flexbox and CSS Grid can be used to create modern and responsive web layouts. I also learned how to combine different CSS layout techniques, create hover effects, and adapt a website for different screen sizes.
