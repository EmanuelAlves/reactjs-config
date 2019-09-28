# reactjs-config
Guide for creating a *reactjs* application


```yarn create react-app my-app```

* no parckge.json remover o "eslintConfig"

* vscode .editconfig

```yarn add eslint -D```

```yarn eslint --init```

```yarn add prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D ```

* abrir o .eslintrc.js
* colocar no extends: 'prettier', 'prettier/react'
* adcionar "parser: 'babel-eslint'"
* dentro dos plugins: 'prettier'
* rules: 
```
rules: {
    'prettier/prettier': 'error',
    'react/jsx-filename-extension':[
        'warn',
        { extensions: ['.jsx', '.js'] }
    ],
    'import/prefer-default-export': 'off'
   }
```


* criar o arquivo .prettierrc
* adicionar: 
```
{
    "singleQuote": true,
    "trailingComma": "es5"
}
```
