# Template Project

This is a template project for building an HTML site with SCSS.

## Project Structure

```
.gitignore
index.html
package.json
README.md
src/
    scss/
        abstracts/
            _functions.scss
            _mixins.scss
            _variables.scss
        base/
            _generic.scss
            _reset.scss
            _typography.scss
        components/
            _buttons.scss
            _cards.scss
            _forms.scss
        layout/
            _footer.scss
            _grid.scss
            _header.scss
            _navigation.scss
        main.scss
        pages/
            _about.scss
            _home.scss
        themes/
            _dark.scss
            _light.scss
        vendors/
            _third-party.scss
```

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mladjom/template.git
   cd template
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

### Usage

#### Building CSS

To build the CSS from the SCSS source files, run:
```bash
npm run build:css
```

#### Watching for Changes

To watch for changes in the SCSS files and automatically build the CSS, run:
```bash
npm run watch:css
```

#### Post-processing CSS

To run PostCSS with autoprefixer on the built CSS file, run:
```bash
npm run postcss
```

#### Purging Unused CSS

To remove unused CSS from the final build, run:
```bash
npm run purgecss
```

### Project Structure

- `src/scss/abstracts`: Contains SCSS functions, mixins, and variables.
- `src/scss/base`: Contains base styles such as resets and typography.
- `src/scss/components`: Contains styles for individual components like buttons, cards, and forms.
- `src/scss/layout`: Contains layout-related styles such as grid, header, footer, and navigation.
- `src/scss/pages`: Contains styles specific to individual pages.
- `src/scss/themes`: Contains theme-related styles.
- `src/scss/vendors`: Contains styles from third-party libraries.

### License

This project is licensed under the ISC License.