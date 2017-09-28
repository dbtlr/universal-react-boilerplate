# Build Your Own Universal React Boilerplate

### Intent

Over and over again I find myself trying to rebuild the wheel when I want to start a new project. My needs are fairly straight-forward and nearly 100% predictable, but getting the tools ready to go in order to do this in React always ends up being a bigger deal than it should, and thus I don't build.

Thus I want to build a React Boilerplate from scratch for 2 reasons:

1. So that I don't have to keep circling around this same process instead of building.
2. So that I can get a better understanding of some of the base tools and settings.

### Expectations

The application base should meet the following minimums:

1. Allow for the use of Babel transpiling from the newest ES2017 standards
2. Use webpack to serve and build assets
3. Allow for easy Universal and Server-only routes
4. Provide a basis for user registration and authentication using JWT and Passport
5. Uses Redux and GraphQL for querying from the server
6. Connects to a PostgreSQL database (Mongo is too loose for me)
7. Uses StyledComponents for style updates and customization
8. Uses ReactStrap for Bootstrap 4.0 integration
9. Have sane ESLint standards baked in
10. Maintains a sane component directory structure

### Directory Structure

```

├── src
│   ├── client
│   │   └ index.js
│   ├── components
│   │   ├── Elements
│   │   │   ├── Form
│   │   │   │   ├── Input.jsx
│   │   │   │   └── TextArea.jsx
│   │   │   └── Button.jsx
│   │   ├── Layout
│   │   │   ├── Footer.js
│   │   │   ├── Header.js
│   │   │   ├── index.js
│   │   │   └── TopNavigation.js
│   ├── routes
│   │   ├── Auth
│   │   │   ├── LoginPage.jsx
│   │   │   ├── SignUpPage.jsx
│   │   │   ├── ForgotPasswordPage.jsx
│   │   │   └── ResetPasswordPage.jsx
│   │   ├── HomePage.jsx
│   │   ├── index.jsx
│   │   └── NotFoundPage.js
│   ├── server
│   │   └ index.js
│   ├── store
│   │   ├── modules
│   │   │   └── index.js
│   │   └── createStore.js
│   ├── static
│   │   └── favicon.ico
│   └── views
│       └──  index.ejs
│
├── package.json
└── webpack.config.js
        
```

### License

I'm licensing this boilerplate under the MIT license so that it is freely used by all. Not that I expect much to be done with it, considering there are a billion other boilerplates out there, but here it is.