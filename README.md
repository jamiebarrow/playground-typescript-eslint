# playground-typescript-eslint

A place to play around with TypeScript ESLint plugin.

## Getting Started

The below steps are outlined in the Getting Started guide in the TypeScript ESLint website.

1. Installation of TypeScript, ESLint and the TypeScript ESLint plugin.

    ```shell
    npm install --save-dev @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint typescript
    ```

2. Configuration through `.eslintrc.json` configuration file in the root of the project.

    ```json
    {
        "root": true,
        "extends": ["eslint:recommended", "plugin:@typescript-eslint/recommended"],
        "parser": "@typescript-eslint/parser",
        "plugins": ["@typescript-eslint"],
    }
    ```

3. Running ESLint in the root of the project.

    ```shell
    npx eslint .
    ```

## References

- [Github](https://github.com/typescript-eslint/typescript-eslint)
- [Docs](https://typescript-eslint.io/docs/)
- [Docs > Rules](https://typescript-eslint.io/rules/)