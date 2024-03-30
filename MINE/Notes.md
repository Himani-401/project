# NOTES

min-height : property that sets the minimum height of an element. It ensures that the element will never be smaller than the specified value, even if its content is smaller or if other factors would cause it to be smaller.

In Fex Model, We will first make a flex container (parent)

Main-axis : Horizontal Line
</br>
Cross-axis : Vertical Line

Flex-direction : applied in flex container which defines the direction in which the child elements are laid out within the flex container.

justify-content: space-between; is applied to a flex container (parent element) to distribute the space between the flex items (child elements).

align-items : is applied to the parent flex container, not to the child flex items. It controls how the flex items are aligned within the flex container along the cross-axis.

width : 90% -> Which means 90% of the parent element width.

margin: 0px auto; sets the top and bottom margins of an element to 0 pixels and the left and right margins to automatic. typically resulting in centering the element horizontally within its containing block.

padding: 30px 0px;, it sets the padding to 30 pixels on the top and bottom sides of the element and 0 pixels on the left and right sides.

font-size: 1.4rem;, the font size is set to 1.4 times the size of the root element's font size.(typically the `<html>` element).

transition property allows you to control the transition effect when a CSS property changes its value.

`<i class="fa-solid fa-magnifying-glass"></i>` : using the Font Awesome library to add an icon to your HTML document and make sure link the Font awesome library for the icon to display.

line-height : controls the amount of vertical space between lines of text. It determines how tall each line of text should be within an element.By adjusting this property, you can change the spacing between lines to make text easier to read and look better on the page.

If you want the background image to be centered both horizontally and vertically within its container, you can use the background-position property with the value center center.

background-size: cover; ensures that the background image covers the entire background area while maintaining its aspect ratio. This property scales the background image as large as possible so that the background area is completely covered by the background image, without stretching or distorting the image.

background-attachment: fixed; to your CSS ensures that the background image remains fixed in place while the content of the webpage scrolls.

The box-sizing: border-box; By default, when you set the width and height of an element in CSS, those dimensions only apply to the element's content area. Any padding or border added to the element increases its overall width and height, potentially causing layout issues. However, when you apply box-sizing: border-box; to an element, it changes the box model so that the specified width and height include both the content area and any padding or border. This means that the element's padding and border are contained within the specified width and height, rather than adding to them.

justify-content: space-between; CSS property is used to distribute space evenly between the flex items along the main axis of a flex container, with extra space placed between the items.

If you have a box with a positive horizontal offset (box-shadow: 0.5rem 0 ...;), the shadow will appear to the right of the box.

If you have a box with a negative horizontal offset (box-shadow: -0.5rem 0 ...;), the shadow will appear to the left of the box.

If you have a box with a positive vertical offset (box-shadow: 0 0.5rem ...;), the shadow will appear below the box.

If you have a box with a negative vertical offset (box-shadow: 0 -0.5rem ...;), the shadow will appear above the box.

Adjusting the blur radius value in your CSS allows you to control the sharpness or softness of the shadow, enabling you to achieve the desired visual effect for your design.

width: 78%;: Sets the width of the element to 78% of its containing block's width. This means the element will take up 78% of the available horizontal space.

Bootstrap is a framework of HTML, CSS , Javascript.

carousel-control-prev class is used in Bootstrap to style the previous control button in a carousel.

data-bs-target attribute specifies the ID of the carousel to control

The data-bs-target attribute is set to the ID of the carousel element that the control button should interact with. This attribute helps Bootstrap identify the target carousel when the control button is clicked, allowing it to perform the appropriate slide transition.

data-bs-slide attribute is used in Bootstrap to specify the direction of sliding when a carousel control button is clicked. It determines whether the carousel should move to the previous or next slide.

Imagine you have a box on a webpage that's just there for decoration, like a picture that doesn't convey important information. For people who use screen readers because they can't see the screen, it's helpful if the screen reader doesn't waste time describing this picture because it doesn't add anything useful. So, you can add aria-hidden="true" to that box to tell the screen reader to skip over it and not read it out loud.

target="_blank" is an attribute commonly used in HTML anchor (<a>) tags to specify that when the link is clicked, the linked document should open in a new browser window or tab.
