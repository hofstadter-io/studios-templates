# Module Default

Starting files and dirs for new types.

#### create command

```sh
hof new module "design/modules/<module-name>"
```

#### output structure

This will create a skeleton of
directories, designs, and other files:

```
design/modules/
└── <module-name>
    ├── module.yaml
    ├── pages/
    │   └── <page-name>/
    │       ├── content.jsx
    │       └── style.scss
    ├── components/
    │   └── <component-name>/
    │       ├── content.jsx
    │       └── style.scss
    ├── locales
    │   ├── en.json
    │   └── es.json
    └── seeds/
        └── default.json
```

