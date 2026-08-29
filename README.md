<p align="center">
  <br>
  <img width="240" src="logo.png" alt="awesome-shiny-extensions logo">
  <br>
  <br>
</p>

<!--lint disable awesome-heading-->

# Awesome Shiny Extensions with stars

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 500,888 | 🐛 105 | 📅 2026-08-21

A curated list of awesome R and Python packages offering extended UI or
server components to the web framework [Shiny](https://shiny.posit.co/).

Your contribution is welcomed. Please create a pull request or issue to
add packages to the list.

<hr>

* Inspired by: [awesome-react-components](https://github.com/brillout/awesome-react-components) ⭐ 48,288 | 🐛 83 | 📅 2026-01-26 and [awesome-rshiny](https://github.com/grabear/awesome-rshiny) ⭐ 870 | 🐛 7 | 🌐 R | 📅 2022-10-07.
* Please send pull requests: [contributing guide](.github/CONTRIBUTING.md) and [code of conduct](.github/CODE-OF-CONDUCT.md).
* A special thanks to all the package authors for making the world a better place!

<hr>

## Contents

* [Theming](#theming)
  * [Generic Theming](#generic-theming)
  * [Dashboard Theming](#dashboard-theming)
  * [Mobile Theming](#mobile-theming)
  * [Theme Customization](#theme-customization)
* [UI Components](#ui-components)
  * [Bootstrap](#bootstrap)
  * [File Input](#file-input)
  * [Special Input](#special-input)
  * [Loader](#loader)
  * [Feedback / Alert / Notification](#feedback--alert--notification)
  * [Walkthrough / Tooltip / Help](#walkthrough--tooltip--help)
  * [Clipboard](#clipboard)
  * [Color Picker](#color-picker)
  * [Editor](#editor)
  * [Chat](#chat)
  * [Table](#table)
  * [Drawers](#drawers)
  * [Drag and Drop](#drag-and-drop)
  * [Text](#text)
  * [Image / Audio / Video](#image--audio--video)
  * [PDF](#pdf)
  * [Icon Font](#icon-font)
  * [Image Comparison](#image-comparison)
  * [Code Diff](#code-diff)
  * [Calendar](#calendar)
  * [Notebooks](#notebooks)
  * [Animation Effects](#animation-effects)
  * [i18n](#i18n)
  * [React](#react)
  * [Vue.js](#vuejs)
  * [Advanced Interactivity](#advanced-interactivity)
* [Visualization](#visualization)
  * [General-Purpose](#general-purpose)
  * [Scatterplot](#scatterplot)
  * [Parallel Coordinates](#parallel-coordinates)
  * [Time Series](#time-series)
  * [Tree and Hierarchical Data](#tree-and-hierarchical-data)
  * [Network and Graph Data](#network-and-graph-data)
  * [Categorical Data](#categorical-data)
  * [Diagrams](#diagrams)
  * [Heatmap](#heatmap)
  * [Maps and Spatial Data](#maps-and-spatial-data)
  * [Sparkline](#sparkline)
  * [Word Cloud](#word-cloud)
  * [Biological Data](#biological-data)
  * [Chemical Data](#chemical-data)
  * [WebGL](#webgl)
  * [Augmented and Virtual Reality](#augmented-and-virtual-reality)
* [Frameworks](#frameworks)
  * [Foundational frameworks](#foundational-frameworks)
  * [Scaffolding](#scaffolding)
  * [Framework extensions](#framework-extensions)
* [Backend](#backend)
  * [Database](#database)
  * [Persistent Data Storage](#persistent-data-storage)
  * [API Frameworks](#api-frameworks)
  * [URL Routing](#url-routing)
  * [Authentication](#authentication)
  * [Job Scheduling](#job-scheduling)
  * [Web APIs Integration](#web-apis-integration)
  * [Notification Integration](#notification-integration)
  * [Cloud Integration](#cloud-integration)
  * [G Suite Integration](#g-suite-integration)
* [Deploy](#deploy)
  * [Remote Deploy](#remote-deploy)
  * [Desktop Deploy](#desktop-deploy)
  * [Static Server Deploy](#static-server-deploy)
* [Developer Tools](#developer-tools)
  * [Prototyping](#prototyping)
  * [Modularization](#modularization)
  * [Debugging](#debugging)
  * [Testing](#testing)
  * [Profiling](#profiling)
  * [Scaling](#scaling)
  * [Monitoring and Analytics](#monitoring-and-analytics)
* [Miscellaneous](#miscellaneous)
  * [UI Customization](#ui-customization)
  * [Dependency Resolution](#dependency-resolution)
  * [Editor Extensions](#editor-extensions)
  * [Books](#books)
  * [Videos / Screencasts](#videos--screencasts)
* [Shiny for Python](#shiny-for-python)
  * [Python - Theming](#python---theming)
  * [Python - UI Components](#python---ui-components)
  * [Python - Chat](#python---chat)
  * [Python - Table](#python---table)
  * [Python - Frameworks](#python---frameworks)
  * [Python - Deploy](#python---deploy)
  * [Python - Persistent Data Storage](#python---persistent-data-storage)

## Theming

*An awesome Shiny app often looks different from the default Bootstrap theme.*

### Generic Theming

* [shiny.semantic](https://github.com/Appsilon/shiny.semantic) ⭐ 513 | 🐛 40 | 🌐 R | 📅 2025-12-02 - Fomantic UI (formerly Semantic UI) for Shiny.
* [shiny.fluent](https://github.com/Appsilon/shiny.fluent) ⭐ 292 | 🐛 45 | 🌐 R | 📅 2026-08-11 - Fluent UI for Shiny apps.
* [shinymaterial](https://github.com/ericrayanderson/shinymaterial) ⭐ 234 | 🐛 43 | 🌐 R | 📅 2025-12-23 - Material Design for Shiny with Materialize.css.
* [shinythemes](https://github.com/rstudio/shinythemes) ⭐ 160 | 🐛 6 | 🌐 R | 📅 2022-02-25 - Bootswatch themes (Bootstrap 3) for Shiny.
* [fullPage](https://github.com/RinteRface/fullPage) ⭐ 114 | 🐛 9 | 🌐 R | 📅 2021-08-31 - Single page styles for Shiny apps.
* [shinybulma](https://github.com/RinteRface/shinybulma) ⭐ 112 | 🐛 15 | 🌐 R | 📅 2024-07-06 - Bulma.io for Shiny.
* [lcars](https://github.com/leonawicz/lcars) ⭐ 78 | 🐛 0 | 🌐 R | 📅 2025-06-16 - Star Trek aesthetic for Shiny with custom UI components.
* [shiny.tailwind](https://github.com/kylebutts/shiny.tailwind) ⭐ 70 | 🐛 0 | 🌐 R | 📅 2025-03-25 - Tailwind CSS for Shiny apps.
* [argonR](https://github.com/RinteRface/argonR) ⭐ 55 | 🐛 6 | 🌐 SCSS | 📅 2024-01-16 - Argon Bootstrap 4 UI components for Shiny apps.
* [shinyGovstyle](https://github.com/dfe-analytical-services/shinyGovstyle) ⭐ 52 | 🐛 26 | 🌐 R | 📅 2026-08-28 - Custom GOV.UK style inputs for Shiny.
* [shiny.blueprint](https://github.com/Appsilon/shiny.blueprint) ⭐ 48 | 🐛 28 | 🌐 R | 📅 2026-08-26 - Palantir's Blueprint for Shiny apps.
* [shinyNextUI](https://github.com/RinteRface/shinyNextUI) ⭐ 44 | 🐛 6 | 🌐 CSS | 📅 2026-03-19 - NextUI for Shiny.
* [gridlayout](https://github.com/rstudio/gridlayout) ⭐ 44 | 🐛 2 | 🌐 HTML | 📅 2023-10-16 - Build dashboard-style layouts for Shiny and R Markdown using CSS Grid.
* [shinyChakraUI](https://github.com/stla/shinyChakraUI) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-05 - Chakra UI for Shiny.
* [shinyUIkit](https://github.com/RinteRface/shinyUIkit) ⭐ 14 | 🐛 1 | 🌐 R | 📅 2019-07-22 - UIkit API for Shiny.
* [shinyMetroUi](https://github.com/RinteRface/shinyMetroUi) ⭐ 14 | 🐛 0 | 🌐 R | 📅 2019-12-20 - Metro 4 UI for Shiny.
* [flexlayout](https://github.com/the-y-company/flexlayout) ⭐ 11 | 🐛 0 | 🌐 HTML | 📅 2024-09-23 - A responsive three-column layout for Shiny. Creates up-to three-column layout where the left and right columns collapse into offcanvas elements on tablets and mobile devices.
* [muiMaterial](https://github.com/lgnbhl/muiMaterial) ⭐ 7 | 🐛 2 | 🌐 R | 📅 2026-08-27 - Material UI for Shiny apps and Quarto.
* [fomantic.plus](https://github.com/ashbaldry/fomantic.plus) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2022-01-27 - Extra Fomantic UI components for shiny.semantic.
* [shinyds](https://github.com/novica/shinyds) ⭐ 3 | 🐛 2 | 🌐 R | 📅 2026-08-22 - Shiny bindings for the Designsystemet component library.
* [shiny.webawesome](https://github.com/mbanand/shiny.webawesome) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2026-04-23 - Web Awesome component library for Shiny.
* [shinyglass](https://github.com/ericrayanderson/shinyglass) ⭐ 2 | 🐛 1 | 🌐 R | 📅 2026-08-21 - Liquid Glass design themes for Shiny, adding translucent surfaces, backdrop blur, and system typography to Bootstrap components via bslib.
* [calcite](https://r.esri.com/calcite/) - Bindings to the Calcite Design System JavaScript component library.

### Dashboard Theming

* [shinydashboard](https://github.com/rstudio/shinydashboard) ⭐ 927 | 🐛 165 | 🌐 CSS | 📅 2025-04-22 - Shiny dashboarding framework based on AdminLTE 2.
* [flexdashboard](https://github.com/rstudio/flexdashboard) ⭐ 847 | 🐛 84 | 🌐 JavaScript | 📅 2026-06-26 - R Markdown format for flexible dashboards.
* [shinydashboardPlus](https://github.com/RinteRface/shinydashboardPlus) ⭐ 466 | 🐛 50 | 🌐 R | 📅 2025-08-25 - Additional AdminLTE 2 components for shinydashboard.
* [bs4Dash](https://github.com/RinteRface/bs4Dash) ⭐ 458 | 🐛 103 | 🌐 R | 📅 2025-08-25 - Bootstrap 4 Shiny dashboards using AdminLTE 3.
* [semantic.dashboard](https://github.com/Appsilon/semantic.dashboard) ⭐ 256 | 🐛 15 | 🌐 R | 📅 2024-04-18 - Fomantic UI for Shiny dashboards.
* [argonDash](https://github.com/RinteRface/argonDash) ⭐ 143 | 🐛 9 | 🌐 CSS | 📅 2025-04-14 - Bootstrap 4 Argon template for Shiny dashboards.
* [tablerDash](https://github.com/RinteRface/tablerDash) ⭐ 88 | 🐛 12 | 🌐 CSS | 📅 2024-09-26 - Tabler dashboard template for Shiny with Bootstrap 4.
* [gentelellaShiny](https://github.com/RinteRface/gentelellaShiny) ⭐ 12 | 🐛 0 | 🌐 R | 📅 2019-12-20 - Bootstrap 3 Gentelella theme for Shiny dashboards.
* [shidashi](https://github.com/dipterix/shidashi) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2026-08-04 - A Shiny dashboard template system using AdminLTE 3 template.
* [bs4Dashkit](https://github.com/PrigasG/bs4Dashkit) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-08-24 - Branding, theme application, and navigation utilities for bs4Dash dashboards.

### Mobile Theming

* [shinyMobile](https://github.com/RinteRface/shinyMobile) ⭐ 423 | 🐛 71 | 🌐 R | 📅 2026-06-13 - Theming Shiny apps with Framework7, a full featured HTML framework for building iOS & Android apps.
* [miniUI](https://github.com/rstudio/miniUI) ⭐ 108 | 🐛 6 | 🌐 R | 📅 2025-04-17 - Widgets and layouts for Shiny apps working on small screens. Designed for creating Shiny Gadgets.

### Theme Customization

* [bslib](https://github.com/rstudio/bslib) ⭐ 568 | 🐛 205 | 🌐 SCSS | 📅 2026-08-25 - Tools for theming Shiny and R Markdown from R via Bootstrap (3 or 4) Sass.
* [fresh](https://github.com/dreamRs/fresh) ⭐ 232 | 🐛 12 | 🌐 SCSS | 📅 2025-09-04 - Create fresh themes for use in shiny & shinydashboard applications and flexdashboard documents.
* [designer](https://github.com/ashbaldry/designer) ⭐ 154 | 🐛 6 | 🌐 JavaScript | 📅 2026-01-08 - Shiny UI prototype builder allowing drag and drop UI components before saving the equivalent R code.
* [gfonts](https://github.com/dreamRs/gfonts) ⭐ 115 | 🐛 2 | 🌐 R | 📅 2023-01-08 - Offline Google Fonts for Markdown and Shiny.
* [sass](https://github.com/rstudio/sass) ⭐ 103 | 🐛 22 | 🌐 C++ | 📅 2025-06-30 - Compile Sass for dynamic style sheets.
* [linne](https://github.com/JohnCoene/linne) ⭐ 78 | 🐛 0 | 🌐 R | 📅 2022-01-15 - Write CSS in R.
* [Rnightly](https://github.com/feddelegrand7/Rnightly) ⭐ 22 | 🐛 1 | 🌐 R | 📅 2020-12-12 - An R wrapper of the JavaScript library Nightly.
* [cascadess](https://github.com/nteetor/cascadess) ⭐ 18 | 🐛 3 | 🌐 R | 📅 2026-01-22 - Style-pronoun utilities for applying CSS to htmltools and Shiny tags.
* [corazon](https://github.com/feddelegrand7/corazon) ⭐ 3 | 🐛 1 | 🌐 R | 📅 2020-12-10 - Apply colorffy gradients to Shiny elements.

## UI Components

*Frontend UI components for special input/output types.*

### Bootstrap

* [shinyWidgets](https://github.com/dreamRs/shinyWidgets) ⭐ 871 | 🐛 116 | 🌐 R | 📅 2026-07-06 - Bootstrap 3 custom widgets for Shiny (switches, checkboxes, sweet alerts, slider text, knob inputs, select pickers, search bar, dropdown buttons).
* [shinyBS](https://github.com/ebailey78/shinyBS) ⭐ 182 | 🐛 115 | 🌐 R | 📅 2021-01-07 - Bootstrap 3 components for Shiny (alerts, tooltips, popovers, modals, collapsible panels, button upgrades).
* [slickR](https://github.com/yonicd/slickR) ⭐ 162 | 🐛 19 | 🌐 JavaScript | 📅 2025-12-15 - Carousels for Shiny apps using slick.js.
* [bsplus](https://github.com/ijlyttle/bsplus) ⭐ 150 | 🐛 44 | 🌐 R | 📅 2025-04-06 - Bootstrap 3 addons for Shiny and R Markdown (collapsible elements, accordion panels, accordion-sidebar sets, tooltips, popovers, modals, carousels).
* [shinyLP](https://github.com/jasdumas/shinyLP) ⭐ 119 | 🐛 0 | 🌐 R | 📅 2025-05-15 - Bootstrap 3 landing pages for Shiny apps.
* [shinypanels](https://github.com/datasketch/shinypanels) ⭐ 81 | 🐛 13 | 🌐 R | 📅 2024-06-17 - Shiny layout with collapsible panels.
* [bsutils](https://github.com/the-y-company/bsutils) ⭐ 36 | 🐛 0 | 🌐 R | 📅 2024-06-11 - UI utilities for Bootstrap 5 and Shiny.
* [spsComps](https://github.com/lz100/spsComps) ⭐ 34 | 🐛 0 | 🌐 R | 📅 2023-10-07 - Additional Bootstrap 3 custom UI components (gallery, panels, buttons, animation and more) and additional Shiny server components (exception catch, validation, etc.).
* [dockViewR](https://github.com/cynkra/dockViewR) ⭐ 33 | 🐛 24 | 🌐 R | 📅 2026-08-28 - Layout manager widget for R and Shiny apps.
* [litter](https://github.com/devOpifex/litter) ⭐ 31 | 🐛 1 | 🌐 HTML | 📅 2024-04-13 - Lit components for Shiny.
* [dipsaus](https://github.com/dipterix/dipsaus) ⭐ 15 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-05 - Custom Shiny input widgets including styled buttons, compound inputs, file/directory inputs, alerts, and progress indicators.
* [inshiny](https://github.com/nicholasdavies/inshiny) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2026-08-23 - Compact inline widgets for Shiny apps.
* [card.pro](https://github.com/oobianom/card.pro) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2025-02-17 - Lightweight modern and responsive card component for Shiny.
* [glasstabs](https://github.com/PrigasG/glasstabs) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2026-08-24 - Animated glass-style tabs and multi-select filter for Shiny.
* [shinyGizmo](https://cran.r-project.org/package=shinyGizmo) - Custom UI components and input widgets for Shiny applications.
* [gridstackeR](https://cran.r-project.org/package=gridstackeR) - R wrapper for gridstack.js to create draggable and resizable grid layouts.
* [resizableSplitLayout](https://cran.r-project.org/package=resizableSplitLayout) - Resizable split layout module for Shiny.
* [bs4cards](https://cran.r-project.org/package=bs4cards) - Generate Bootstrap 4 cards for Shiny and R Markdown.

### File Input

* [shinyFiles](https://github.com/thomasp85/shinyFiles) ⭐ 206 | 🐛 36 | 🌐 JavaScript | 📅 2023-07-05 - A server-side file system viewer for Shiny.
* [datamods](https://github.com/dreamRs/datamods) ⭐ 155 | 🐛 18 | 🌐 R | 📅 2025-09-25 - Shiny modules to import and manipulate data from various sources.
* [directoryInput](https://github.com/wleepang/shiny-directory-input) ⭐ 49 | 🐛 5 | 🌐 R | 📅 2021-03-03 - Shiny input widget for selecting directories.
* [shinydrive](https://github.com/datastorm-open/shinydrive) ⭐ 13 | 🐛 2 | 🌐 HTML | 📅 2025-12-05 - Shiny module for file sharing between users with admin and user roles.

### Special Input

* [shinyTime](https://github.com/burgerga/shinyTime) ⭐ 31 | 🐛 8 | 🌐 R | 📅 2024-05-08 - A timeInput widget for Shiny.
* [histoslider](https://github.com/cpsievert/histoslider) ⭐ 26 | 🐛 6 | 🌐 R | 📅 2023-11-05 - A histogram slider input binding for Shiny. Supports creating histograms from numeric, date, and date-time vectors.
* [shinySelect](https://github.com/stla/shinySelect) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2022-11-18 - A wrapper of the react-select library that supports grouped, sortable items with Font Awesome icons, KaTeX formulas, and Bootstrap tooltips.
* [shinyMatrix](https://github.com/INWTlab/shinyMatrix) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-05 - Matrix input for Shiny.
* [regexSelect](https://github.com/yonicd/regexSelect) ⭐ 19 | 🐛 1 | 🌐 R | 📅 2017-09-26 - Enable regular expression searches within a Shiny selectize object.
* [shinyMultiActionButton](https://github.com/stla/shinyMultiActionButton) ⭐ 17 | 🐛 1 | 🌐 R | 📅 2020-09-02 - A multi-action button for Shiny.
* [shinyfilter](https://github.com/jsugarelli/shinyfilter) ⭐ 17 | 🐛 3 | 🌐 HTML | 📅 2021-05-10 - Interdependent selectize filters for table columns in Shiny apps.
* [IDEAFilter](https://github.com/Biogen-Inc/IDEAFilter) ⭐ 17 | 🐛 13 | 🌐 R | 📅 2025-07-29 - Agnostic, idiomatic data filter module for Shiny.
* [daterangepicker](https://github.com/trafficonese/daterangepicker) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2023-07-14 - A date-range input widget for Shiny.
* [shinySearchbar](https://github.com/jsdnrs/shiny-searchbar) ⭐ 15 | 🐛 1 | 🌐 R | 📅 2020-06-08 - An input widget for searching and highlighting text in Shiny apps.
* [shinyDatetimePickers](https://github.com/stla/shinyDatetimePickers) ⭐ 14 | 🐛 6 | 🌐 JavaScript | 📅 2024-02-06 - Datetime pickers for Shiny.
* [shinyCleave](https://github.com/carlganz/shinyCleave) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2017-07-05 - Customized text inputs (phone number, ZIP code, currency, credit card) based on Cleave.js.
* [algo](https://github.com/feddelegrand7/algo) ⭐ 11 | 🐛 1 | 🌐 R | 📅 2020-11-24 - Implements the Algolia Places address search auto completion menu on shiny text inputs.
* [codeModules](https://github.com/statistikat/codeModules) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2021-03-18 - Shiny modules to import/manipulate/export tabular data, download plots/tables/widgets, and output code with syntax highlighting using highlight.js.
* [shinyCohortBuilder](https://github.com/r-world-devs/shinyCohortBuilder) ⭐ 10 | 🐛 37 | 🌐 R | 📅 2026-07-10 - Modular cohort-building framework for analytical dashboards.
* [ShinyRatingInput](https://github.com/stefanwilhelm/ShinyRatingInput) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2017-01-08 - Star rating inputs for Shiny based on bootstrap-rating.
* [NestedMenu](https://github.com/stla/NestedMenu) ⭐ 9 | 🐛 2 | 🌐 R | 📅 2022-09-16 - Multi-level dropdown menu selection input.
* [jqbr](https://github.com/hfshr/jqbr) ⭐ 9 | 🐛 2 | 🌐 R | 📅 2025-09-09 - jQuery QueryBuilder input for Shiny, enabling interactive construction of complex filter queries.
* [cascadeSelect](https://github.com/stla/cascadeSelect) ⭐ 8 | 🐛 0 | 🌐 CSS | 📅 2023-06-15 - Cascade select widget for Shiny, useful for selection of hierarchical choices.
* [shinyChakraSlider](https://github.com/stla/shinyChakraSlider) ⭐ 7 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-06 - Combined slider and number input for Shiny.
* [shinyfilters](https://github.com/joshwlivingston/shinyfilters) ⭐ 7 | 🐛 17 | 🌐 R | 📅 2026-05-13 - Create Shiny inputs from vectors, data frames, or any R object.
* [shinyXYpad](https://github.com/stla/shinyXYpad) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2022-09-26 - XY controller input widget for Shiny.
* [shinyquiz](https://github.com/priism-center/shinyquiz) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2025-04-16 - Create interactive quizzes in Shiny apps.
* [shinynlq](https://github.com/Appsilon/shinynlq) ⭐ 3 | 🐛 1 | 🌐 R | 📅 2023-12-15 - Natural language queries (NLQs) for Shiny as a bslib custom component.
* [shiny-highlight-rmarkdown](https://github.com/nanxstats/shiny-highlight-rmarkdown) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2022-02-03 - R code and R Markdown code output syntax highlighting using highlight.js.
* [shinyKnobs](https://github.com/cotepat/shinyKnobs) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2020-01-07 - A collection of knob inputs for Shiny.
* [DateTimeRangePicker](https://github.com/stla/DateTimeRangePicker) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-09-02 - A datetime range picker widget for Shiny.
* [multiActionButton](https://github.com/stla/multiActionButton) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2022-06-20 - Multi-action button for Shiny applications.
* [shinypanel](https://github.com/alexvpickering/shinypanel) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2022-03-25 - Shiny inputs with inline buttons, tooltips, and validation styling.
* [reactCheckbox](https://github.com/stla/reactCheckbox) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-03-01 - Checkbox group input for Shiny, with a head checkbox allowing to check or uncheck all the checkboxes in the group.
* [vfinputs](https://github.com/rhenkin/vfinputs) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2020-10-19 - Visual filter inputs for Shiny.
* [shinyDTC](https://github.com/sigbertklinke/shinyDTC) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2025-01-04 - Dynamic timer control widget for Shiny.
* [picClip](https://github.com/deppemj/picClip) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2023-11-27 - Paste box input for Shiny, allowing users to paste images from the clipboard.
* [shinycroneditor](https://github.com/DatalabFabriek/shinycroneditor) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2024-09-23 - Cron expression input widget for Shiny apps.
* [rquiz](https://github.com/saskiaotto/rquiz) ⭐ 0 | 🐛 2 | 🌐 HTML | 📅 2026-04-28 - Interactive quiz widgets for Shiny, R Markdown, and Quarto.
* [sillysplines](https://github.com/janithwanni/sillysplines) ⭐ 0 | 🐛 2 | 🌐 R | 📅 2026-07-17 - Draw linear splines to define classification decision boundaries and generate synthetic 2D datasets.
* [shinyRadioMatrix](https://cran.r-project.org/package=shinyRadioMatrix) - Matrix of radio buttons input widget for Shiny, useful for Likert-scale and survey-style inputs.
* [shinyRatings](https://cran.r-project.org/package=shinyRatings) - Star rating input for Shiny apps.
* [shinyQueryBuilder](https://cran.r-project.org/package=shinyQueryBuilder) - Construct complex filtering queries in Shiny.
* [scoutbaR](https://cran.r-project.org/package=scoutbaR) - A spotlight React widget for Shiny apps, providing a command palette UI.
* [shinyTimer](https://cran.r-project.org/package=shinyTimer) - Customizable timer widget for Shiny applications.

### Loader

* [waiter](https://github.com/JohnCoene/waiter) ⭐ 495 | 🐛 35 | 🌐 JavaScript | 📅 2026-08-17 - Splash loading screens for Shiny.
* [shinycssloaders](https://github.com/daattali/shinycssloaders) ⭐ 422 | 🐛 3 | 🌐 CSS | 📅 2025-08-14 - CSS loader animations for Shiny outputs.
* [shinybusy](https://github.com/dreamRs/shinybusy) ⭐ 146 | 🐛 12 | 🌐 R | 📅 2024-09-17 - Minimal busy indicator for Shiny apps.
* [shinycustomloader](https://github.com/emitanaka/shinycustomloader) ⭐ 121 | 🐛 8 | 🌐 R | 📅 2018-07-17 - Custom css/html or gif/image loaders for Shiny outputs.
* [sever](https://github.com/JohnCoene/sever) ⭐ 80 | 🐛 8 | 🌐 R | 📅 2024-03-17 - Customize Shiny's disconnected screen.
* [shinydisconnect](https://github.com/daattali/shinydisconnect) ⭐ 71 | 🐛 5 | 🌐 R | 📅 2024-08-18 - Show a nice message when a Shiny app disconnects or errors.
* [shiny.emptystate](https://github.com/Appsilon/shiny.emptystate) ⭐ 28 | 🐛 6 | 🌐 R | 📅 2024-05-21 - Empty state components for Shiny.
* [shiny-loading-skeleton](https://github.com/nanxstats/shiny-loading-skeleton) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2022-04-25 - Shiny app template with an animated, fully customizable skeleton loader.
* [standby](https://github.com/rsquaredacademy/standby) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-31 - Alerts, notifications, and loading screens for Shiny.
* [shiny-fcp-loader](https://github.com/nanxstats/shiny-fcp-loader) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2023-01-28 - Shiny app template with a loading screen that aims to minimize the time to First Contentful Paint (FCP).

### Feedback / Alert / Notification

* [shinyalert](https://github.com/daattali/shinyalert) ⭐ 245 | 🐛 5 | 🌐 R | 📅 2024-06-02 - Create pretty popup messages (modals) in Shiny apps.
* [shinyFeedback](https://github.com/merlinoa/shinyFeedback) ⭐ 193 | 🐛 13 | 🌐 R | 📅 2023-01-31 - Display user feedback next to Shiny inputs.
* [shinyvalidate](https://github.com/rstudio/shinyvalidate) ⭐ 116 | 🐛 30 | 🌐 JavaScript | 📅 2023-10-05 - Add input validation capabilities to Shiny.
* [shinytoastr](https://github.com/MangoTheCat/shinytoastr) ⭐ 96 | 🐛 0 | 🌐 R | 📅 2016-08-29 - Notifications for Shiny apps, via toastr.
* [shinypop](https://github.com/dreamRs/shinypop) ⭐ 53 | 🐛 2 | 🌐 JavaScript | 📅 2021-10-14 - Collection of notifications, confirm dialogs, and alerts for Shiny apps based on noty, notie, push.js, and notiflix.
* [awn](https://github.com/JohnCoene/awn) ⭐ 26 | 🐛 1 | 🌐 R | 📅 2025-08-19 - Awesome Notifications for Shiny.
* [shinyToastify](https://github.com/stla/shinyToastify) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-31 - A wrapper of the React-Toastify library for Shiny.
* [micromodal](https://github.com/kennedymwavu/micromodal) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2026-07-09 - Simple modal dialogs for Shiny based on Micromodal.js.

### Walkthrough / Tooltip / Help

* [cicerone](https://github.com/JohnCoene/cicerone) ⚠️ Archived - Create guided tours for Shiny apps using driver.js.
* [rintrojs](https://github.com/carlganz/rintrojs) ⭐ 137 | 🐛 20 | 🌐 R | 📅 2024-01-11 - Wrapper for Intro.js to create step-by-step introductions and clickable hints.
* [shinyhelper](https://github.com/cwthom/shinyhelper) ⭐ 116 | 🐛 14 | 🌐 R | 📅 2022-10-05 - Add Markdown help files to Shiny app elements.
* [tippy](https://github.com/JohnCoene/tippy) ⭐ 76 | 🐛 16 | 🌐 R | 📅 2023-04-13 - Wrapper for Tippy.js to add tooltips to R Markdown documents or Shiny apps.
* [conductor](https://github.com/etiennebacher/conductor) ⭐ 41 | 🐛 5 | 🌐 R | 📅 2026-08-17 - Create guided tours in Shiny apps using Shepherd.js.
* [prompter](https://github.com/etiennebacher/prompter) ⭐ 40 | 🐛 0 | 🌐 R | 📅 2025-07-02 - Add tooltips in Shiny apps with 'hint.css'.
* [flashCard](https://github.com/jienagu/flashCard) ⭐ 36 | 🐛 1 | 🌐 R | 📅 2022-01-10 - HTML widget for creating flippable flash cards.
* [faq](https://github.com/jienagu/faq) ⭐ 31 | 🐛 1 | 🌐 R | 📅 2023-03-06 - Accordion-based FAQ component with expand/collapse control.
* [scrollrevealR](https://github.com/feddelegrand7/scrollrevealR) ⭐ 22 | 🐛 0 | 🌐 R | 📅 2020-12-09 - Animate shiny elements when they scroll into view using the scrollrevealjs library.

### Clipboard

* [rclipboard](https://github.com/sbihorel/rclipboard) ⭐ 51 | 🐛 0 | 🌐 R | 📅 2023-11-15 - Wrapper for clipboard.js to create copy-to-clipboard buttons for Shiny apps.

### Color Picker

* [colourpicker](https://github.com/daattali/colourpicker) ⭐ 227 | 🐛 4 | 🌐 JavaScript | 📅 2024-08-18 - A colour picker tool for Shiny.
* [gradientInput](https://github.com/daattali/shiny-colour-gradient-input) ⭐ 6 | 🐛 1 | 🌐 R | 📅 2019-11-20 - Another approach at gradient colour picker, implemented using the `colourpicker` package.
* [gradientPickerD3](https://github.com/peikert/gradientPickerD3) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-11 - Interactive color gradient picker based on jquery-gradient-picker.

### Editor

* [DataEditR](https://github.com/DillonHammill/DataEditR) ⭐ 389 | 🐛 20 | 🌐 HTML | 📅 2026-03-14 - Interactive data editor for Shiny with modules for editing, filtering, and syncing data.
* [shinyAce](https://github.com/trestletech/shinyAce) ⭐ 227 | 🐛 14 | 🌐 R | 📅 2025-02-02 - Ace code editor bindings for Shiny.
* [sqlquery](https://github.com/dreamRs/sqlquery) ⭐ 29 | 🐛 2 | 🌐 JavaScript | 📅 2018-05-09 - HTML widget for writing SQL queries with autocompletion for SQL keywords and table/field names.
* [shinyMCE](https://github.com/mul118/shinyMCE) ⭐ 19 | 🐛 5 | 🌐 HTML | 📅 2021-09-19 - TinyMCE WYSIWYG editor bindings for Shiny.
* [shinyMonacoEditor](https://github.com/stla/shinyMonacoEditor) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-21 - The Monaco Editor in Shiny.
* [findInFiles](https://github.com/stla/findInFiles) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2024-04-28 - Search files and display grep results in an HTML widget with Shiny bindings.
* [monaco](https://github.com/stla/monaco) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2022-05-18 - The Monaco Editor as an HTML widget.
* [aceEditor](https://github.com/stla/aceEditor) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2021-03-06 - Ace editor as an HTML widget based on react-ace.
* [markdownInput](https://github.com/juliendiot42/markdownInput) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2020-02-04 - Shiny module for a Markdown input with live result preview.
* [shinyNotes](https://github.com/danielkovtun/shinyNotes) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2023-02-19 - Shiny module for taking free-form notes.
* [highlighter](https://github.com/federiva/highlighter) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2024-03-07 - Prism.js syntax highlighting for code snippets and complete files.
* [shinyEditor](https://github.com/zearoby/shinyEditor) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2026-03-27 - Ace and Monaco editor bindings for Shiny applications.

### Chat

* [gptstudio](https://github.com/MichelNivard/gptstudio) ⭐ 993 | 🐛 10 | 🌐 R | 📅 2026-01-03 - Incorporate use of large language models (LLMs) into project workflows, with Shiny bindings for streamingMessage components.
* [chattr](https://github.com/mlverse/chattr) ⭐ 249 | 🐛 24 | 🌐 R | 📅 2025-11-11 - Interact with large language models (LLMs) in RStudio through the R console or Shiny gadget.
* [querychat](https://github.com/posit-dev/querychat) ⭐ 211 | 🐛 27 | 🌐 Python | 📅 2026-08-27 - Filter and query data frames in Shiny using an LLM chat interface.
* [shinychat](https://github.com/posit-dev/shinychat) ⭐ 137 | 🐛 55 | 🌐 TypeScript | 📅 2026-08-28 - Chat UI component for Shiny.
* [shinyChatR](https://github.com/julianschmocker/shinyChatR) ⭐ 26 | 🐛 1 | 🌐 R | 📅 2024-05-25 - Reusable chat module for Shiny apps. Allows sending messages and view messages from other users. Messages can be stored in a database or a `.rds` file.
* [shiny.ollama](https://github.com/ineelhere/shiny.ollama) ⭐ 22 | 🐛 0 | 🌐 R | 📅 2025-03-12 - Shiny interface for chatting with large language models offline using Ollama.
* [LLMR.shiny](https://github.com/asanaei/LLMR.shiny) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-08-04 - Shiny modules for LLM-powered GUIs, including provider and model selection, API-key handling, session cost tracking, and error and report displays.

### Table

* [gt](https://github.com/rstudio/gt) ⭐ 2,161 | 🐛 313 | 🌐 R | 📅 2026-08-26 - Generate information-rich, publication-quality tables.
* [gtsummary](https://github.com/ddsjoberg/gtsummary) ⭐ 1,208 | 🐛 17 | 🌐 R | 📅 2026-08-26 - Presentation-ready data summary and analytic result tables.
* [kableExtra](https://github.com/haozhu233/kableExtra) ⭐ 736 | 🐛 147 | 🌐 R | 📅 2026-07-04 - Construct complex table with `knitr::kable()` and pipes.
* [formattable](https://github.com/renkun-ken/formattable) ⭐ 700 | 🐛 66 | 🌐 HTML | 📅 2026-08-08 - Table elements formatting and styling for R Markdown documents and Shiny apps.
* [reactable](https://github.com/glin/reactable) ⭐ 677 | 🐛 162 | 🌐 JavaScript | 📅 2026-06-16 - Interactive data tables for R, based on the React Table library and made with reactR.
* [flextable](https://github.com/davidgohel/flextable) ⭐ 626 | 🐛 10 | 🌐 R | 📅 2026-08-05 - Create tables for reporting with format and layout control.
* [DT](https://github.com/rstudio/DT) ⭐ 622 | 🐛 207 | 🌐 JavaScript | 📅 2026-05-18 - R interface to the DataTables library.
* [rhandsontable](https://github.com/jrowen/rhandsontable) ⭐ 389 | 🐛 166 | 🌐 HTML | 📅 2024-07-23 - Create Excel-like editable tables in Shiny apps.
* [gtExtras](https://github.com/jthomasmock/gtExtras) ⭐ 223 | 🐛 28 | 🌐 R | 📅 2026-01-16 - Extending gt for beautiful HTML tables.
* [reactablefmtr](https://github.com/kcuilla/reactablefmtr) ⭐ 214 | 🐛 40 | 🌐 R | 📅 2024-03-16 - Simplify the styling, formatting, and customization of tables made with reactable.
* [excelR](https://github.com/Swechhya/excelR) ⭐ 154 | 🐛 31 | 🌐 JavaScript | 📅 2023-07-12 - R interface to the jExcel.js library.
* [DTedit](https://github.com/jbryer/DTedit) ⭐ 129 | 🐛 2 | 🌐 R | 📅 2024-07-09 - Editable DataTables for Shiny apps.
* [pivottabler](https://github.com/cbailiss/pivottabler) ⭐ 124 | 🐛 16 | 🌐 R | 📅 2025-08-14 - Create pivot tables in R.
* [toastui](https://github.com/dreamRs/toastui) ⭐ 94 | 🐛 14 | 🌐 R | 📅 2025-04-10 - Interactive tables, calendars, and charts based on the TOAST UI JavaScript library.
* [htmlTable](https://github.com/gforge/htmlTable) ⭐ 79 | 🐛 2 | 🌐 R | 📅 2026-04-22 - Advanced HTML tables with Shiny output and render bindings.
* [tangram](https://github.com/spgarbet/tangram) ⭐ 68 | 🐛 15 | 🌐 R | 📅 2023-02-09 - Formula grammar for creating tables.
* [texPreview](https://github.com/yonicd/texPreview) ⭐ 53 | 🐛 3 | 🌐 R | 📅 2024-01-24 - Preview and save images of rendered snippets of LaTeX in RStudio viewer, R Markdown and Shiny.
* [reactable.extras](https://github.com/Appsilon/reactable.extras) ⭐ 49 | 🐛 24 | 🌐 R | 📅 2025-02-10 - Enhanced functionality for reactable in Shiny applications, with interactive and dynamic data table capabilities.
* [cheetahR](https://github.com/cynkra/cheetahR) ⭐ 39 | 🐛 4 | 🌐 R | 📅 2026-06-11 - High-performance Cheetah Grid htmlwidget for large interactive tables.
* [basictabler](https://github.com/cbailiss/basictabler) ⭐ 36 | 🐛 1 | 🌐 R | 📅 2025-04-26 - Construct rich tables for output to HTML/Excel.
* [RagGrid](https://github.com/no-types/RagGrid) ⭐ 33 | 🐛 19 | 🌐 CSS | 📅 2023-03-01 - AG Grid htmlwidget for interactive tables in R Markdown and Shiny.
* [editbl](https://github.com/openanalytics/editbl) ⭐ 31 | 🐛 2 | 🌐 R | 📅 2026-08-05 - DT (DataTables) extension to support interactive editing. Easily supports databases.
* [pivta](https://github.com/feddelegrand7/pivta) ⭐ 28 | 🐛 1 | 🌐 CSS | 📅 2020-12-09 - R wrapper for WebDataRocks, an interactive pivot table component for data analysis.
* [xSpreadsheet](https://github.com/MichaelHogers/xSpreadsheet) ⭐ 27 | 🐛 9 | 🌐 R | 📅 2023-07-16 - R wrapper for the JavaScript canvas spreadsheet library x-spreadsheet.
* [condformat](https://github.com/zeehio/condformat) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2026-07-10 - Conditional formatting for data frames.
* [dteditmod](https://github.com/DavidPatShuiFong/DTedit) ⭐ 21 | 🐛 4 | 🌐 R | 📅 2022-11-04 - A fork of DTedit with a modular implementation and more [documentation](https://rpubs.com/DavidFong/DTedit).
* [tableHTML](https://github.com/LyzandeR/tableHTML) ⭐ 20 | 🐛 10 | 🌐 R | 📅 2025-11-28 - Create and style HTML tables with CSS, with Shiny rendering functions.
* [dataviewR](https://github.com/madhankumarnagaraji/dataviewR) ⭐ 19 | 🐛 11 | 🌐 R | 📅 2026-08-27 - Interactive data frame viewer with filtering, column selection, and code generation.
* [rtabulator](https://github.com/eoda-dev/rtabulator) ⭐ 10 | 🐛 22 | 🌐 R | 📅 2024-11-14 - R bindings for the Tabulator JS library for interactive tables.
* [dtsmartr](https://github.com/wagh-nikhil/dtsmartr) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-17 - Interactive virtualized data explorer grid htmlwidget with column-type detection, multi-value filtering, sorting, and virtual scrolling.
* [DT2](https://github.com/StrategicProjects/DT2) ⭐ 9 | 🐛 1 | 🌐 R | 📅 2026-06-29 - DataTables 2.x htmlwidget with Shiny rendering, proxy, and event helpers.
* [perspectiveR](https://github.com/EydlinIlya/perspectiveR) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-14 - Perspective htmlwidget for interactive pivot tables and browser-side analytics, with Shiny proxy support.
* [ViewR](https://github.com/itsmdivakaran/viewR) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-06-03 - Interactive data table and data explorer with a virtualized grid, spark histograms, hover metadata, visual query builder, and code generation.
* [datasetviewer](https://github.com/vthanik/datasetviewer) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23 - SAS Studio style dataset viewer with browser-side filtering, sorting, metadata inspection, CSV export, and DuckDB-WASM queries.
* [shinydataviewer](https://github.com/Ryan-W-Harrison/shinydataviewer) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-08-05 - Reusable data viewer module for Shiny.
* [nestable](https://github.com/derekunderwood/nestable) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-06-16 - Collapsible hierarchical HTML tables with Shiny bindings.
* [muiDataGrid](https://github.com/lgnbhl/muiDataGrid) ⭐ 0 | 🐛 1 | 🌐 R | 📅 2026-07-19 - MUI X Data Grid for Shiny apps and Quarto, a fast and extensible React data table with filtering, sorting, and pagination.
* [QuickExplore](https://github.com/ramsas88/QuickExplore) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-08-01 - Shiny modules for browsing, filtering, summarizing, and converting tabular datasets.
* [shinypivottabler](https://cran.r-project.org/package=shinypivottabler) - Shiny module to create interactive pivot tables.

### Drawers

* [pushbar](https://github.com/JohnCoene/pushbar) ⭐ 60 | 🐛 1 | 🌐 R | 📅 2022-11-09 - Brings pushbar.js to Shiny. Create off-canvas sliding drawers for inputs, outputs, or any other content.

### Drag and Drop

* [esquisse](https://github.com/dreamRs/esquisse) ⭐ 1,859 | 🐛 53 | 🌐 R | 📅 2025-02-21 - Drag and drop inputs and visual builder for ggplot2.
* [sortable](https://github.com/rstudio/sortable) ⭐ 136 | 🐛 20 | 🌐 R | 📅 2026-02-18 - HTML widget for SortableJS that enables drag-and-drop behavior and reorderable elements.
* [shinyDND](https://github.com/ayayron/shinydnd) ⭐ 93 | 🐛 5 | 🌐 R | 📅 2017-09-24 - Create drag and drop elements in Shiny.
* [dragulaR](https://github.com/zzawadz/dragulaR) ⭐ 62 | 🐛 0 | 🌐 R | 📅 2026-01-17 - R interface for the dragula JavaScript library for moving around elements in Shiny apps.
* [shinykanban](https://github.com/ugurdar/shinykanban) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-04 - Interactive Kanban board with drag-and-drop interface for Shiny.
* [dndselectr](https://github.com/serenity-r/dndselectr) ⭐ 4 | 🐛 5 | 🌐 R | 📅 2021-03-02 - Drag-and-drop Shiny select input.

### Text

* [equatiomatic](https://github.com/datalorax/equatiomatic) ⭐ 626 | 🐛 26 | 🌐 R | 📅 2026-08-19 - Transform fitted statistical models into LaTeX equations, with Shiny output and render bindings.
* [epoxy](https://github.com/gadenbuie/epoxy) ⭐ 217 | 🐛 10 | 🌐 R | 📅 2026-08-07 - Data-driven string interpolation helpers for Shiny UI and rendered HTML text.
* [marker](https://github.com/JohnCoene/marker) ⭐ 55 | 🐛 5 | 🌐 R | 📅 2023-03-14 - Highlight text in Shiny with markjs.
* [circletyper](https://github.com/etiennebacher/circletyper) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2022-09-21 - Curve text elements in Shiny using CircleType.js.

### Image / Audio / Video

* [shinysense](https://github.com/nstrayer/shinysense) ⭐ 205 | 🐛 19 | 🌐 JavaScript | 📅 2019-10-15 - A series of shiny modules to help Shiny sense the world around it (draw, swipe cards, record images from a webcam, record audio, capture accelerometer data).
* [shinyscreenshot](https://github.com/daattali/shinyscreenshot) ⭐ 72 | 🐛 4 | 🌐 R | 📅 2024-10-27 - Capture screenshots of entire pages or parts of pages in Shiny apps.
* [vembedr](https://github.com/ijlyttle/vembedr) ⭐ 58 | 🐛 10 | 🌐 HTML | 📅 2021-12-11 - Embed videos in R Markdown documents and Shiny apps.
* [fabricerin](https://github.com/feddelegrand7/fabricerin) ⭐ 55 | 🐛 3 | 🌐 R | 📅 2021-02-01 - Create HTML5 canvas in Shiny and R Markdown documents based on Fabric.js.
* [pixels](https://github.com/javierluraschi/pixels) ⭐ 30 | 🐛 7 | 🌐 R | 📅 2020-12-03 - HTML widget and Shiny Gadget to render and draw pixels.
* [heyshiny](https://github.com/jcrodriguez1989/heyshiny) ⭐ 29 | 🐛 0 | 🌐 R | 📅 2020-02-16 - Speech to text input.
* [recogito](https://github.com/DIGI-VUB/recogito) ⭐ 23 | 🐛 6 | 🌐 JavaScript | 📅 2022-08-18 - Text and image annotation.
* [howler](https://github.com/ashbaldry/howler) ⭐ 17 | 🐛 1 | 🌐 R | 📅 2025-05-26 - Shiny extension for howler.js to add audio playback controls.
* [drawer](https://github.com/lz100/drawer) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2023-07-05 - A front-end only image editor for both Shiny and R Markdown.
* [swipeR](https://github.com/stla/swipeR) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2023-10-11 - Carousels using the JavaScript library Swiper.
* [webcamR](https://github.com/ginberg/webcamR) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2019-01-31 - HTML widget wrapper around the react-webcam library.
* [video](https://github.com/ashbaldry/video) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-02-02 - Shiny extension for video.js to embed customizable HTML5 video players.
* [rintimg](https://github.com/feddelegrand7/rintimg) ⭐ 5 | 🐛 1 | 🌐 R | 📅 2025-04-07 - View an image in full screen by clicking on it.
* [annotator](https://github.com/valcu/annotator) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2025-09-22 - Image annotation and polygon outlining htmlwidget using free drawing.
* [freewall](https://github.com/stla/freewall) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-28 - Dynamic image grid layouts for Shiny and R Markdown.

### PDF

* [rpdf](https://github.com/yonicd/rpdf) ⭐ 42 | 🐛 2 | 🌐 JavaScript | 📅 2018-06-20 - Mozilla pdf.js htmlwidget for R.

### Icon Font

* [fontawesome](https://github.com/rstudio/fontawesome) ⭐ 300 | 🐛 9 | 🌐 R | 📅 2025-10-05 - Insert FontAwesome icons into R Markdown documents and Shiny apps.
* [icongram](https://github.com/r4fun/icongram) ⭐ 33 | 🐛 0 | 🌐 R | 📅 2020-08-18 - Interface to Icongram, easily fetch svg icons with a single function.
* [phosphoricons](https://github.com/dreamRs/phosphoricons) ⭐ 31 | 🐛 0 | 🌐 R | 📅 2024-09-17 - Phosphor icon set for Shiny and R Markdown.
* [bsicons](https://github.com/rstudio/bsicons) ⭐ 17 | 🐛 5 | 🌐 R | 📅 2025-12-30 - Bootstrap Icons helpers for Shiny, R Markdown, and htmltools.
* [lucidr](https://github.com/hyperverse-r/lucidr) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-03-10 - Lucide SVG icons for R.
* [rheroicons](https://cran.r-project.org/package=rheroicons) - A zero-dependency SVG icon library implementing the Heroicons set for Shiny.

### Image Comparison

* [vdiffr](https://github.com/r-lib/vdiffr) ⭐ 198 | 🐛 13 | 🌐 C++ | 📅 2026-02-13 - Visual regression testing and graphical diffing, with toggle, slide, and diff widgets for comparing two images.
* [slideview](https://github.com/r-spatial/slideview) ⭐ 25 | 🐛 3 | 🌐 R | 📅 2025-08-21 - Slider-based htmlwidget for comparing raster images side by side.

### Code Diff

* [diffr](https://github.com/muschellij2/diffr) ⭐ 67 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-01 - Create code diff widgets based on codediff.js.
* [diffviewer](https://github.com/r-lib/diffviewer) ⭐ 66 | 🐛 9 | 🌐 JavaScript | 📅 2024-06-12 - HTML widget to visually compare files (text, images, and data frames).
* [jsondiff](https://github.com/bergant/jsondiff) ⭐ 10 | 🐛 0 | 🌐 R | 📅 2017-10-05 - R interface to jsondiffpatch for comparing R objects as JSONs.
* [diffRgit](https://github.com/abossi/diffRgit) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2017-03-20 - Create an HTML Git diff widget using the diff2html library.

### Calendar

* [tuicalendr](https://github.com/dreamRs/tuicalendr) ⚠️ Archived - HTML widget to create interactive calendars with JavaScript library tui-calendar.

### Notebooks

* [robservable](https://github.com/juba/robservable) ⭐ 167 | 🐛 7 | 🌐 HTML | 📅 2026-08-05 - [Observable](https://observablehq.com/) notebooks as R htmlwidgets.

### Animation Effects

* [countdown](https://github.com/gadenbuie/countdown) ⭐ 157 | 🐛 10 | 🌐 JavaScript | 📅 2026-02-14 - A countdown timer for Shiny apps, R Markdown, and Quarto.
* [shinyglide](https://github.com/juba/shinyglide) ⭐ 93 | 🐛 4 | 🌐 R | 📅 2026-08-05 - Create carousel-like or assistant-like (wizard) UI components with Glide.js.
* [d3rain](https://github.com/daranzolin/d3rain) ⭐ 78 | 🐛 0 | 🌐 R | 📅 2019-07-15 - HTML widget bringing D3 drip to R.
* [shinyEffects](https://github.com/RinteRface/shinyEffects) ⭐ 52 | 🐛 0 | 🌐 R | 📅 2021-11-18 - Customize shiny apps with CSS effects (Zoom / Pulse / Shadow / Shake).
* [countup](https://github.com/JohnCoene/countup) ⭐ 41 | 🐛 0 | 🌐 CSS | 📅 2025-01-18 - R htmlwidget that animates a numerical value by counting to it with CountUp.js.
* [shinyanimate](https://github.com/Swechhya/shinyanimate) ⭐ 39 | 🐛 4 | 🌐 R | 📅 2024-02-12 - Animation for Shiny elements using Animate.css.
* [flipdownr](https://github.com/feddelegrand7/flipdownr) ⭐ 29 | 🐛 0 | 🌐 R | 📅 2021-01-23 - Flipdown.js countdown component for R Markdown documents and Shiny apps.
* [vov](https://github.com/tylerlittlefield/vov) ⭐ 23 | 🐛 0 | 🌐 R | 📅 2020-09-01 - CSS animations for Shiny elements.
* [typedjs](https://github.com/JohnCoene/typedjs) ⭐ 15 | 🐛 0 | 🌐 R | 📅 2021-12-12 - R htmlwidget for animated typing effect with typed.js.
* [hover](https://github.com/r4fun/hover) ⭐ 15 | 🐛 0 | 🌐 R | 📅 2021-03-19 - Add animations to Shiny button elements using Hover.css.
* [bubblyr](https://github.com/feddelegrand7/bubblyr) ⭐ 15 | 🐛 0 | 🌐 R | 📅 2020-12-12 - Add animated bubbles to Shiny and R Markdown backgrounds.
* [textillate](https://github.com/JohnCoene/textillate) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2020-04-18 - CSS3 text animations with textillate.js.
* [aos](https://github.com/lgnbhl/aos) ⭐ 8 | 🐛 1 | 🌐 R | 📅 2024-09-16 - Apply scroll-triggered animations to Shiny and R Markdown elements using the AOS (Animate On Scroll) library.
* [GomoGomonoMi](https://github.com/feddelegrand7/GomoGomonoMi) ⭐ 8 | 🐛 1 | 🌐 R | 📅 2020-12-10 - Animate Shiny and R Markdown text using Animate.css.
* [r2fireworks](https://github.com/oobianom/r2fireworks) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2024-01-17 - Add fireworks celebration effects to Shiny apps and R Markdown.
* [shinyLottie](https://github.com/camhowitt/shinyLottie) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2024-06-21 - Seamlessly integrate Lottie animations into Shiny applications.
* [aniview](https://github.com/lgnbhl/aniview) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2024-09-12 - Animate Shiny and R Markdown elements when they scroll into view, powered by AniView and Animate.css.
* [spoiler](https://github.com/etiennebacher/spoiler) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2021-06-26 - Blur HTML elements in Shiny applications using Spoiler-Alert.js.
* [animejs](https://github.com/long39ng/animejs) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2026-08-21 - Low-level htmlwidget bindings to Anime.js for browser-native SVG and HTML animations.
* [flipdownWidgets](https://github.com/fanggong/flipdownWidgets) ⭐ 0 | 🐛 1 | 🌐 R | 📅 2021-07-01 - Flipdown.js countdown htmlwidget with Shiny bindings.

### i18n

* [shiny.i18n](https://github.com/Appsilon/shiny.i18n) ⭐ 173 | 🐛 30 | 🌐 R | 📅 2026-07-01 - Easy internationalization of Shiny apps.
* [shi18ny](https://github.com/datasketch/shi18ny) ⭐ 22 | 🐛 12 | 🌐 R | 📅 2021-06-10 - Tools for shiny apps internationalization.

### React

* [reactR](https://github.com/react-R/reactR) ⭐ 418 | 🐛 14 | 🌐 JavaScript | 📅 2025-06-23 - Use React in R with htmlwidget constructor templates and local JavaScript dependencies.
* [shiny.react](https://github.com/Appsilon/shiny.react) ⭐ 102 | 🐛 20 | 🌐 JavaScript | 📅 2024-05-20 - Tools for using React in Shiny.
* [shinyReactWidgets](https://github.com/pvictor/shinyReactWidgets) ⭐ 19 | 🐛 1 | 🌐 R | 📅 2019-03-18 - React widgets for Shiny apps.
* [reactRouter](https://github.com/lgnbhl/reactRouter) ⭐ 14 | 🐛 1 | 🌐 R | 📅 2026-08-15 - React Router for Shiny apps and Quarto.

### Vue.js

* [vueR](https://github.com/vue-r/vueR) ⭐ 145 | 🐛 7 | 🌐 R | 📅 2024-07-26 - Use Vue.js in R with htmlwidget constructor templates and local JavaScript dependencies.
* [vuer](https://github.com/ramnathv/vuer) ⭐ 41 | 🐛 0 | 🌐 R | 📅 2019-09-19 - Use Vue components and build Vue apps in R.

### Advanced Interactivity

* [htmlwidgets](https://github.com/ramnathv/htmlwidgets) ⭐ 798 | 🐛 133 | 🌐 R | 📅 2026-04-22 - A framework for creating R bindings to JavaScript libraries.
* [shinyjs](https://github.com/daattali/shinyjs) ⭐ 751 | 🐛 5 | 🌐 R | 📅 2026-08-11 - Perform common JavaScript operations in Shiny apps.
* [crosstalk](https://github.com/rstudio/crosstalk) ⭐ 300 | 🐛 90 | 🌐 JavaScript | 📅 2025-08-27 - Inter-widget interactivity (for example, linked brushing and filtering) for htmlwidgets.
* [shinyjqui](https://github.com/Yang-Tang/shinyjqui) ⭐ 279 | 🐛 16 | 🌐 R | 📅 2023-12-30 - Add jQuery UI interactions and effects (e.g. draggable, resizable, sortable elements) to Shiny apps.
* [shinymeta](https://github.com/rstudio/shinymeta) ⭐ 228 | 🐛 27 | 🌐 R | 📅 2026-03-02 - Record and expose Shiny app logic using metaprogramming.
* [manipulateWidget](https://github.com/rte-antares-rpackage/manipulateWidget) ⭐ 131 | 🐛 18 | 🌐 R | 📅 2026-01-16 - Add interactivity to htmlwidgets with combine and filter controls for Shiny.
* [shiny.collections](https://github.com/Appsilon/shiny.collections) ⭐ 75 | 🐛 4 | 🌐 R | 📅 2023-12-15 - Google Docs-like live collaboration in Shiny with RethinkDB.
* [js4shiny](https://github.com/gadenbuie/js4shiny) ⭐ 54 | 🐛 2 | 🌐 R | 📅 2024-03-24 - Companion package for 'JavaScript for Shiny Users' workshop, with components to enable using R Markdown for literate programming with JavaScript.
* [keys](https://github.com/r4fun/keys) ⭐ 48 | 🐛 4 | 🌐 R | 📅 2024-05-23 - Assign and listen to keyboard shortcuts in Shiny using the Mousetrap JavaScript library.
* [svgPanZoom](https://github.com/timelyportfolio/svgPanZoom) ⭐ 45 | 🐛 10 | 🌐 R | 📅 2023-04-05 - Add pan and zoom interactivity to SVG graphics as an htmlwidget.
* [shinyCanvas](https://github.com/yonicd/shinyCanvas) ⭐ 24 | 🐛 0 | 🌐 R | 📅 2017-11-17 - Create and customize an interactive canvas using the D3 JavaScript library and the htmlwidgets package.
* [shinyscroll](https://github.com/JohnCoene/shinyscroll) ⭐ 23 | 🐛 1 | 🌐 R | 📅 2020-07-17 - Scroll to an element in Shiny.
* [pagemapR](https://github.com/swsoyee/pagemapR) ⭐ 21 | 🐛 0 | 🌐 R | 📅 2021-08-27 - Create a mini map for Shiny apps and R Markdown documents.
* [bscui](https://github.com/patzaw/bscui) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-23 - Interactive SVG custom interfaces with Shiny bindings and proxy updates.
* [gotop](https://github.com/lgnbhl/gotop) ⭐ 18 | 🐛 1 | 🌐 R | 📅 2024-09-12 - Add a scroll back to top Font Awesome icon to Shiny apps and R Markdown documents using jQuery GoTop.
* [r2resize](https://github.com/oobianom/r2resize) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2025-11-11 - In-text resizable containers for images, tables, and other content in Shiny, R Markdown, and Quarto.
* [flexfilter](https://github.com/the-y-company/flexfilter) ⭐ 13 | 🐛 0 | 🌐 HTML | 📅 2025-01-08 - Create a filter from a data frame that enables users to dynamically add filters on each column. The filter dynamically generates the appropriate input for the selected column based on its type.
* [scroller](https://github.com/lgnbhl/scroller) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2024-09-12 - Smooth scroll to any element in Shiny apps and R Markdown documents using the Arbitrary Anchor jQuery plugin.
* [overshiny](https://github.com/nicholasdavies/overshiny) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2025-09-14 - Draggable and resizable rectangular overlays on Shiny plots.
* [linkeR](https://github.com/EpiForeSITE/linkeR) ⭐ 4 | 🐛 6 | 🌐 R | 📅 2026-04-14 - Link interactive plots and tables in Shiny applications for coordinated views.
* [shinyphaser](https://github.com/maciekbanas/shinyphaser) ⭐ 4 | 🐛 18 | 🌐 R | 📅 2026-08-28 - Interface to the Phaser.js game framework for constructing and managing 2D games in Shiny apps.
* [shinyReports](https://github.com/aes21/shinyReports) ⭐ 2 | 🐛 0 | 🌐 R | 📅 2026-07-02 - Render R Markdown reports to HTML and open them in a new browser tab.

## Visualization

*Frontend components for interactive visualization of specific data types.*

### General-Purpose

* [plotly](https://github.com/plotly/plotly.R) ⭐ 2,676 | 🐛 760 | 🌐 R | 📅 2026-07-25 - Interactive web graphics via plotly.js. Has special support for linking/highlighting/filtering views.
* [ggiraph](https://github.com/davidgohel/ggiraph) ⭐ 877 | 🐛 11 | 🌐 R | 📅 2026-08-14 - HTML widget that makes ggplot2 graphics interactive. Select graphical elements, add tooltips, animations, and JavaScript actions to the graphics.
* [highcharter](https://github.com/jbkunst/highcharter) ⭐ 739 | 🐛 39 | 🌐 R | 📅 2026-04-26 - R wrapper for the highcharts JavaScript charting library.
* [echarts4r](https://github.com/JohnCoene/echarts4r) ⭐ 628 | 🐛 179 | 🌐 R | 📅 2026-06-23 - Interactive graphs with Echarts v4.
* [GWalkR](https://github.com/Kanaries/GWalkR) ⭐ 558 | 🐛 14 | 🌐 TypeScript | 📅 2025-07-03 - Interactive Tableau-like exploratory data analysis htmlwidget for Shiny.
* [r2d3](https://github.com/rstudio/r2d3) ⭐ 528 | 🐛 40 | 🌐 R | 📅 2024-01-09 - R interface to D3 visualizations.
* [googleVis](https://github.com/mages/googleVis) ⭐ 363 | 🐛 33 | 🌐 R | 📅 2025-10-08 - R interface to Google Charts.
* [canvasXpress](https://github.com/neuhausi/canvasXpress) ⭐ 313 | 🐛 27 | 🌐 R | 📅 2026-08-28 - Interactive visualization for scientific and biomedical research using CanvasXpress.
* [rbokeh](https://github.com/bokeh/rbokeh) ⚠️ Archived - R interface for Bokeh.
* [visachartR](https://github.com/visa/visa-chart-components/tree/main/packages/charts-R) ⭐ 187 | 🐛 4 | 🌐 TypeScript | 📅 2026-04-15 - Accessibility-focused htmlwidget wrappers for Visa Chart Components.
* [billboarder](https://github.com/dreamRs/billboarder) ⭐ 177 | 🐛 11 | 🌐 R | 📅 2026-08-06 - HTML widget for billboard.js.
* [vegalite](https://github.com/hrbrmstr/vegalite) ⚠️ Archived - R ggplot2 bindings for Vega-Lite.
* [apexcharter](https://github.com/dreamRs/apexcharter) ⭐ 150 | 🐛 12 | 🌐 R | 📅 2026-08-25 - HTML widget for ApexCharts.js.
* [sketch](https://github.com/kcf-jackson/sketch) ⭐ 126 | 🐛 1 | 🌐 HTML | 📅 2024-02-17 - Creates static / animated / interactive visualizations embeddable in R Markdown documents and Shiny. Implements an R-to-JavaScript transpiler and enables users to write JavaScript applications using the syntax of R.
* [g2r](https://github.com/devOpifex/g2r) ⭐ 122 | 🐛 6 | 🌐 R | 📅 2022-01-15 - Grammar of graphics for interactive visualization using G2.js.
* [echarty](https://github.com/helgasoft/echarty) ⭐ 113 | 🐛 2 | 🌐 R | 📅 2026-08-12 - Minimal Shiny and htmlwidget interface to Apache ECharts.
* [altair](https://github.com/vegawidget/altair) ⭐ 92 | 🐛 3 | 🌐 R | 📅 2024-01-15 - R interface to Altair and Vega-Lite with Shiny-ready vegawidget output bindings.
* [vegawidget](https://github.com/vegawidget/vegawidget) ⭐ 71 | 🐛 21 | 🌐 R | 📅 2024-01-13 - HTML widget renderer for Vega and Vega-Lite.
* [taucharts](https://github.com/hrbrmstr/taucharts) ⭐ 64 | 🐛 22 | 🌐 HTML | 📅 2019-09-07 - HTML widget for Taucharts.
* [ggcube](https://github.com/matthewkling/ggcube) ⭐ 56 | 🐛 2 | 🌐 R | 📅 2026-07-29 - Create layered 3D figures with ggplot2, including drag-to-rotate htmlwidgets with Shiny output bindings.
* [lineupjs](https://github.com/lineupjs/lineup_htmlwidget) ⭐ 55 | 🐛 4 | 🌐 R | 📅 2026-02-28 - LineUp.js htmlwidget for interactive visual analysis of multi-attribute rankings.
* [d3po](https://github.com/pachadotdev/d3po) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-27 - Fast and beautiful interactive visualization for R Markdown and Shiny. Acts as intermediate layer between Shiny and D3 by providing templates.
* [rAmCharts](https://github.com/datastorm-open/rAmCharts) ⭐ 49 | 🐛 16 | 🌐 JavaScript | 📅 2025-01-13 - Interface to the amCharts JavaScript charting library.
* [flourishcharts](https://github.com/canva-public/flourishcharts) ⭐ 48 | 🐛 6 | 🌐 R | 📅 2025-12-18 - Flourish htmlwidget for interactive data storytelling charts.
* [c3](https://github.com/mrjoh3/c3) ⭐ 39 | 🐛 5 | 🌐 R | 📅 2026-08-25 - Interactive C3.js charts for R Markdown and Shiny applications.
* [upsetjs](https://github.com/upsetjs/upsetjs_r) ⭐ 36 | 🐛 7 | 🌐 R | 📅 2023-04-20 - UpSet.js htmlwidget for interactive set intersection visualizations.
* [rAmCharts4](https://github.com/stla/rAmCharts4) ⭐ 28 | 🐛 8 | 🌐 JavaScript | 📅 2023-03-15 - R interface to amCharts 4.
* [AutoPlots](https://github.com/AdrianAntico/AutoPlots) ⭐ 26 | 🐛 0 | 🌐 R | 📅 2026-08-15 - High-level ECharts visualization helpers for common chart types and model evaluation plots.
* [rfrappe](https://github.com/merlinoa/rfrappe) ⭐ 23 | 🐛 1 | 🌐 R | 📅 2020-10-13 - HTML widget for the Frappe Charts JavaScript library.
* [plotscaper](https://github.com/bartonicek/plotscaper) ⭐ 21 | 🐛 1 | 🌐 HTML | 📅 2025-11-30 - Linked interactive exploratory figures with selection, zooming, and panning.
* [tuichartr](https://github.com/dreamRs/tuichartr) ⚠️ Archived - HTML widget for tui-chart.
* [rroughviz](https://github.com/tidyss/rroughviz) ⭐ 10 | 🐛 1 | 🌐 R | 📅 2020-04-14 - R warpper for roughViz.js, a JavaScript library for creating sketchy/hand-drawn styled charts.
* [litecharts4r](https://github.com/the-y-company/litecharts4r) ⭐ 9 | 🐛 1 | 🌐 R | 📅 2023-09-30 - A lite wrapper around echarts.js and echarts4r.
* [vchartr](https://github.com/dreamRs/vchartr) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2026-01-08 - Interactive charts with the VChart JavaScript library.
* [vizdraws](https://github.com/ignacio82/vizdraws) ⭐ 9 | 🐛 6 | 🌐 JavaScript | 📅 2025-06-04 - Interactive visualization of Bayesian prior and posterior distribution draws.
* [detourr](https://github.com/casperhart/detourr) ⭐ 8 | 🐛 2 | 🌐 HTML | 📅 2026-07-01 - Interactive 2D and 3D scatterplot display.
* [fusionchartsR](https://github.com/alexym1/fusionchartsR) ⭐ 7 | 🐛 1 | 🌐 R | 📅 2026-01-12 - R wrapper for the FusionCharts JavaScript charting library.
* [myIO](https://github.com/mortonanalytics/myIO) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-25 - Composable D3 htmlwidget chart system.
* [controlcharts](https://github.com/aus-doh-safety-and-quality/controlcharts) ⭐ 5 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-25 - Interactive funnel plots and statistical process control charts.
* [maidr](https://github.com/xability/r-maidr) ⭐ 4 | 🐛 6 | 🌐 HTML | 📅 2026-08-28 - Multimodal access and interactive data representation with accessibility features.
* [rPackedBar](https://github.com/AdamSpannbauer/rPackedBar) ⭐ 3 | 🐛 1 | 🌐 R | 📅 2019-06-16 - Packed bar charts with plotly as an htmlwidget.
* [SveltePlots](https://github.com/Pascal-Schmidt/SveltePlots) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-02 - Svelte and D3 charting htmlwidget designed to simplify Shiny interactivity.
* [rMosaic](https://github.com/TiRizvanov/rMosaic) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-09 - R bindings to the Mosaic declarative visualization framework with linked, interactive plots backed by DuckDB.
* [Rnvd3](https://github.com/stla/Rnvd3) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2021-09-01 - Wrapper for selected nvd3 JavaScript charts.
* [muiCharts](https://github.com/lgnbhl/muiCharts) ⭐ 1 | 🐛 1 | 🌐 R | 📅 2026-07-19 - MUI X Charts for Shiny apps and Quarto, a set of React chart components including bar, line, pie, scatter, gauge, radar, and sparkline charts.
* [shinyHugePlot](https://cran.r-project.org/package=shinyHugePlot) - Efficient Plotly/Shiny plotting for very large datasets using downsampling.

### Scatterplot

* [rthreejs](https://github.com/bwlewis/rthreejs) ⭐ 308 | 🐛 37 | 🌐 JavaScript | 📅 2025-05-03 - Interactive 3D scatterplots, networks, and globes based on three.js.
* [scatterD3](https://github.com/juba/scatterD3) ⭐ 162 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-05 - R scatterplot htmlwidget based on D3.js.
* [pairsD3](https://github.com/garthtarr/pairsD3) ⭐ 55 | 🐛 4 | 🌐 R | 📅 2022-06-05 - D3 scatterplot matrices.
* [langevitour](https://github.com/pfh/langevitour) ⭐ 27 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-08 - Interactive tours of 2D projections of high-dimensional data.
* [graph3d](https://github.com/stla/graph3d) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2020-11-12 - R wrapper of the JavaScript library vis-graph3d.
* [picker](https://github.com/hms-dbmi/picker) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2022-05-17 - High-performance deck.gl scatterplot widget with Shiny bindings.
* [hpackedbubble](https://cran.r-project.org/package=hpackedbubble) - Split packed bubble charts with highcharts.
* [scatterPlotMatrix](https://cran.r-project.org/package=scatterPlotMatrix) - D3 scatter plot matrix htmlwidget with Shiny bindings.

### Parallel Coordinates

* [parcoords](https://github.com/timelyportfolio/parcoords) ⭐ 79 | 🐛 25 | 🌐 JavaScript | 📅 2023-01-06 - HTML widget for D3 parallel coordinates chart.
* [klustR](https://github.com/McKayMDavis/klustR) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2019-07-04 - D3 visualizations for interactive parallel coordinate and principal component plots.
* [parallelPlot](https://gitlab.com/drti/parallelplot) - D3 parallel coordinates htmlwidget with Shiny bindings.

### Time Series

* [timevis](https://github.com/daattali/timevis) ⭐ 683 | 🐛 4 | 🌐 R | 📅 2024-08-18 - Interactive timeline visualizations based on vis.js.
* [dygraphs](https://github.com/rstudio/dygraphs) ⭐ 367 | 🐛 122 | 🌐 JavaScript | 📅 2024-03-15 - R interface to the dygraphs JavaScript charting library.
* [streamgraph](https://github.com/hrbrmstr/streamgraph) ⭐ 146 | 🐛 23 | 🌐 HTML | 📅 2021-04-15 - HTML widget for creating streamgraph visualizations in R.
* [metricsgraphics](https://github.com/hrbrmstr/metricsgraphics) ⭐ 130 | 🐛 22 | 🌐 HTML | 📅 2018-02-03 - An htmlwidget interface to the MetricsGraphics.js D3-based charting library.
* [cronologia](https://github.com/feddelegrand7/cronologia) ⭐ 52 | 🐛 1 | 🌐 R | 📅 2021-04-23 - HTML vertical timeline component for R Markdown and Shiny.
* [tsibbletalk](https://github.com/earowang/tsibbletalk) ⭐ 28 | 🐛 0 | 🌐 R | 📅 2023-09-18 - Interactive graphics for tsibble objects with Shiny modules for exploring temporal patterns.
* [timelineschart](https://github.com/dreamRs/timelineschart) ⭐ 27 | 🐛 0 | 🌐 R | 📅 2022-10-03 - R interface to timelines-chart.
* [eventdropR](https://github.com/timelyportfolio/eventdropR) ⭐ 16 | 🐛 0 | 🌐 R | 📅 2017-03-14 - HTML widget for EventDrops, time based and event series interactive visualization using D3.
* [linevis](https://gitlab.com/thomaschln/linevis) - Interactive time-series visualizations based on vis.js, easy to synchronize with timevis.

### Tree and Hierarchical Data

* [trelliscopejs](https://github.com/hafen/trelliscopejs) ⭐ 263 | 🐛 77 | 🌐 R | 📅 2026-01-14 - Create interactive Trelliscope displays based on trelliscopejs-lib.
* [sunburstR](https://github.com/timelyportfolio/sunburstR) ⭐ 217 | 🐛 42 | 🌐 JavaScript | 📅 2024-02-08 - D3 sunburst charts for hierarchical data.
* [listviewer](https://github.com/timelyportfolio/listviewer) ⭐ 187 | 🐛 13 | 🌐 R | 📅 2023-10-01 - View and modify lists interactively, based on jsoneditor and react-json-view.
* [collapsibleTree](https://github.com/AdeelK93/collapsibleTree) ⭐ 163 | 🐛 37 | 🌐 HTML | 📅 2023-11-14 - D3-based interactive collapsible tree diagrams.
* [shinyTree](https://github.com/shinyTree/shinyTree) ⭐ 153 | 🐛 35 | 🌐 JavaScript | 📅 2025-10-02 - jsTree bindings for creating interactive trees in Shiny.
* [d3Tree](https://github.com/yonicd/d3Tree) ⭐ 86 | 🐛 0 | 🌐 R | 📅 2024-01-29 - D3-based collapsible trees for Shiny.
* [vtree](https://github.com/nbarrowman/vtree) ⭐ 76 | 🐛 10 | 🌐 R | 📅 2026-02-13 - Display information about nested subsets of a data frame as htmlwidgets.
* [treemap](https://github.com/mtennekes/treemap) ⭐ 65 | 🐛 17 | 🌐 R | 📅 2024-01-08 - Hierarchical data visualization with treemaps.
* [voronoiTreemap](https://github.com/uRosConf/voronoiTreemap) ⭐ 59 | 🐛 5 | 🌐 R | 📅 2019-07-02 - Interactive Voronoi treemaps as htmlwidgets.
* [jsTreeR](https://github.com/stla/jsTreeR) ⭐ 49 | 🐛 9 | 🌐 R | 📅 2024-07-15 - A wrapper of the JavaScript library jsTree.
* [D3partitionR](https://github.com/AntoineGuillot2/D3partitionR) ⭐ 41 | 🐛 14 | 🌐 JavaScript | 📅 2019-07-31 - D3-based interactive visualization of nested and hierarchical data (sunburst, treemap, circle treemap, icicle, and partition chart) for Shiny.
* [jsTree](https://github.com/yonicd/jsTree) ⭐ 30 | 🐛 5 | 🌐 HTML | 📅 2020-12-12 - R htmlwidget for inspecting heirachal structures with the jQuery jsTree plugin.
* [Rmarkmap](https://github.com/seifer08ms/Rmarkmap) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-02 - Create interactive mind maps with the markmap JavaScript library.
* [shinyCheckboxTree](https://github.com/stla/shinyCheckboxTree) ⭐ 7 | 🐛 12 | 🌐 R | 📅 2023-01-06 - Checkbox tree widget for Shiny. Wrapper of the JavaScript library react-checkbox-tree.
* [nivo.bubblechart](https://github.com/DataRacerEdu/nivo.bubblechart) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-14 - Nivo circle packing htmlwidget for hierarchical bubble charts in Shiny.
* [heattree](https://github.com/grunwaldlab/heattree) ⭐ 3 | 🐛 3 | 🌐 R | 📅 2026-05-08 - Interactive phylogenetic tree visualization.
* [muiTreeView](https://github.com/lgnbhl/muiTreeView) ⭐ 2 | 🐛 5 | 🌐 R | 📅 2026-08-28 - MUI X Tree View for Shiny apps and Quarto, a React component for navigating expandable, collapsible hierarchical lists.
* [sunburstShinyWidget](https://github.com/Tazovsky/sunburstShinyWidget) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-02-15 - D3-based sunburst htmlwidget for hierarchical data in Shiny.

### Network and Graph Data

* [networkD3](https://github.com/christophergandrud/networkD3) ⭐ 660 | 🐛 82 | 🌐 R | 📅 2025-04-18 - Create D3 network, tree, dendrogram, and Sankey diagram from R.
* [visNetwork](https://github.com/datastorm-open/visNetwork) ⭐ 564 | 🐛 156 | 🌐 JavaScript | 📅 2026-07-15 - Network visualization using vis.js.
* [chorddiag](https://github.com/mattflor/chorddiag) ⭐ 170 | 🐛 27 | 🌐 R | 📅 2021-10-18 - R interface to D3 interactive chord diagrams.
* [cyjShiny](https://github.com/cytoscape/cyjShiny) ⭐ 98 | 🐛 17 | 🌐 JavaScript | 📅 2024-08-06 - R/Shiny widget for Cytoscape.js.
* [grapher](https://github.com/JohnCoene/grapher) ⭐ 94 | 🐛 19 | 🌐 JavaScript | 📅 2023-01-05 - An R integration of ngraph to create 3D and 2D interactive graphs.
* [sigmajs](https://github.com/JohnCoene/sigmajs) ⭐ 72 | 🐛 7 | 🌐 R | 📅 2021-01-29 - Interface to the sigma.js graph visualization library, including animations, plugins, and Shiny widgets.
* [edgebundleR](https://github.com/garthtarr/edgebundleR) ⭐ 69 | 🐛 15 | 🌐 JavaScript | 📅 2023-03-23 - Circular layout plots with bundled edges based on D3.
* [ndtv](https://github.com/statnet/ndtv) ⭐ 52 | 🐛 45 | 🌐 HTML | 📅 2026-04-09 - Animated visualizations for dynamic network data.
* [sigmaNet](https://github.com/iankloo/sigmaNet) ⭐ 41 | 🐛 7 | 🌐 R | 📅 2018-06-28 - Render igraph networks using sigma.js.
* [g6R](https://github.com/cynkra/g6R) ⭐ 30 | 🐛 8 | 🌐 R | 📅 2026-08-28 - Graph visualization engine widget based on AntV G6 for R and Shiny.
* [shinyCyJS](https://github.com/jhk0530/shinyCyJS) ⭐ 10 | 🐛 4 | 🌐 JavaScript | 📅 2024-08-18 - Cytoscape.js R binding for Shiny.
* [chordViz](https://github.com/nredell/chordViz) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2019-05-26 - Create interactive chord diagrams in R.
* [hiveD3](https://github.com/nielsenmarkus11/hiveD3) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-18 - D3-based hive plots. [Tutorial](https://www.nielsenmark.us/2018/01/02/creating-a-custom-htmlwidget/) for recreating the package.
* [sgraph](https://gitlab.com/thomaschln/sgraph) - Network visualization for large igraph graphs with sigma.js v2.

### Categorical Data

* [parcats](https://github.com/erblast/parcats) ⭐ 40 | 🐛 2 | 🌐 R | 📅 2025-09-04 - Interactive parallel categories diagrams using plotly.js.
* [bar](https://github.com/dreamRs/bar) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-05 - Interactive one-dimensional proportions chart for representing categorical data.

### Diagrams

* [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) ⭐ 1,740 | 🐛 172 | 🌐 R | 📅 2026-04-27 - Diagram, graph, and network visualization based on D3.js, viz.js, and mermaid.js.
* [nomnoml](https://github.com/rstudio/nomnoml) ⭐ 222 | 🐛 3 | 🌐 JavaScript | 📅 2024-12-11 - R interface to nomnoml, a tool for drawing sassy UML diagrams based on syntax with customizable styling.
* [bpmn](https://github.com/bergant/bpmn) ⭐ 19 | 🐛 2 | 🌐 R | 📅 2017-05-15 - R interface to the bpmn-js library.
* [bpmnVisualizationR](https://github.com/process-analytics/bpmn-visualization-R) ⭐ 19 | 🐛 29 | 🌐 R | 📅 2026-06-23 - BPMN diagram htmlwidget with overlays, styling, and interactions.
* [processmapR](https://github.com/bupaverse/processmapr) ⭐ 11 | 🐛 23 | 🌐 R | 📅 2026-02-27 - Construct interactive process maps using event data as htmlwidgets.
* [amVennDiagram5](https://github.com/stla/amVennDiagram5) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-29 - Interactive amCharts 5 Venn diagrams for Shiny and R Markdown.
* [sankeywheel](https://github.com/lqqa/sankeywheel) ⭐ 1 | 🐛 0 | 📅 2022-07-02 - Highcharts-based Sankey diagrams and dependency wheels for Shiny and R Markdown.

### Heatmap

* [heatmaply](https://github.com/talgalili/heatmaply) ⭐ 408 | 🐛 39 | 🌐 R | 📅 2025-11-29 - Interactive heatmaps using plotly.
* [iheatmapr](https://github.com/ropensci/iheatmapr) ⭐ 270 | 🐛 50 | 🌐 R | 📅 2026-04-29 - Modular interactive complex heatmaps as htmlwidgets.
* [d3heatmap](https://github.com/talgalili/d3heatmap) ⭐ 236 | 🐛 45 | 🌐 R | 📅 2025-11-29 - D3-based interactive heatmaps (highlight rows/columns, zoom in/out, clustering, dendrograms).
* [nivocal](https://github.com/react-R/nivocal) ⭐ 40 | 🐛 3 | 🌐 R | 📅 2019-02-18 - HTML widget for drawing calendar heatmaps based on nivo.
* [rChartsCalmap](https://github.com/ramnathv/rChartsCalmap) ⭐ 31 | 🐛 6 | 🌐 JavaScript | 📅 2017-03-29 - An htmlwidgets binding for calendar heatmaps using D3.
* [calheatmapR](https://github.com/durtal/calheatmapR) ⭐ 21 | 🐛 4 | 🌐 JavaScript | 📅 2025-08-12 - R interface for the cal-heatmap JavaScript charting library to create calendar heatmaps.
* [supercaliheatmapwidget](https://github.com/hrbrmstr/supercaliheatmapwidget) ⭐ 20 | 🐛 1 | 🌐 JavaScript | 📅 2021-01-11 - Supercalifragilistic HTML calendar heatmaps.

### Maps and Spatial Data

* [leaflet](https://github.com/rstudio/leaflet) ⭐ 840 | 🐛 320 | 🌐 JavaScript | 📅 2025-10-08 - R interface to the Leaflet JavaScript library to create interactive maps.
* [mapview](https://github.com/r-spatial/mapview) ⭐ 551 | 🐛 103 | 🌐 JavaScript | 📅 2025-09-05 - Interactive viewing of spatial data.
* [mapdeck](https://github.com/SymbolixAU/mapdeck) ⭐ 384 | 🐛 79 | 🌐 HTML | 📅 2025-03-21 - Interactive maps using Mapbox GL and Deck.gl.
* [leafgl](https://github.com/r-spatial/leafgl) ⭐ 289 | 🐛 23 | 🌐 R | 📅 2026-04-15 - Performant WebGL rendering for leaflet.
* [googleway](https://github.com/SymbolixAU/googleway) ⭐ 240 | 🐛 58 | 🌐 HTML | 📅 2024-09-24 - Access Google Maps API to retrieve data and draw maps.
* [leaflet.extras](https://github.com/trafficonese/leaflet.extras) ⭐ 223 | 🐛 28 | 🌐 R | 📅 2025-12-15 - Extra functionality for the leaflet package.
* [mapedit](https://github.com/r-spatial/mapedit) ⭐ 221 | 🐛 37 | 🌐 R | 📅 2026-02-15 - Interactive editing of spatial data.
* [leafletCN](https://github.com/Lchiffon/leafletCN) ⭐ 197 | 🐛 13 | 🌐 R | 📅 2024-01-17 - China and geojson choropleth maps for Leaflet.
* [mapgl](https://github.com/walkerke/mapgl) ⭐ 171 | 🐛 26 | 🌐 R | 📅 2026-08-28 - Interactive maps using Mapbox GL JS and MapLibre GL JS.
* [leafpop](https://github.com/r-spatial/leafpop) ⭐ 117 | 🐛 10 | 🌐 R | 📅 2025-05-15 - Embed tables, images, and graphs in leaflet popups.
* [leafem](https://github.com/r-spatial/leafem) ⭐ 111 | 🐛 20 | 🌐 JavaScript | 📅 2025-11-04 - Leaflet and mapdeck extensions for mouse coordinates, image queries, zoom controls, and feature layers.
* [leaflet.minicharts](https://github.com/rte-antares-rpackage/leaflet.minicharts) ⭐ 108 | 🐛 26 | 🌐 R | 📅 2025-10-29 - Add and modify small charts on the interactive map created with the leaflet package.
* [deckgl](https://github.com/crazycapivara/deckgl) ⭐ 98 | 🐛 64 | 🌐 R | 📅 2024-02-05 - R Interface to Deck.gl.
* [leaflet.extras2](https://github.com/trafficonese/leaflet.extras2) ⭐ 90 | 🐛 15 | 🌐 JavaScript | 📅 2025-10-13 - More plugins for the leaflet package.
* [h3r](https://github.com/scottmmjackson/h3r) ⭐ 80 | 🐛 3 | 🌐 C++ | 📅 2024-02-06 - Uber's H3 geographical indexing library bindings for R.
* [flowmapblue](https://github.com/FlowmapBlue/flowmapblue.R) ⭐ 71 | 🐛 8 | 🌐 R | 📅 2025-02-28 - Interactive flow map htmlwidget for movement flows between geographic locations.
* [leafdown](https://github.com/hoga-it/leafdown) ⭐ 63 | 🐛 1 | 🌐 R | 📅 2022-11-13 - Provides drilldown functionality for leaflet choropleths.
* [leaftime](https://github.com/timelyportfolio/leaftime) ⭐ 57 | 🐛 6 | 🌐 R | 📅 2020-04-14 - Leaflet-timeline plugin for Leaflet to show changing geospatial data over time.
* [topogram](https://github.com/dreamRs/topogram) ⭐ 49 | 🐛 1 | 🌐 R | 📅 2021-12-11 - Cartogram htmlwidget for visualizing geographical data by distorting a TopoJSON topology using cartogram-chart.
* [leaflegend](https://github.com/tomroh/leaflegend) ⭐ 38 | 🐛 1 | 🌐 R | 📅 2026-07-23 - Custom legends and symbols for leaflet maps.
* [leafsync](https://github.com/r-spatial/leafsync) ⭐ 37 | 🐛 6 | 🌐 JavaScript | 📅 2022-03-03 - Small multiples of synchronized leaflet web maps.
* [datamaps](https://github.com/JohnCoene/datamaps) ⭐ 23 | 🐛 2 | 🌐 R | 📅 2020-08-27 - Create interactive choropleth maps with the JavaScript library Datamaps, add arcs and bubbles, change choropleth values, and change labels.
* [quickglobe](https://github.com/daranzolin/quickglobe) ⭐ 22 | 🐛 1 | 🌐 R | 📅 2020-05-25 - View country data via a 3D D3 globe.
* [leafpm](https://github.com/r-spatial/leafpm) ⭐ 22 | 🐛 4 | 🌐 R | 📅 2019-04-27 - Leaflet plugin for drawing and editing spatial features.
* [tmap.mapgl](https://github.com/r-tmap/tmap.mapgl) ⭐ 17 | 🐛 4 | 🌐 R | 📅 2026-06-16 - Mapbox GL JS and MapLibre GL JS modes for tmap.
* [tmap](https://github.com/mtennekes/tmap) ⭐ 15 | 🐛 0 | 📅 2022-11-10 - Create thematic maps, such as choropleths and bubble maps.
* [leaflet.providers](https://github.com/rstudio/leaflet.providers) ⭐ 15 | 🐛 3 | 🌐 R | 📅 2026-03-19 - Third-party map tile provider definitions for the leaflet package.
* [plainview](https://github.com/r-spatial/plainview) ⭐ 13 | 🐛 1 | 🌐 R | 📅 2025-08-19 - Interactive raster image viewer on a plain HTML canvas.
* [gior](https://github.com/JohnCoene/gior) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2020-03-02 - HTML widget for gio.js for declarative 3D globe data visualization.
* [maplamina](https://github.com/jhumbl/maplamina) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-15 - High-performance WebGL mapping widgets based on MapLibre GL and deck.gl.
* [geoarrowWidget](https://github.com/r-spatial/geoarrowWidget) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-03 - Attach GeoArrow and GeoParquet data to interactive htmlwidgets.
* [planetary](https://github.com/jonmcalder/planetary) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-21 - HTML widget for the planetary.js library for creating interactive globes.
* [rsquaire](https://github.com/Jkassof/rsquaire) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-29 - R interface for squaire.js, a JavaScript library for making responsive equal-area square maps using D3.
* [leaflet.opacity](https://github.com/be-marc/leaflet.opacity) ⭐ 4 | 🐛 3 | 🌐 R | 📅 2023-08-15 - Opacity controls for Leaflet maps.
* [amapro](https://github.com/helgasoft/amapro) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2026-01-29 - Build and control interactive 2D and 3D AMap/Gaode maps in R and Shiny.
* [rDeckgl](https://github.com/TiRizvanov/rDeckgl) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-02 - R bindings to Deck.gl.
* [toro](https://github.com/Epi-interactive-Ltd/toro) ⭐ 2 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-25 - Interactive and customizable maps using the MapLibre GL JS library.
* [r2deck](https://github.com/crazycapivara/r2deck) ⭐ 1 | 🐛 14 | 🌐 R | 📅 2023-01-07 - R interface to Deck.gl and Mapbox GL visualizations.
* [AtlasMaker](https://github.com/rachel-greenlee/AtlasMaker) ⭐ 1 | 🐛 1 | 🌐 R | 📅 2025-08-09 - Shiny module to create multiple interconnected leaflet maps across tabs.
* [bivariateLeaflet](https://github.com/maduprey/bivariateleaflet) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2025-01-02 - Create bivariate choropleth maps with Leaflet.
* [explodemap](https://github.com/PrigasG/explodemap) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-11 - Hierarchical exploded-view cartography with an interactive focus map widget for Shiny.
* [hchinamap](https://cran.r-project.org/package=hchinamap) - Mapping China and its provinces with highcharts.
* [webmap](https://code.usgs.gov/inl/webmap) - Interactive Leaflet web maps using The National Map services, with map controls and widgets.

### Sparkline

* [sparkline](https://github.com/htmlwidgets/sparkline) ⭐ 242 | 🐛 11 | 🌐 JavaScript | 📅 2019-04-28 - jQuery Sparkline (tiny inline charts) HTML Widget for R. [Use sparklines in DT](https://github.com/leonawicz/HtmlWidgetExamples) ⚠️ Archived.
* [dataui](https://github.com/timelyportfolio/dataui) ⭐ 78 | 🐛 8 | 🌐 R | 📅 2024-11-20 - Interactive visualizations of data-ui based on vx.
* [trendchart](https://github.com/the-y-company/trendchart) ⭐ 22 | 🐛 0 | 🌐 R | 📅 2024-01-29 - Small, simple trendchart for R.
* [reactrend](https://github.com/JohnCoene/reactrend) ⭐ 19 | 🐛 13 | 🌐 R | 📅 2023-01-04 - Simple, elegant spark lines and trend graphs based on react-trend.
* [peity](https://github.com/JohnCoene/peity) ⭐ 12 | 🐛 0 | 🌐 R | 📅 2019-05-28 - Inline charts for R.

### Word Cloud

* [wordcloud2](https://github.com/lchiffon/wordcloud2) ⭐ 414 | 🐛 49 | 🌐 JavaScript | 📅 2022-02-03 - Word cloud visualization based on wordcloud2.js.
* [d3wordcloud](https://github.com/jbkunst/d3wordcloud) ⭐ 63 | 🐛 5 | 🌐 R | 📅 2016-09-27 - HTML widget for D3.js word cloud layout.
* [hwordcloud](https://cran.r-project.org/package=hwordcloud) - Render word clouds with highcharts.

### Biological Data

* [geneviewer](https://github.com/nvelden/geneviewer) ⭐ 100 | 🐛 3 | 🌐 R | 📅 2025-09-29 - Interactive gene cluster visualization.
* [qtlcharts](https://github.com/kbroman/qtlcharts) ⭐ 87 | 🐛 14 | 🌐 CoffeeScript | 📅 2026-06-25 - Interactive graphics for QTL experiments.
* [NGLVieweR](https://github.com/nvelden/NGLVieweR) ⭐ 54 | 🐛 3 | 🌐 R | 📅 2026-05-02 - Interactive 3D visualization of molecular structures using the NGL Viewer JavaScript library.
* [threeBrain](https://github.com/dipterix/threeBrain) ⭐ 51 | 🐛 0 | 🌐 R | 📅 2026-08-26 - Advanced 3D brain visualization as an htmlwidget.
* [igvR](https://github.com/gladkia/igvR) ⭐ 46 | 🐛 4 | 🌐 JavaScript | 📅 2026-05-01 - R package providing interactive connections to igv.js running in a web browser.
* [igvShiny](https://github.com/gladkia/igvShiny) ⭐ 46 | 🐛 7 | 🌐 R | 📅 2026-08-28 - HTML widget for igv.js, a JavaScript library for embeddable genomic visualization.
* [ggseg3d](https://github.com/ggsegverse/ggseg3d) ⭐ 45 | 🐛 7 | 🌐 R | 📅 2026-08-28 - Interactive Three.js brain atlas meshes visualization.
* [JBrowseR](https://github.com/GMOD/JBrowseR) ⭐ 40 | 🐛 0 | 🌐 R | 📅 2026-08-27 - R interface to the JBrowse 2 linear genome view.
* [BioCircos.R](https://github.com/lvulliard/BioCircos.R) ⭐ 38 | 🐛 19 | 🌐 JavaScript | 📅 2019-05-03 - Interactive circular visualization of genomic data using htmlwidgets and BioCircos.js.
* [g3viz](https://github.com/G3viz/g3viz) ⭐ 33 | 🐛 19 | 🌐 JavaScript | 📅 2024-09-10 - D3-based interactive lollipop plots.
* [Racmacs](https://github.com/acorg/Racmacs) ⭐ 24 | 🐛 37 | 🌐 JavaScript | 📅 2026-07-08 - Make antigenic maps from immunological assay data.
* [shiny.molstar](https://github.com/Appsilon/shiny.molstar) ⭐ 19 | 🐛 9 | 🌐 R | 📅 2026-08-26 - Shiny wrapper for Mol\*, a visualization toolkit of large scale molecular data.
* [shiny.gosling](https://github.com/Appsilon/shiny.gosling) ⭐ 18 | 🐛 24 | 🌐 R | 📅 2026-04-22 - Shiny wrapper for Gosling.js, grammar-based toolkit for scalable and interactive genomics data visualization.
* [phylowidget](https://github.com/sdwfrost/phylowidget) ⭐ 18 | 🐛 4 | 🌐 HTML | 📅 2015-02-26 - Interactive phylogenetic trees based on phylotree.js.
* [TnT](https://github.com/Marlin-Na/TnT) ⭐ 15 | 🐛 5 | 🌐 R | 📅 2024-09-09 - Track-based visulizations based on the TnT JavaScript libraries. Useful for displaying genomic features as a simple genome browser.
* [ideogRam](https://github.com/freestatman/ideogRam) ⭐ 15 | 🐛 7 | 🌐 R | 📅 2022-10-26 - HTML widget for chromosome visualization with ideogram.js.
* [shinybody](https://github.com/robert-norberg/shinybody) ⭐ 13 | 🐛 0 | 🌐 R | 📅 2025-01-08 - Interactive anatomography widget for Shiny.
* [mutsneedle](https://github.com/freezecoder/mutsneedle) ⭐ 12 | 🐛 3 | 🌐 JavaScript | 📅 2018-04-18 - Interactive mutation lollipop diagrams.
* [safetyCharts](https://github.com/SafetyGraphics/safetyCharts) ⭐ 12 | 🐛 31 | 🌐 JavaScript | 📅 2025-04-09 - Charts for monitoring clinical trial safety.
* [msaR](https://github.com/zachcp/msaR) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2021-09-22 - BioJS-based MSA (multiple sequence alignment) viewer.
* [phylocanvas](https://github.com/zachcp/phylocanvas) ⭐ 9 | 🐛 5 | 🌐 R | 📅 2019-12-03 - Interactive phylogenetic trees using the Phylocanvas JavaScript library.
* [flowDashboard](https://github.com/laderast/flowDashboard) ⭐ 8 | 🐛 5 | 🌐 R | 📅 2018-06-14 - Shiny Modules for visualizing flow cytometry data.
* [volcanoPlot](https://github.com/SafetyGraphics/volcanoPlot) ⭐ 6 | 🐛 17 | 🌐 R | 📅 2024-01-30 - Volcano plot Shiny module for clinical trial adverse event monitoring.
* [jellyfisher](https://github.com/HautaniemiLab/jellyfisher) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2026-08-21 - Interactive jellyfish plots combining sample and phylogenetic trees to visualize spatiotemporal tumor evolution.
* [nglShiny](https://github.com/paul-shannon/nglShiny) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2024-08-07 - NGL Viewer as an htmlwidget for molecular visualization.
* [chromoMap](https://cran.r-project.org/package=chromoMap) - Interactive visualization and mapping of human chromosomes.

### Chemical Data

* [r3dmol](https://github.com/swsoyee/r3dmol) ⭐ 99 | 🐛 11 | 🌐 JavaScript | 📅 2023-10-25 - Visualizing molecular data in 3D, based on 3Dmol.js.
* [chemdoodle](https://github.com/zachcp/chemdoodle) ⚠️ Archived - HTML widget for visualizing and drawing molecules.

### WebGL

* [rayshader](https://github.com/tylermorganwall/rayshader) ⭐ 2,175 | 🐛 48 | 🌐 R | 📅 2026-08-26 - Create and visualize hillshaded maps from elevation matrices.
* [rayrender](https://github.com/tylermorganwall/rayrender) ⭐ 643 | 🐛 4 | 🌐 C++ | 📅 2026-07-22 - Build and raytrace 3D scenes.
* [rgl](https://github.com/dmurdoch/rgl) ⭐ 103 | 🐛 20 | 🌐 C++ | 📅 2026-07-15 - Render WebGL scenes created with the rgl package ([vignette](https://cran.r-project.org/web/packages/rgl/vignettes/WebGL.html)).
* [rayimage](https://github.com/tylermorganwall/rayimage) ⭐ 64 | 🐛 1 | 🌐 R | 📅 2026-07-04 - Render depth of field for images.
* [cubeview](https://github.com/r-spatial/cubeview) ⭐ 25 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-20 - Interactive 3D raster cube viewer.
* [r3js](https://github.com/shwilks/r3js) ⭐ 14 | 🐛 6 | 🌐 JavaScript | 📅 2025-01-28 - WebGL-based 3D plotting with three.js and Shiny bindings.
* [ggWebGL](https://github.com/fbertran/ggWebGL) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2026-06-06 - Browser-native WebGL rendering for R graphics.
* [thorn](https://github.com/stla/thorn) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2020-11-12 - WebGL shader htmlwidgets that can be used as Shiny app backgrounds.

### Augmented and Virtual Reality

* [arframer](https://github.com/JohnCoene/arframer) ⭐ 13 | 🐛 0 | 🌐 R | 📅 2020-10-15 - Augmented Reality in R based on AR.js.
* [shinyaframe](https://cran.r-project.org/package=shinyaframe) - WebVR data visualizations with Shiny and Mozilla A-Frame.

## Frameworks

*Shiny app scaffolding and development frameworks built for various purposes.*

### Foundational frameworks

* [golem](https://github.com/ThinkR-open/golem) ⭐ 945 | 🐛 21 | 🌐 R | 📅 2026-07-07 - Opinionated framework for building production-grade Shiny apps.
* [learnr](https://github.com/rstudio/learnr) ⭐ 736 | 🐛 152 | 🌐 R | 📅 2025-11-13 - Interactive R Markdown tutorials with Shiny-powered exercises, quizzes, and question widgets.
* [Rhino](https://github.com/Appsilon/rhino) ⭐ 330 | 🐛 84 | 🌐 R | 📅 2026-06-10 - Build high quality, enterprise-grade Shiny apps at speed.
* [teal](https://github.com/insightsengineering/teal) ⭐ 263 | 🐛 75 | 🌐 R | 📅 2026-08-28 - Interactive exploration framework for analyzing clinical trials data, provides a dynamic filtering facility and different data viewers.
* [surveydown](https://github.com/surveydown-dev/surveydown) ⭐ 180 | 🐛 17 | 🌐 R | 📅 2026-06-23 - Markdown-based programmable surveys using Quarto and Shiny, with skip logic, multiple question types, and database storage.
* [yonder](https://github.com/nteetor/yonder) ⭐ 136 | 🐛 26 | 🌐 R | 📅 2026-08-29 - A reactive web framework built on Shiny with Bootstrap 4.
* [irid](https://github.com/khusmann/irid) ⭐ 22 | 🐛 5 | 🌐 R | 📅 2026-07-23 - Component-based reactive UI framework for Shiny with fine-grained DOM updates that avoid full re-rendering and update callbacks.
* [blockr.core](https://github.com/BristolMyersSquibb/blockr.core) ⭐ 16 | 🐛 31 | 🌐 R | 📅 2026-08-27 - Graphical web framework for data manipulation and visualization using reusable, composable blocks.
* [aurora](https://github.com/aurora-govpe/aurora-rpkg) ⭐ 1 | 🐛 1 | 🌐 R | 📅 2026-07-31 - Build stateless web apps in R with plumber2 and bslib.

### Scaffolding

* [leprechaun](https://github.com/devOpifex/leprechaun) ⭐ 77 | 🐛 8 | 🌐 R | 📅 2025-04-14 - Code generator for lean and robust Shiny applications.
* [windy](https://github.com/devOpifex/windy) ⭐ 40 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-12 - Sets up basic scaffold to use Tailwind CSS within an R package for a Shiny application.
* [autoshiny](https://github.com/alekrutkowski/autoshiny) ⭐ 26 | 🐛 0 | 🌐 R | 📅 2023-03-10 - Automatically transform an R function into a Shiny app object or app files.
* [periscope](https://github.com/cb4ds/periscope) ⭐ 18 | 🐛 0 | 🌐 R | 📅 2025-01-29 - Enterprise streamlined Shiny application framework with reusable downloadable modules.
* [periscope2](https://github.com/Aggregate-Genius/periscope2) ⭐ 9 | 🐛 0 | 🌐 R | 📅 2026-08-21 - Enterprise streamlined Shiny application framework using bs4Dash.
* [ggpaintr](https://github.com/willju-wangqian/ggpaintr) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-07-10 - Build formula-driven Shiny apps for ggplot2 with automatically generated controls, live plots, and reproducible code.

### Framework extensions

* [teal.modules.clinical](https://github.com/insightsengineering/teal.modules.clinical) ⭐ 42 | 🐛 108 | 🌐 R | 📅 2026-08-23 - A set of teal modules for standard clinical outputs.
* [mwshiny](https://github.com/delosh653/mwshiny) ⭐ 25 | 🐛 2 | 🌐 R | 📅 2020-06-08 - Run a Shiny app across multiple connected browser windows.
* [teal.modules.general](https://github.com/insightsengineering/teal.modules.general) ⭐ 16 | 🐛 44 | 🌐 R | 📅 2026-08-17 - General modules for teal applications.
* [teal.code](https://github.com/insightsengineering/teal.code) ⭐ 12 | 🐛 16 | 🌐 R | 📅 2026-07-26 - Code storage and execution class for teal applications.
* [teal.slice](https://github.com/insightsengineering/teal.slice) ⭐ 12 | 🐛 36 | 🌐 R | 📅 2026-07-29 - Filter module for teal applications.
* [teal.data](https://github.com/insightsengineering/teal.data) ⭐ 11 | 🐛 20 | 🌐 R | 📅 2026-06-29 - Data model for teal applications.
* [teal.reporter](https://github.com/insightsengineering/teal.reporter) ⭐ 9 | 🐛 25 | 🌐 R | 📅 2026-07-27 - Reporting tools for Shiny modules.
* [formods](https://github.com/john-harrold/formods) ⭐ 9 | 🐛 13 | 🌐 R | 📅 2026-02-11 - Shiny modules for general tasks including data wrangling, figure generation, and app state management.
* [teal.logger](https://github.com/insightsengineering/teal.logger) ⭐ 7 | 🐛 5 | 🌐 R | 📅 2026-06-29 - Logging setup for the teal family of packages.
* [tutorial.helpers](https://github.com/PPBDS/tutorial.helpers) ⭐ 7 | 🐛 0 | 🌐 HTML | 📅 2026-08-15 - Helper functions and Shiny modules for creating, editing, and testing tutorials with learnr, including collecting student submissions.
* [teal.widgets](https://github.com/insightsengineering/teal.widgets) ⭐ 6 | 🐛 37 | 🌐 R | 📅 2026-07-30 - Shiny widgets for teal applications.
* [uteals](https://github.com/phuse-org/uteals) ⭐ 6 | 🐛 5 | 🌐 R | 📅 2026-07-10 - Shared decorators, transformators, and utility functions that extend teal modules.
* [teal.picks](https://github.com/insightsengineering/teal.picks) ⭐ 4 | 🐛 29 | 🌐 R | 📅 2026-08-28 - Dataset and variable picker and merge module for teal applications.
* [VizModules](https://github.com/j-andrews7/VizModules) ⭐ 3 | 🐛 12 | 🌐 R | 📅 2026-08-28 - Flexible Shiny plotting modules for composing interactive visualization apps.
* [teal.transform](https://github.com/insightsengineering/teal.transform) ⭐ 2 | 🐛 40 | 🌐 R | 📅 2026-06-29 - Functions and Shiny modules for extracting and merging data within the teal framework.
* [blockr.dplyr](https://github.com/BristolMyersSquibb/blockr.dplyr) ⭐ 1 | 🐛 1 | 🌐 R | 📅 2026-08-25 - Interactive dplyr data transformation blocks for blockr.
* [blockr.ggplot](https://github.com/BristolMyersSquibb/blockr.ggplot) ⭐ 1 | 🐛 4 | 🌐 R | 📅 2026-08-24 - Interactive ggplot2 visualization blocks for blockr.
* [blockr.io](https://github.com/BristolMyersSquibb/blockr.io) ⭐ 1 | 🐛 5 | 🌐 R | 📅 2026-08-23 - Interactive file import and export blocks for blockr.
* [blockr.dag](https://github.com/BristolMyersSquibb/blockr.dag) ⭐ 0 | 🐛 20 | 🌐 R | 📅 2026-08-28 - A directed acyclic graph extension for blockr.
* [blockr.dock](https://github.com/BristolMyersSquibb/blockr.dock) ⭐ 0 | 🐛 27 | 🌐 R | 📅 2026-08-28 - A docking layout manager for blockr.
* [blockr.session](https://github.com/BristolMyersSquibb/blockr.session) ⭐ 0 | 🐛 4 | 🌐 R | 📅 2026-08-25 - Persist, restore, share, and manage blockr boards with pins-backed storage, including Posit Connect user accounts and version history.

## Backend

*Backend components and service integrations for Shiny apps.*

### Database

* [pool](https://github.com/rstudio/pool) ⭐ 255 | 🐛 3 | 🌐 R | 📅 2026-05-19 - Database connection pooling in R.
* [elastic](https://github.com/ropensci-archive/elastic) ⚠️ Archived - R client for the Elasticsearch HTTP API.
* [sergeant](https://github.com/hrbrmstr/sergeant) ⭐ 124 | 🐛 7 | 🌐 R | 📅 2022-04-18 - Transform and query data with Apache Drill.
* [Best Practices in Working with Databases](https://solutions.posit.co/connections/db/) - Packages and tutorials for connecting R and Shiny apps to databases.

### Persistent Data Storage

* [pins](https://github.com/rstudio/pins-r) ⭐ 335 | 🐛 44 | 🌐 R | 📅 2026-08-02 - Publish data sets, models, and other R objects to folders, Posit Connect, Amazon S3, and more.
* [shinystate](https://github.com/rpodcast/shinystate) ⭐ 23 | 🐛 8 | 🌐 R | 📅 2026-02-11 - Customize Shiny's bookmarkable state with configurable storage locations via the pins package.

### API Frameworks

* [plumber](https://github.com/rstudio/plumber) ⭐ 1,438 | 🐛 126 | 🌐 R | 📅 2026-02-09 - Create web APIs by decorating R code with special comments.
* [opencpu](https://github.com/opencpu/opencpu) ⭐ 761 | 🐛 105 | 🌐 R | 📅 2026-05-31 - A system for embedded scientific computing and reproducible research with R.
* [RestRserve](https://github.com/rexyai/RestRserve) ⭐ 295 | 🐛 11 | 🌐 R | 📅 2025-03-21 - R web API framework for building high-performance and robust microservices and app backends.
* [valve](https://github.com/JosiahParry/valve) ⭐ 156 | 🐛 7 | 🌐 R | 📅 2025-06-24 - Create multi-threaded Plumber APIs powered by Rust's tokio and axum web frameworks.
* [plumber2](https://github.com/posit-dev/plumber2) ⭐ 116 | 🐛 29 | 🌐 R | 📅 2026-01-21 - Easy and powerful webservers in R. A complete rewrite of plumber.
* [htmxr](https://github.com/hyperverse-r/htmxr) ⭐ 45 | 🐛 0 | 🌐 R | 📅 2026-08-10 - Build server-driven web applications in R with htmx for partial page updates and plumber2 for non-blocking HTTP endpoints.
* [communicate](https://github.com/devOpifex/communicate) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2024-05-29 - Small framework to communicate between Shiny client and server via HTTP requests.

### URL Routing

* [shiny.router](https://github.com/Appsilon/shiny.router) ⭐ 266 | 🐛 14 | 🌐 R | 📅 2025-04-18 - Minimalistic URL router for Shiny apps.
* [brochure](https://github.com/ColinFay/brochure) ⭐ 109 | 🐛 17 | 🌐 R | 📅 2026-06-17 - Create natively multi-page Shiny applications to serve content from multiple endpoints. See [blog post](https://colinfay.me/post-request-shiny-app-brochure/) on POST requests support.
* [shinyURL](https://github.com/aoles/shinyURL) ⭐ 82 | 🐛 8 | 🌐 R | 📅 2016-08-08 - Save and restore the state of a Shiny app by encoding the values of user inputs and active tab panels in the app's URL query string.
* [scenes](https://github.com/shinyworks/scenes) ⭐ 16 | 🐛 10 | 🌐 R | 📅 2024-11-07 - Switch between alternative UIs based on request properties, such as cookies, paths, query parameters, or HTTP request method.
* [shinypayload](https://github.com/PawanRamaMali/shinypayload) ⭐ 11 | 🐛 5 | 🌐 R | 📅 2026-01-26 - Accept POST data and URL parameters in Shiny for same-port integration.
* [Accepting POST requests from Shiny](https://gist.github.com/jcheng5/2aaff19e67079840350d08361fe7fb20) - Undocumented feature for handling POST requests that are not associated with any specific Shiny session.

### Authentication

* [shinyauthr](https://github.com/PaulC91/shinyauthr) ⭐ 439 | 🐛 14 | 🌐 R | 📅 2024-03-04 - Server-side authentication using shiny modules.
* [shinymanager](https://github.com/datastorm-open/shinymanager) ⭐ 404 | 🐛 53 | 🌐 HTML | 📅 2026-07-06 - Simple and secure authentification mechanism for single Shiny apps.
* [polished](https://github.com/tychobra/polished) ⭐ 236 | 🐛 21 | 🌐 R | 📅 2025-03-20 - Authentication, user administration, and hosting for Shiny apps.
* [googleAuthR](https://github.com/MarkEdmondson1234/googleAuthR) ⭐ 180 | 🐛 48 | 🌐 R | 📅 2025-11-28 - Shiny compatible Google API client for authentication with OAuth2.
* [firebase](https://github.com/JohnCoene/firebase) ⭐ 169 | 🐛 13 | 🌐 R | 📅 2025-07-09 - Authenticate Shiny users with Google Firebase.
* [auth0](https://github.com/curso-r/auth0) ⭐ 165 | 🐛 31 | 🌐 R | 📅 2026-04-13 - Authentication in Shiny apps using Auth0.
* [gargle](https://github.com/r-lib/gargle) ⭐ 113 | 🐛 34 | 🌐 R | 📅 2026-05-28 - Infrastructure for calling Google APIs from R, including auth.
* [tapLock](https://github.com/ixpantia/tapLock) ⭐ 38 | 🐛 4 | 🌐 Rust | 📅 2025-12-13 - Seamless Single Sign-On for Shiny.
* [login](https://github.com/jbryer/login) ⭐ 30 | 🐛 4 | 🌐 R | 📅 2025-05-16 - Shiny login module providing customizable login/logout UI.
* [shinyOAuth](https://github.com/lukakoning/shinyOAuth) ⭐ 28 | 🐛 0 | 🌐 R | 📅 2026-07-24 - Provider-agnostic OAuth authentication for Shiny applications.
* [cognitoR](https://github.com/chi2labs/cognitoR) ⭐ 22 | 🐛 6 | 🌐 R | 📅 2024-01-29 - Authentication for Shiny apps with Amazon Cognito.
* [otp](https://github.com/randy3k/otp) ⭐ 18 | 🐛 1 | 🌐 R | 📅 2024-01-23 - One-Time Password generation and verification.
* [rAccess](https://github.com/johnsonandjohnson/rAccess) ⭐ 18 | 🐛 2 | 🌐 R | 📅 2025-11-06 - Access control module for Shiny applications with hierarchical permission management.
* [shinydbauth](https://github.com/diegoefe/shinydbauth) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2024-07-21 - Simple authentication for Shiny applications with database-backed credential storage.
* [backendlessr](https://gitlab.com/rresults/backendlessr) - R wrapper for Backendless API to manage users.

### Job Scheduling

* [cronR](https://github.com/bnosac/cronR) ⭐ 289 | 🐛 7 | 🌐 R | 📅 2023-12-12 - R package for managing cron jobs.

### Web APIs Integration

* [shinyStore](https://github.com/trestletech/shinyStore) ⭐ 95 | 🐛 7 | 🌐 R | 📅 2023-04-04 - Use the Web Storage API to store persistent, synchronized data in the user's browser.
* [geoloc](https://github.com/ColinFay/geoloc) ⭐ 47 | 🐛 2 | 🌐 R | 📅 2019-11-25 - Use the Geolocation API to get the location of the user (with user's permission).
* [glouton](https://github.com/ColinFay/glouton) ⭐ 41 | 🐛 2 | 🌐 R | 📅 2022-02-22 - Handle browser cookies in shiny, built on top of js-cookie.
* [cookies](https://github.com/shinyworks/cookies) ⭐ 38 | 🐛 18 | 🌐 R | 📅 2026-02-04 - Another js-cookie package, with added functionality to handle HttpOnly cookies.
* [shinyStorePlus](https://github.com/oobianom/shinyStorePlus) ⭐ 34 | 🐛 5 | 🌐 JavaScript | 📅 2025-06-06 - In-browser storage for Shiny persistent, synchronized data from the inputs using IndexedDB.
* [AutoDeskR](https://github.com/paulgovan/AutoDeskR) ⭐ 8 | 🐛 0 | 🌐 R | 📅 2026-07-22 - Interface to Autodesk Platform Services APIs with Shiny viewers for 2D and 3D design models.

### Notification Integration

* [blastula](https://github.com/rstudio/blastula) ⭐ 575 | 🐛 107 | 🌐 R | 📅 2025-04-03 - Easily send HTML email messages from R.
* [slackr](https://github.com/mrkaye97/slackr) ⭐ 308 | 🐛 4 | 🌐 R | 📅 2024-10-16 - Send messages, images, R objects, and files to Slack channels/users.
* [twilio](https://github.com/seankross/twilio) ⭐ 46 | 🐛 7 | 🌐 R | 📅 2020-12-23 - R interface to the Twilio API.
* [sendgridr](https://github.com/mrchypark/sendgridr) ⭐ 25 | 🐛 5 | 🌐 R | 📅 2025-06-02 - Send emails with SendGrid mail API (v3).
* [mailtoR](https://github.com/feddelegrand7/mailtoR) ⭐ 22 | 🐛 3 | 🌐 R | 📅 2020-12-09 - Creates a friendly user interface for emails sending in Shiny.
* [mjml](https://github.com/JohnCoene/mjml) ⭐ 14 | 🐛 0 | 🌐 R | 📅 2020-06-15 - Create responsive emails with R and MJML.
* [r2social](https://github.com/oobianom/r2social) ⭐ 7 | 🐛 0 | 🌐 R | 📅 2024-07-30 - Social media sharing and connect buttons for Shiny and R Markdown.
* [emailjsr](https://cran.r-project.org/package=emailjsr) - EmailJS integration for sending emails from Shiny apps.

### Cloud Integration

* [cloudyr](https://cloudyr.github.io/packages/) - R packages for integrating with AWS, Azure, and Google Cloud.

### G Suite Integration

<!--lint disable awesome-spell-check-->

* [googlesheets](https://github.com/jennybc/googlesheets) ⚠️ Archived - R interface to Google Spreadsheets API (no longer under active development).
* [googlesheets4](https://github.com/tidyverse/googlesheets4) ⭐ 377 | 🐛 37 | 🌐 R | 📅 2026-08-28 - R interface to Google Sheets via the Sheets API v4.
* [googledrive](https://github.com/tidyverse/googledrive) ⭐ 346 | 🐛 41 | 🌐 R | 📅 2026-08-28 - R API client for Google Drive.
* [gmailr](https://github.com/r-lib/gmailr) ⭐ 237 | 🐛 23 | 🌐 R | 📅 2026-01-30 - Access the Gmail RESTful API from R.

<!--lint enable awesome-spell-check-->

## Deploy

*Deploy Shiny apps to the cloud, hosted infrastructure, or desktop.*

### Remote Deploy

* [rsconnect](https://github.com/rstudio/rsconnect) ⭐ 145 | 🐛 73 | 🌐 R | 📅 2026-08-27 - Deploy Shiny apps to shinyapps.io, or Posit Connect.
* [connectwidgets](https://github.com/rstudio/connectwidgets) ⭐ 22 | 🐛 30 | 🌐 R | 📅 2025-05-06 - Query a Posit Connect server for a subset of content items, then organize them within htmlwidget components in R Markdown documents or Shiny applications.
* [tinyshinyserver](https://github.com/lab1702/tinyshinyserver) ⭐ 21 | 🐛 1 | 🌐 R | 📅 2026-01-06 - Lightweight multi-app Shiny proxy with WebSocket support and automatic health monitoring.

### Desktop Deploy

* [nativefier](https://github.com/nativefier/nativefier) ⚠️ Archived - Create Electron wrappers for any websites (including remotely deployed Shiny apps).
* [DesktopDeployR](https://github.com/wleepang/DesktopDeployR) ⭐ 437 | 🐛 23 | 🌐 R | 📅 2022-05-29 - A framework for deploying self-contained R-based applications to the desktop.
* [RInno](https://github.com/ficonsulting/RInno) ⭐ 313 | 🐛 61 | 🌐 HTML | 📅 2023-10-31 - Deploy Shiny apps to Windows by interfacing Inno Setup and Electron.
* [electricShine](https://github.com/chasemc/electricShine) ⚠️ Archived - Create distributable Shiny Electron apps.
* [photon](https://github.com/COVAIL/photon) ⭐ 131 | 🐛 32 | 🌐 R | 📅 2023-05-09 - RStudio Add-in to build Shiny apps utilizing the Electron framework.
* [r-shiny-electron](https://github.com/dirkschumacher/r-shiny-electron) ⚠️ Archived - Template for R Shiny and Electron integration.
* [shiny.pwa](https://github.com/pedrocoutinhosilva/shiny.pwa) ⭐ 62 | 🐛 4 | 🌐 R | 📅 2021-09-05 - Progressive Web App (PWA) support for Shiny, enabling installable web apps.
* [Shiny Meets Electron](https://github.com/ksasso/useR_electron_meet_shiny) ⭐ 52 | 🐛 3 | 🌐 HTML | 📅 2020-01-28 - Talk at useR! 2018 on turning Shiny app into standalone desktop apps. [Talk video](https://www.youtube.com/watch?v=ARrbbviGvjc).

### Static Server Deploy

* [webR](https://github.com/r-wasm/webr) ⭐ 1,088 | 🐛 91 | 🌐 TypeScript | 📅 2026-06-23 - A version of R compiled for the browser and Node.js using WebAssembly via Emscripten.
* [r-shinylive](https://github.com/posit-dev/r-shinylive) ⭐ 235 | 🐛 48 | 🌐 R | 📅 2026-07-29 - Run Shiny apps entirely in the browser using WebAssembly via webR.

## Developer Tools

*Debug, test, and optimize Shiny apps.*

### Prototyping

* [shinyuieditor](https://github.com/rstudio/shinyuieditor) ⭐ 227 | 🐛 48 | 🌐 JavaScript | 📅 2024-06-27 - A GUI for laying out a Shiny application that generates clean and human-readable UI code.
* [fakir](https://github.com/ThinkR-open/fakir) ⭐ 133 | 🐛 6 | 🌐 R | 📅 2026-04-25 - Create fake data in R for tutorials.
* [shinipsum](https://github.com/ThinkR-open/shinipsum) ⭐ 124 | 🐛 12 | 🌐 R | 📅 2026-05-15 - Lorem-Ipsum-like helpers for fast Shiny prototyping.
* [shinysnippets](https://github.com/ThinkR-open/shinysnippets) ⭐ 100 | 🐛 4 | 🌐 R | 📅 2026-04-25 - A series of Shiny related RStudio snippets.
* [html2R](https://github.com/stla/html2R) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-08 - Converts HTML markup into R tag code for building Shiny UIs.
* [midas](https://github.com/shapenaji/midas) ⭐ 5 | 🐛 0 | 🌐 R | 📅 2018-03-02 - Bootstrap new Shiny functions by turning HTML snippets directly into R tag functions.
* [ShinyQuickStarter](https://cran.r-project.org/package=ShinyQuickStarter) - RStudio addin for drag-and-drop creation of Shiny apps, dashboards, and modules.

### Modularization

* [box](https://github.com/klmr/box) ⭐ 975 | 🐛 71 | 🌐 R | 📅 2026-08-16 - Organize code into hierarchical, composable, reusable modules, to use across projects.
* [packer](https://github.com/JohnCoene/packer) ⭐ 151 | 🐛 12 | 🌐 R | 📅 2025-09-17 - An opinionated framework for using JavaScript with R.
* [tidymodules](https://github.com/Novartis/tidymodules) ⭐ 145 | 🐛 25 | 🌐 R | 📅 2024-09-05 - An object-oriented approach to Shiny modules.
* [supreme](https://github.com/strboul/supreme) ⚠️ Archived - Structure Shiny applications developed with modules.
* [component](https://github.com/devOpifex/component) ⭐ 29 | 🐛 0 | 🌐 R | 📅 2023-11-05 - Create components for Shiny, inspired by Vue.js.
* [many](https://github.com/the-y-company/many) ⭐ 17 | 🐛 1 | 🌐 R | 📅 2024-03-30 - Use multiple directories to build R packages.
* [gargoyle](https://cran.r-project.org/package=gargoyle) - An event-based mechanism for Shiny, providing lighter alternatives to standard reactive objects.
* [shiny.destroy](https://cran.r-project.org/package=shiny.destroy) - Create destroyable modules in Shiny, allowing dynamic creation and removal of module instances.

### Debugging

* [flow](https://github.com/moodymudskipper/flow) ⭐ 424 | 🐛 35 | 🌐 R | 📅 2026-08-08 - Visualize code flow and dependencies, including dependencies between Shiny app modules.
* [reactlog](https://github.com/rstudio/reactlog) ⭐ 131 | 🐛 26 | 🌐 JavaScript | 📅 2026-08-24 - Visual debugger for Shiny reactivity.
* [shinyobjects](https://github.com/rjake/shinyobjects) ⭐ 21 | 🐛 24 | 🌐 R | 📅 2022-06-03 - Access reactive data interactively to help debug reactive data frames and load assigned objects into local environment.
* [shinyStep](https://github.com/zhangh12/shinyStep) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-05-23 - Shiny modules for user-editable R functions with an Ace code editor, R console, and step debugger.

### Testing

* [shinytest](https://github.com/rstudio/shinytest) ⭐ 224 | 🐛 53 | 🌐 JavaScript | 📅 2024-05-28 - Automated testing for Shiny apps.
* [data.validator](https://github.com/Appsilon/data.validator) ⭐ 153 | 🐛 15 | 🌐 HTML | 📅 2024-04-18 - Validate dataset and generate a report.
* [shinytest2](https://github.com/rstudio/shinytest2) ⭐ 123 | 🐛 58 | 🌐 R | 📅 2026-07-15 - Automated unit testing of Shiny apps through a headless Chromium browser.
* [shinyloadtest](https://github.com/rstudio/shinyloadtest) ⭐ 112 | 🐛 34 | 🌐 HTML | 📅 2026-02-09 - Load testing for Shiny apps.
* [reactor](https://github.com/yonicd/reactor) ⭐ 58 | 🐛 1 | 🌐 R | 📅 2021-07-07 - Unit testing for Shiny reactivity.
* [shinyValidator](https://github.com/Novartis/shinyValidator) ⭐ 44 | 🐛 10 | 🌐 HTML | 📅 2023-08-10 - Audit Shiny apps at each commit.

### Profiling

* [profvis](https://github.com/r-lib/profvis) ⭐ 315 | 🐛 18 | 🌐 JavaScript | 📅 2026-02-13 - Interactive visualizations for profiling R code. [Profiling Shiny apps](https://profvis.r-lib.org/examples.html#example-3---profiling-a-shiny-application).
* [shiny.info](https://github.com/Appsilon/shiny.info) ⭐ 63 | 🐛 6 | 🌐 R | 📅 2024-04-18 - Displays simple diagnostic information of the Shiny project in the user interface of the app.
* [shiny.benchmark](https://github.com/Appsilon/shiny.benchmark) ⭐ 33 | 🐛 20 | 🌐 R | 📅 2024-04-18 - Measure and compare the performance of different versions of a Shiny application.
* [shiny.tictoc](https://github.com/Appsilon/shiny.tictoc) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-08 - Measure Shiny app performance in the browser.

### Scaling

* [promises](https://github.com/rstudio/promises) ⭐ 210 | 🐛 30 | 🌐 R | 📅 2026-06-27 - Promise-based asynchronous programming for R. [Using promises with Shiny](https://rstudio.github.io/promises/articles/shiny.html).
* [shiny.worker](https://github.com/Appsilon/shiny.worker) ⭐ 62 | 🐛 7 | 🌐 R | 📅 2023-12-15 - Delegate heavy computation tasks to a separate process in a Shiny application.
* [shinyParallel](https://github.com/jcrodriguez1989/shinyParallel) ⭐ 60 | 🐛 2 | 🌐 R | 📅 2021-06-23 - Run Shiny applications in a multi-session mode.
* [ipc](https://github.com/fellstat/ipc) ⭐ 54 | 🐛 3 | 🌐 R | 📅 2023-02-10 - Tools for message passing between processes, with Shiny-specific features for async progress bars and reactive value updates from futures.
* [jsplyr](https://github.com/r-world-devs/jsplyr) ⭐ 23 | 🐛 9 | 🌐 R | 📅 2026-07-17 - Dplyr backend for Shiny that lazily translates data wrangling verbs into client-side JavaScript and returns results asynchronously as promises.
* [FutureManager](https://github.com/Boehringer-Ingelheim/FutureManager) ⭐ 15 | 🐛 1 | 🌐 R | 📅 2021-06-11 - Background processes for long-running operations in Shiny applications.

### Monitoring and Analytics

* [shinylogs](https://github.com/dreamRs/shinylogs) ⭐ 101 | 🐛 9 | 🌐 R | 📅 2026-03-29 - Record everything that happens in a Shiny application, including inputs, outputs, errors, and session information.
* [shiny.telemetry](https://github.com/Appsilon/shiny.telemetry) ⭐ 76 | 🐛 23 | 🌐 R | 📅 2025-09-08 - Track events occurring on a user session and stores them in a local or remote database.
* [openmetrics](https://github.com/atheriel/openmetrics) ⭐ 36 | 🐛 3 | 🌐 R | 📅 2021-11-15 - An opinionated Prometheus client for R conforming to the OpenMetrics standard.
* [shinymetrics](https://github.com/devOpifex/shinymetrics) ⚠️ Archived - Track shiny applications with Shinymetrics, providing analytics and telemetry for Shiny applications.
* [titan](https://github.com/devOpifex/titan) ⭐ 27 | 🐛 0 | 🌐 HTML | 📅 2022-02-28 - Prometheus monitoring for Shiny applications, plumber APIs, and other R web services.
* [pRometheus](https://github.com/cfmack/pRometheus) ⭐ 21 | 🐛 5 | 🌐 R | 📅 2025-10-03 - A Prometheus client library for R, Plumber, and Shiny.
* [AzureAppInsights](https://github.com/stefanedwards/AzureAppInsights) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2021-10-01 - Include Azure Application Insights telemetry in Shiny apps.

## Miscellaneous

*Not necessarily an R package, but it helps.*

### UI Customization

* [metathis](https://github.com/gadenbuie/metathis) ⭐ 66 | 🐛 5 | 🌐 R | 📅 2026-05-16 - Add HTML metadata tags for Shiny apps and R Markdown documents.
* [shinybrowser](https://github.com/daattali/shinybrowser) ⭐ 40 | 🐛 3 | 🌐 R | 📅 2024-08-18 - Find out information about a user's web browser in Shiny.
* [shinyfullscreen](https://github.com/etiennebacher/shinyfullscreen) ⭐ 33 | 🐛 1 | 🌐 R | 📅 2023-04-20 - Display HTML elements on full screen using 'screenfull.js'.
* [favawesome](https://github.com/shinyworks/favawesome) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2024-11-07 - Use Font Awesome Icons as Shiny favicons.
* [hypothesis](https://github.com/r-world-devs/hypothesis) ⭐ 2 | 🐛 3 | 🌐 R | 📅 2023-12-21 - Add, share, and manage hypothes.is annotations in Shiny apps and R Markdown documents.
* [shinytitle](https://github.com/ashbaldry/shinytitle) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2021-06-15 - Update the browser window title dynamically in a Shiny session.
* [shinyseo](https://github.com/rolfmblindgren/shinyseo) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2026-07-20 - Inject SEO, Open Graph, Twitter, site verification, and schema.org metadata into Shiny apps.
* [Bootstrap Live Customizer](https://www.bootstrap-live-customizer.com/) - Customize Bootswatch themes (Bootstrap 3) to create your own Bootstrap themes.
* [google-webfonts-helper](https://gwfh.mranftl.com/fonts) - A hassle-free way to self-hosted Google Fonts, useful for air-gapped environments.
* [a11yShiny](https://gitlab.opencode.de/bmbf/datenlabor/a11yshiny) - Accessibility-enhanced replacements for popular Shiny UI functions.

### Dependency Resolution

* [renv](https://github.com/rstudio/renv) ⭐ 1,161 | 🐛 217 | 🌐 R | 📅 2026-08-28 - Create isolated, portable, and reproducible environments for R projects.
* [packrat](https://github.com/rstudio/packrat) ⭐ 409 | 🐛 231 | 🌐 R | 📅 2026-07-27 - Parse R package dependencies of Shiny apps with `packrat::appDependencies`.
* [sysreqsdb](https://github.com/r-hub/sysreqsdb) ⚠️ Archived - SystemRequirements mappings for R packages.
* [shinyapps-package-dependencies](https://github.com/rstudio/shinyapps-package-dependencies) ⭐ 79 | 🐛 86 | 🌐 R | 📅 2026-04-24 - A collection of bash scripts that install system dependencies for R packages.

### Editor Extensions

* [shiny-vscode](https://marketplace.visualstudio.com/items?itemName=posit.shiny) - VS Code extension to run Shiny apps (in R and Python) and create or save Shinylive links.
* [ShinyUiEditor](https://marketplace.visualstudio.com/items?itemName=Posit.shinyuieditor) - A visual tool for building the UI portion of a Shiny application that generates clean and human-readable code.
* [shinysnip](https://marketplace.visualstudio.com/items?itemName=Mohamed-El-Fodil-Ihaddaden.shinysnip) - Simple Shiny code snippets generator in VS Code.
* [textmate.rstheme](https://marketplace.visualstudio.com/items?itemName=nanxstats.textmate-rstheme) - A light theme for VS Code inspired by the TextMate (default) theme in RStudio IDE.

### Books

* [Mastering Shiny: Build Interactive Apps, Reports, and Dashboards Powered by R](https://mastering-shiny.org/)
* [Engineering Production-Grade Shiny Apps](https://engineering-shiny.org/)
* [JavaScript for R](https://book.javascript-for-r.com/)
* [Outstanding User Interfaces with Shiny](https://unleash-shiny.rinterface.com/)

### Videos / Screencasts

* [Shiny Developer Series](https://shinydevseries.com) - Interviews with practitioners & developers of Shiny and the broader ecosystem of Shiny packages, plus occasional live streams of Shiny app development in action.

## Shiny for Python

### Python - Theming

* [brand-yml](https://github.com/posit-dev/brand-yml) ⭐ 110 | 🐛 37 | 🌐 Python | 📅 2026-08-11 - Unified branding with `_brand.yml` files.
* [py-shinyswatch](https://github.com/posit-dev/py-shinyswatch) ⭐ 37 | 🐛 5 | 🌐 Python | 📅 2026-07-29 - Bootswatch themes for py-shiny.

### Python - UI Components

* [py-shinywidgets](https://github.com/posit-dev/py-shinywidgets) ⭐ 54 | 🐛 42 | 🌐 Python | 📅 2026-05-06 - Render ipywidgets inside a Shiny app.
* [py-htmltools](https://github.com/posit-dev/py-htmltools) ⭐ 24 | 🐛 30 | 🌐 Python | 📅 2026-08-14 - Tools for creating, manipulating, and writing HTML from Python.
* [py\_shiny\_semantic](https://github.com/Appsilon/py_shiny_semantic) ⭐ 12 | 🐛 4 | 🌐 Python | 📅 2023-12-15 - Create rich web applications in PyShiny using styles and components from Fomantic UI.
* [shinymedia](https://github.com/posit-dev/shinymedia) ⭐ 10 | 🐛 7 | 🌐 TypeScript | 📅 2025-08-15 - UI controls for recording video clips and playing audio media.
* [py-faicons](https://github.com/posit-dev/py-faicons) ⭐ 9 | 🐛 6 | 🌐 Python | 📅 2024-01-16 - An interface to Font Awesome for use in Shiny for Python.
* [py-shiny-validate](https://github.com/posit-dev/py-shiny-validate) ⭐ 6 | 🐛 8 | 🌐 JavaScript | 📅 2025-03-17 - Input validation for Shiny for Python applications.

### Python - Chat

* [shinychat](https://github.com/posit-dev/shinychat/tree/main/pkg-py) ⭐ 137 | 🐛 55 | 🌐 TypeScript | 📅 2026-08-28 - Chat UI component for Shiny for Python.
* [shinyrealtime](https://github.com/posit-dev/shinyrealtime) ⭐ 25 | 🐛 3 | 🌐 Python | 📅 2026-07-31 - Integrate OpenAI's Realtime API.

### Python - Table

* [great-tables](https://github.com/posit-dev/great-tables) ⭐ 2,724 | 🐛 103 | 🌐 Python | 📅 2026-08-24 - Create styled display tables in Python.
* [itables](https://github.com/mwouts/itables) ⭐ 972 | 🐛 40 | 🌐 Python | 📅 2026-08-21 - Display Pandas and Polars data frames as interactive DataTables that you can sort, paginate, scroll, and filter.
* [gt-extras](https://github.com/posit-dev/gt-extras) ⭐ 102 | 🐛 32 | 🌐 Python | 📅 2025-11-03 - Additional helper functions for enhancing great-tables tables.
* [reactable-py](https://github.com/machow/reactable-py) ⭐ 88 | 🐛 28 | 🌐 JavaScript | 📅 2025-10-10 - Interactive data tables for Python, port of the R package reactable.

### Python - Frameworks

* [Tapyr](https://github.com/Appsilon/tapyr-template) ⭐ 45 | 🐛 5 | 🌐 Python | 📅 2026-03-18 - Shiny for Python application template.

### Python - Deploy

* [py-shinylive](https://github.com/posit-dev/py-shinylive) ⭐ 56 | 🐛 11 | 🌐 Python | 📅 2026-07-29 - Export Shiny applications as Shinylive applications.
* [rsconnect-python](https://github.com/posit-dev/rsconnect-python) ⭐ 37 | 🐛 93 | 🌐 Python | 📅 2026-08-28 - CLI for interacting with and deploying to Posit Connect.

### Python - Persistent Data Storage

* [pins-python](https://github.com/rstudio/pins-python) ⭐ 58 | 🐛 65 | 🌐 Python | 📅 2026-07-14 - Publish data, models, and other Python objects for sharing across projects and with colleagues.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
