// prettier 

установить расширения в VS Code

ctrl + shift + p, выбираем open settings Json

вписать настройки:

"editor.defaultFormatter": "esbenp.prettier-vscode",
"[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"prettier.tabWidth": 2,
"prettier.singleQuote": true,
"prettier.trailingComma": "all",
"prettier.semi": true,
"prettier.jsxBracketSameLine": true,
"prettier.printWidth": 100,
"editor.formatOnSave": true,

// npm install scss