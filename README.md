# typescript-npm-module
base npm module as typescript

## NPM Login before deploy
```bash
npm login --scope=@{Github_Account} --registry=https://npm.pkg.github.com
```
Input below value for this command.

- Username: {Github_Account}
- Password: {Github_Token}
- Email: {Your_Email}

## NPM deploy
```bash
npm deploy
```