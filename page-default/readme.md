# Component Default

Starting files and dirs for new pages.

#### create command

```sh
# App component:
hof new page "design/<page-name>"

# Module page:
hof new page "design/modules/<module-name>/<page-name>"

# Type page:
hof new page "design/modules/<module-name>/<type-name>/<page-name>"
```

#### output structure

The output will appear in one of the directory levels.

```
design/modules/
├── <module-name>
│   ├── <type-name>.yaml
│   │   │
│   │   │   # New Page Layout
└───└───└── Page<page-name>.yaml
            └── pages
                └── <page-name>
                    ├── content.html
                    └── style.scss

```


