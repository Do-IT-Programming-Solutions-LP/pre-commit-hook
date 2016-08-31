# Pre commit hook

There is a [overcommit's](https://github.com/brigade/overcommit) pre-commit hook that runs [Semistandard](https://github.com/Flet/semistandard) and [ESLint](https://github.com/eslint/eslint) with [AirBnb config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb).
Also it fixes (as much as possible, of course) code style and lint errors before checking, so you may not worry about missing semicolons and spaces ;)
 
To install it:
1) Install SemiStandard globally
2) Install EsLint globally
3) Install overcommit
4) Add lint rules for technologies that you are using

### Issues: ###

Rule for "import/no-extraneous-dependencies": "off" is temporary solution; remofe it when [this](https://github.com/clayne11/eslint-import-resolver-meteor/issues/11) issue will be closed