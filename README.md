# my-eslint-prettier-config
This is my config for eslint and prettier for a react project created with CRA using VSC.

## Configuring steps

1. Install dev dependencies into proyect

    > npm install eslint eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier --save-dev

2. install VSC extensions
    - Prettier - Code formatter
    - ESLint

3. Create .eslintrc file
    ```
    {
      "extends": ["react-app", "react-app/jest", "prettier"]
    }
    ```
4. Create .prettierrc file
    ```
    {
      "tabWidth": 2,
      "useTabs": false,
      "semi": true,
      "singleQuote": true,
      "bracketSpacing": true
    }
    ```
5. Modify settings.json in VSC
    ```
    {
      "editor.formatOnSave": true,
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
    ```

[Referencies](https://www.youtube.com/watch?v=xinJSYiOB6Q)
