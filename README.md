# lessons-js-core

**[figma](https://www.figma.com/file/uvOH3bGfmJ6rfvgOnQy4RC/SBER-%E2%80%93-%D0%A8%D0%BA%D0%BE%D0%BB%D0%B0-JS?node-id=6%3A16)**

# command Node.js
```
1. node -v # версия
2. node <pathToJS> # запуск JS скрипта
3. node # запуск в консоли
```

# npm

```
1. npm init создать проект
2. npm install <package name>
3. npm uninstall <package name>
4. npm run <script name>
```

npx - execute npm package binaries
./node_modules/.bin/<package>

### before run project install all package
```
npm install
```
# steps:
```
1. Prettier — это средство для форматирования кода, которое нацелено на использование жёстко заданных правил по оформлению программ.
   https://prettier.io/docs/en/install.html
   1. npm install --save-dev --save-exact prettier
   2. echo {}> .prettierrc.json
   3. npx prettier --write .
2. husky - встроенные хуки Git, улучшает коммиты
   1. npm install husky --save-dev
   2. npx husky install
   3. npx husky add .husky/pre-commit "<your script>"
3. lint-staged - пакет Lint-staged позволяет проверять с помощью линтера индексированные файлы, что помогает предотвратить отправку в репозиторий кода с ошибками.
   https://github.com/okonet/lint-staged
   1. npm install --save-dev lint-staged
   2. create file .lintstagedrc.json - it's template for files
   3. add run lint-staged in .husky/pre-commit
         npm run lint-staged
      create script in package.json
         "lint-staged": "lint-staged"
```  

                 
