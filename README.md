Powered by [Gatsby](https://gatsbyjs.org/) Offical Graphql [Tutorial](https://www.gatsbyjs.org/tutorial/part-four/)

# Gatsby-starter-blog

+ glamorous
+ gatsby-plugin-glamor
+ gatsby-plugin-typography
+ gatsby-source-filesystem
+ gatsby-transformer-remark
+ typography-theme-kirkham

## Structure
.  
├── LICENSE  
├── README.md  
├── gatsby-config.js  
├── gatsby-node.js  
├── package-lock.json  
├── package.json  
├── public  
│   ├── index.html  
│   ├── render-page.js.map  
│   └── static  
├── src  
│   ├── layouts  
│   │   └── index.js  
│   ├── pages  
│   │   ├── about.js  
│   │   ├── index.js  
│   │   ├── my-files.js  
│   │   ├── pandas-and-bananas.md  
│   │   └── sweet-pandas-eating-sweets.md  
│   ├── templates  
│   │   └── blog-post.js  
│   └── utils  
│       └── typography.js  
└── yarn.lock  

+ Add plugins and GraphQLData: `gatsby-config.js`
+ Generate data: `gatsby-node.js`
+ Post template: `src/templates`

We configure layouts in `gatsby-config.js`, nest templates and common pages  
__Layouts__ called by remark plugin, render our markdowns

## Running in development
`gatsby develop`
