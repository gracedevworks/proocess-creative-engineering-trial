# proocess-creative-engineering-trial

## Design decision
There are lots of approach that can be done to achieve the design but I keep it as simple as much as possible. I used the existing Horizon elements, blocks, dynamic content, and section and keep it user-friendly or easy to use and update to avoid custom coding for the non-techy users. 

For easy updating of the contents, I've added additional settings for the custom font family, mobile font size, padding for mobile, and max width in the theme customiser. 

To achieve the editorial section in the design, I created a custom theme block that contains static blocks to have so much control to the layout and achieve the design on both desktop and mobile using grid.

For the custom image swatches, I used metaobjects since product taxonomy or product category is limited to store the custom images.

## Metafield/metaobject setup
### Metafield
- Recommended Products Heading - (Single line text) - For the “Recommended Products” block heading
- Recommended Products - (Product List) - For the selection of products to display in the section. Set to maximum of 2 products
- Short Description - Connected to the text at the top of the product title
- Ring Design - the metafield connected to product category and metaobject for custom variant image
- Ring Polish - the metafield connected to product category and metaobject for custom variant image

### Metaobjects
- Custom Option - consists of label and image for the custom image swatches

## Challeges Faced
 - Can't access reference for storefront password which is needed for the development using Shopify CLI so I used another dev store where I have more access to continue the development
 - Timing and tight schedule
 - Limited access to Figma file to get the accurate gaps, margins, and paddings
