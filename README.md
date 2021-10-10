### Welcome
## ESLint + Prettier config

It's a simple config for my projects. 

On package.json: 

<
"scripts":{
    "lint": "eslint --ignore-path .gitignore .",
    "lint:fix": "eslint --ignore-path .gitignore --fix ."
}
>

And create a file named 
<
.eslintrc
>

And :

<
{
    "extends": ["nbiondini"]
}
>