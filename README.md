# Prettier Configuration

Prettier config files with rules to be used in all Angular projects.

1. Copy files below into root of Angular project
    - .editorconfig
    - .prettierignore
    - .prettierrc.json
2. Add tslint-config-prettier to packages with `npm i --save-dev tslint-config-prettier`
3. Update the tslint.json file to include `tslint-config-prettier` in the extends array
    ```
    {
        "extends": [
            "tslint:recommended",
            "tslint-config-prettier"
        ]
    }
    ```
4. Make sure prettier is installed globally with `npm i prettier -g` and run `prettier --write "./**/*.{js,json,ts}` at the root of the Angular project to update all existing files

You can walkthrough setting up Prettier in Visual Studio Code with me at https://youtu.be/5rabp1QFLXE.
