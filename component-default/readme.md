# Component Default

Starting files and dirs for new components.

#### create command

```sh
# App component:
hof new component "design/<component-name>"

# Module component:
hof new component "design/modules/<module-name>/<component-name>"

# Type component:
hof new component "design/modules/<module-name>/<type-name>/<component-name>"
```

#### output structure

The output will appear in one of the directory levels.

```
design/modules/
├── <module-name>
│   ├── <type-name>.yaml
│   │   │
│   │   │   # New Component Layout
└───└───└── Component<component-name>.yaml
            └── components
                └── <component-name>
                    ├── content.html
                    └── style.scss

```


