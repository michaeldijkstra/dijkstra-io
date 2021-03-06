# [Dijkstra.io](http://dijkstra.io)

## How does this thing work?

### Gatsbyjs

+ Contentful: https://hunterchang.com/gatsby-with-contentful-cms/
+ Stack: https://www.halfelectronic.com/post/setting-up-gatsby-js-contentful-and-netlify/
+ Modal: https://www.gatsbyjs.org/blog/gatsbygram-case-study/
+ Page Transitions: https://github.com/gatsbyjs/gatsby/tree/master/examples/using-page-transitions
+ This line "Always try out queries in graphiql and rely on their
  autocomplete/type information": https://spectrum.chat/thread/a9182df6-0204-4377-95c7-36a21c5c0976
+ https://www.netlify.com/blog/2017/07/20/how-to-integrate-netlifys-form-handling-in-a-react-app/

### Netlify

### Contentful

+ https://www.contentful.com/r/knowledgebase/how-attribution-works/


## What's in the code?

### React

+ Styled components: https://www.styled-components.com/docs/basics#extending-styles
+ https://github.com/styled-components/styled-components/blob/master/docs/tips-and-tricks.md
+ Images: https://www.gatsbyjs.org/packages/gatsby-image/
+ Parallax: https://github.com/gilbox/react-spark-scroll

#### Why styled components

Right as I was building this site there was a good [Twitter
discussion](https://twitter.com/mjackson/status/964662241168539648) about CSS
in React apps. My takeaway was overcoming the awkwardness I first encountered
when combining my HTML and JavaScript, adding CSS to the mix makes sense here
and now everything is a component but it can also easily be extended.


## Development
+ Clone the repo
+ Run `npm install`
+ Run `gatsby develop` and open `http://localhost:8000`

## Deploy

This site will automatically deploy via [Netlify](https://www.netlify.com) when
pushed to [Github](http://www.github.com).
