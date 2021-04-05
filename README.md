# Layout(Restaurant)

## Assignment 
Create a web page strictly according to the [layout](https://www.dropbox.com/s/xvhx2kxlvzxu5n0/Restaurant_2.psd?dl=0).

## Technical Requirements

### General

- [x] The name of the HTML file should be index.html
- [x] Create separate folders for images, fonts, and styles
- [ ] The markup width should be 1600px. Hence the layout will be tested on 1600px screen width or wider. The markup should be centered. If you are going to implement the task on the device with screen width lower then 1600px, the scrollbar will appear, and it is Ok (you can use zoom out)
- [ ] You should implement CSS style effects for the hover events(which effect to use is up to you - for example, the color of the navigation button can change on hover)
- [ ] The header can be fixed on the gradient background when scrolling
- [ ] Pay your attention to the fact that the background should be a graphic pattern, not just plain white
- [ ] You may use any grid markup you want (e.g.: Flex or Grid)
- [ ] Font-awesome can be used for icons

### Semantic layout

- [x] HTML5 semantic tags should be used: `header`, `nav`, `section`, `article`, `footer`, `form` + fields, `figure`
- [x] Class names should be reasonable and correct, avoid names such as .right-column, .third-form, .left, .big. Use more meaningful ones - .heading, .form-container, .wrapper, .menu-column. You are also welcome to use pseudo-classes (:first-child, last-child, etc.)
- [x] Using `id` for styles will be considered as a mistake
- [ ] The logo should be implemented correctly
- [x] Don't forget to use `<h1>` tag on the page
- [x] Navigation should be implemented with a `<nav>` tag. Clickable parts of the menu should be links

### Fonts
- [ ] The fonts should be imported properly. Don't forget about the font-weight

### Blocks and columns

- [ ] Consider the case with more text than in the markup - just add more text to the column and check if the position of the column or layout does not change (limitation by overflow)
- [ ] You should consider the case when one more column is added to menu section. This column should appear under the first one or in the center of the next line or hidden by overflow property. It should not break the layout by being positioned as a third visible element outside of parent's borders
- [ ] If you are going to use inline-block property, make sure that there is no free space between the elements
- [ ] Images in fine ingredients section should be square or rectangle-shaped and should be styled with CSS (border, border-radius)
- [ ] The form should be implemented with a form tag and with proper tags inside of it. Add basic browser validation for Email input field. Name, Email and Date fields should be required. Please ignore typo on one of template's input fields, you should fix it in your application
- [ ] The footer should be placed at the bottom of the page, meaning that if all the content but the footer is deleted from the page, the footer will still be placed at the bottom

### Other

- [ ] Pre-processors and post-processors are not necessary. In case if you decide to use these tools, the final file should still be in `.css` format. Use of libraries such as Bootstrap is not allowed
