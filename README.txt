# Applying PAB branding using Bootstrap / Webpack install #

Deployment at https://pab-prototyping.netlify.app/
https://app.netlify.com/sites/pab-prototyping/deploys


Resources:
https://getbootstrap.com/docs/5.0/getting-started/webpack/

To start dev: 
npm start

Build for production:
npm run build
Currently set to deploy automatically via Github repo.

# TO DO #

Make menu mobile first - padding on items
Sort out evet cards on tablet
hover styles for footer links
link up social media icons
Slightly earlier break point for menu  toggle
Get rid of down arrows

# Theming notes: #

With an aim to keep hover and focus states and transitions across components consistent I've added '_hoverPAB' so that we can eventually settle on patterns and refactor to create mixins.

Adding icon left of drop down menu item - Include within text and use me-3 to pad icon on the right before menu text.

Colours - still working on creating custom mapping of brand colours but it was buggy - amending $dark01 in  'defaultsPAB' works fine however. (Still deciding on colour pallette as of 26th Jan)

Line-height - need to understand this: https://css-tricks.com/how-to-tame-line-height-in-css/

# Accessibility feedback to get #

When tabbing over cards, would it be visually less confusing if the Read more buttons are dark green on focus rather than initially? https://css-tricks.com/how-to-tame-line-height-in-css/https://css-tricks.com/how-to-tame-line-height-in-css/