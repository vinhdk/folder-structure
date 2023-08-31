```
root
├── dist
│   ├── index.html
│   ├── build.js
│   └── ...
├── core
│   ├── modules
│   │   ├── account
│   │   │   ├── languages
│   │   │   ├── data-access
│   │   │   │   ├── interfaces
│   │   │   │   ├── enums
│   │   │   │   ├── constants
│   │   │   │   ├── types
│   │   │   │   ├── stores
│   │   │   │   ├── services
│   │   │   │   ├── models
│   │   │   │   └── ui
│   │   │   │       ├── components
│   │   │   │       ├── directives
│   │   │   │       └── pipes
│   │   │   ├── account.module.ts
│   │   │   └── account.drective.ts
│   │   ├── contact
│   │   └── ...
│   ├── common
│   │   ├── data-access
│   │   │   ├── interfaces
│   │   │   ├── enums
│   │   │   ├── constants
│   │   │   ├── types
│   │   │   ├── stores
│   │   │   ├── services
│   │   │   └── models
│   │   ├── logics
│   │   │   ├── factories
│   │   │   └── guards
│   │   └── ui
│   │       ├── components
│   │       ├── directives
│   │       └── pipes
│   ├── layout
│   │   ├── edit-view
│   │   │   ├── data-access
│   │   │   │   ├── interfaces
│   │   │   │   ├── enums
│   │   │   │   ├── constants
│   │   │   │   ├── animations
│   │   │   │   ├── types
│   │   │   │   ├── stores
│   │   │   │   └── services
│   │   │   └── ui
│   │   │       ├── components
│   │   │       ├── directives
│   │   │       └── pipes
│   │   ├── list-view
│   │   │   ├── data-access
│   │   │   │   ├── interfaces
│   │   │   │   ├── enums
│   │   │   │   ├── constants
│   │   │   │   ├── animations
│   │   │   │   ├── types
│   │   │   │   ├── stores
│   │   │   │   └── services
│   │   │   └── ui
│   │   │       ├── components
│   │   │       ├── directives
│   │   │       └── pipes
│   │   ├── detail-view
│   │   │   ├── data-access
│   │   │   │   ├── interfaces
│   │   │   │   ├── enums
│   │   │   │   ├── constants
│   │   │   │   ├── animations
│   │   │   │   ├── types
│   │   │   │   ├── stores
│   │   │   │   └── services
│   │   │   └── ui
│   │   │       ├── components
│   │   │       ├── directives
│   │   │       └── pipes
│   │   ├── quick-view
│   │   │   ├── data-access
│   │   │   │   ├── interfaces
│   │   │   │   ├── enums
│   │   │   │   ├── constants
│   │   │   │   ├── animations
│   │   │   │   ├── types
│   │   │   │   ├── stores
│   │   │   │   └── services
│   │   │   └── ui
│   │   │       ├── components
│   │   │       ├── directives
│   │   │       └── pipes
│   │   └── ...
│   ├── chat-connection
│   │   ├── data-access
│   │   │   ├── interfaces
│   │   │   ├── enums
│   │   │   ├── constants
│   │   │   ├── animations
│   │   │   ├── types
│   │   │   ├── stores
│   │   │   └── services
│   │   └── ui
│   │       ├── components
│   │       ├── directives
│   │       └── pipes
│   ├── user-preference
│   │   ├── data-access
│   │   │   ├── interfaces
│   │   │   ├── enums
│   │   │   ├── constants
│   │   │   ├── animations
│   │   │   ├── types
│   │   │   ├── stores
│   │   │   ├── services
│   │   │   └── models
│   │   └── ui
│   │       ├── components
│   │       ├── directives
│   │       └── pipes
│   └── design-system
│       ├── data-access
│       │   ├── interfaces
│       │   ├── enums
│       │   ├── constants
│       │   ├── animations
│       │   └── types
│       ├── ui
│       │   ├── components
│       │   ├── directives
│       │   └── pipes
│       └── assets
│           ├── fonts
│           ├── icons
│           ├── svgs
│           ├── jsons
│           ├── images
│           └── styles
│               ├── animations -> animations if needed
│               │   ├── mixins
│               │   └── functions
│               ├── components -> for components styling
│               │   ├── mixins
│               │   └── functions
│               ├── typography
│               │   ├── mixins
│               │   ├── functions
│               │   └── variables
│               ├── palette -> color, shadow
│               │   ├── mixins
│               │   ├── functions
│               │   └── variables
│               ├── resolution -> responsive
│               │   ├── mixins
│               │   ├── functions
│               │   └── variables
│               ├── theme
│               │   ├── mixins
│               │   ├── functions
│               │   └── variables
│               └── settings -> settings for all
│                   └── mixins
└── src
    ├── app
    │   ├── routes
    │   │   ├── auth
    │   │   │   ├── login
    │   │   │   ├── register
    │   │   │   └── ...
    │   │   └── core
    │   │       ├── core.component.ts -> call api and load user config view(sidebar navigation icons,...)
    │   │       └── core.routes.ts
    │   ├── custom
    │   │   ├── account
    │   │   │   ├── data-access
    │   │   │   │   └── ...
    │   │   │   └── ui
    │   │   │       ├── components
    │   │   │       ├── directives
    │   │   │       └── pipes
    │   │   └── ...
    │   ├── app.component.ts
    │   ├── app.routes.ts
    │   ├── index.html
    │   └── styles.scss
    ├── assets
    │   ├── images
    │   ├── svgs
    │   ├── jsons
    │   └── videos
    └── environments

```
