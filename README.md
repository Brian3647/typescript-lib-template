# A template ready to publish

This template includes licensing, custom packaging of the module, linting and formatting

Replace "TODO" and "todo" across the files to customize everything

## Warning

**Do _NOT_ run `yarn publish` nor `npm publish` in the base directory. Run it in the `dist` folder when the project is compiled instead.**

## Scripts

_Recommended use of yarn_

Use `yarn <script>` where `<script>` is one of the following:

- `lint` Lints the project with ESLint. You can change the linting config in `.eslintrc.json`
- `build` Builds the project and generates the `dist` folder. You can use `npm publish` after running this command to publish the module.
- `fmt` Formats the entire code with prettier. You can change the formatting rules in `.prettierrc`
