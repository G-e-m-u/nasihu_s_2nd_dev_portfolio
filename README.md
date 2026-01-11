# nasihu_s_2nd_dev_portfolio
A fully responsive city skyline illustration built entirely with HTML and CSS, using flexbox, gradients, and CSS variables, no images or JavaScript.

This project is a pure HTML and CSS city skyline illustration that renders a layered urban scene with background and foreground buildings, windows, and a dynamic sky. No images, SVGs, or JavaScript are used. Every visual element is created entirely with CSS.

The structure is built using semantic div groupings for background and foreground layers. Buildings are composed of nested elements that represent architectural parts such as rooftops, facades, and windows. This layered layout creates depth by positioning background buildings behind foreground ones using absolute positioning and flexible spacing.

CSS Flexbox is heavily used to align buildings evenly across the viewport and to stack building sections vertically. Flexbox is also used to distribute windows within window rows and columns, allowing the skyline to scale smoothly across different screen sizes.

The project makes extensive use of CSS custom properties (variables) to control building and window colors. This allows for easy theme changes and centralized color management. A media query overrides these variables on smaller screens to switch the skyline into a monochrome nighttime style without rewriting individual styles.

Most building textures and window patterns are created using linear and repeating-linear gradients. These gradients simulate rows and columns of windows, stripes, and facade details, eliminating the need for repeated markup. Multiple gradients are layered together to create complex visual patterns within a single element.

Architectural shapes such as rooftops, spires, and angled structures are formed using CSS borders and transparent borders, a common technique for creating triangles and slanted edges. Rounded windows are achieved with border-radius, adding visual variety across buildings.

The sky is generated using a radial gradient to simulate sunlight and atmospheric depth. This background adapts responsively through media queries to reflect different lighting conditions based on screen width.

Overall, this project demonstrates how far modern CSS can be pushed to create detailed illustrations, layered scenes, and responsive designs using only core web technologies.
