# Related post Widget for Ghost CMS

Add Related post Widget After Post content on your Ghost Blog

- Add this on your theme's `post.hbs` file under `{{content}}` Section
- it requires ghost <b>Public API</b> Goto labs > Enable Public API to Get the Post data's

### Usage

- `limit="3"` - Display no of Posts on Related post Widget
- it get the result from the post tags - `{{#get "posts" filter="tags:{{tags.[0].slug}}+id:-{{id}}" limit="3" as |related_posts|}}{{/get}}`
- <a href="https://themes.ghost.org/docs/recent-featured-sidebar#section-extra-special-sauce-related-posts" target="_blank">Official Documentation</a>




