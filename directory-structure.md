.
├── directory-structure.md
├── public
├── README.md
└── src
    ├── api
    │   ├── api.client.ts
    │   └── apis
    │       ├── auth
    │       │   └── auth.apis.ts
    │       ├── default
    │       │   ├── home.apis.ts
    │       │   └── profile.apis.ts
    │       └── shared
    │           └── file-storage.apis.ts
    ├── App.vue
    ├── components
    │   ├── auth
    │   │   └── shared
    │   │       └── AuthRedirect.vue
    │   ├── default
    │   │   ├── Home
    │   │   │   ├── HomeAds.vue
    │   │   │   ├── HomeHero
    │   │   │   │   ├── HeroTitle.vue
    │   │   │   │   └── HomeHero.vue
    │   │   │   └── HomeNews
    │   │   │       ├── HomeNews.vue
    │   │   │       └── NewsItem.vue
    │   │   └── Profile
    │   │       ├── Profile
    │   │       │   └── ProfileDescription.vue
    │   │       └── ProfileSettings
    │   │           ├── ProfileSettingsBlock.vue
    │   │           └── ProfileSettingsSave
    │   │               ├── ProfileSettingsSaveButton.vue
    │   │               └── ProfileSettingsSaveModal.vue
    │   └── shared
    │       ├── CardTitle.vue
    │       └── Tip.vue
    ├── layouts
    │   ├── auth
    │   │   ├── AuthLayout.vue
    │   │   └── Header
    │   │       └── AuthHeader.vue
    │   └── default
    │       ├── blocks
    │       │   ├── DefaultConfirmEmailBlock.vue
    │       │   └── DefaultNotAllowBlock.vue
    │       ├── DefaultLayout.vue
    │       └── PageWrapper
    │           ├── DefaultPageWrapper.vue
    │           ├── WrapperContent.vue
    │           └── WrapperHeader.vue
    ├── libs
    │   ├── assets
    │   │   └── styles
    │   │       ├── shared.scss
    │   │       └── tailwind.scss
    │   ├── classes
    │   │   ├── auth
    │   │   │   └── auth-lib.ts
    │   │   └── default
    │   │       └── default-lib.ts
    │   ├── composables
    │   │   ├── use-toaster.ts
    │   │   └── use-window-size.ts
    │   ├── configs
    │   │   └── app.config.ts
    │   ├── constants
    │   │   ├── auth.constant.ts
    │   │   └── default.constant.ts
    │   ├── directives
    │   │   └── click-outside.directive.ts
    │   ├── enums
    │   │   └── window-size.enum
    │   ├── inits
    │   │   └── sentry.init.ts
    │   ├── router
    │   │   ├── guards
    │   │   │   └── auth.guard.ts
    │   │   ├── router.ts
    │   │   └── routes
    │   │       ├── auth
    │   │       │   └── auth.routes.ts
    │   │       ├── default
    │   │       │   └── default.routes.ts
    │   │       └── routes.ts
    │   ├── stores
    │   │   ├── auth.store.ts
    │   │   └── pinia.ts
    │   └── types
    │       ├── auth
    │       │   └── auth.type.ts
    │       ├── default
    │       │   ├── default.type.ts
    │       │   └── home.type.ts
    │       └── shared
    │           └── shared.type.ts
    ├── main.ts
    └── pages
        ├── auth
        │   ├── AuthLogin.vue
        │   ├── AuthPasswordRecovery.vue
        │   └── AuthRegister.vue
        └── default
            ├── Home.vue
            └── Profile
                ├── Profile.vue
                ├── ProfileHistory.vue
                └── ProfileSettings.vue

52 directories, 59 files
