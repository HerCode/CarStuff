# Group jQuery Challenge
You will be building a system that manages used car information. It will look something like this:

![mockups](mockup.png)

Make a form that can capture and store used car information:

- Make
- Model
- Year
- Color
- Customer Rating
- Price

When a user submits information through the form, store that information in an object. Use a list to display that information and all of the previously entered car information on the page.

In addition to the used car information add a 'remove' button next to each car's information. Clicking the 'remove' button will remove that specific car from the DOM.

In the review score section, implement some sort of color indicator based on their review. The reviews should only be able to be 1 - 5. 5 would indicate a good score, 1 would be poor. The way you display this is up to you.

Some potential methods of implementing the color indicator are:

- highlighting the entire `li` or `div` that the used car information is in
- or adding a different colored number for each score as it is displayed.
