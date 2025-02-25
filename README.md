# Лето в городе для организаторов

## Описание проекта

Проект представляет собой платформу, предоставляющую возможность организовать мероприятие на летней площадку в Москве и МО. Основные функциональности включают в себя: выбор места для мероприятия с возможностью фильтрации и картой, выбор дополнительных опций и формата мероприятия, форма для бронирования и оплаты. Пользователи могут фильтровать площадки, искать подходящее место на карте, а также просматривать детальную информацию по каждому пространству, переходя на соответствующую детальную страницу.

## Назначение проекта

Этот проект был разработан с целью предоставления удобного и интуитивно понятного инструмента для организации летних мероприятий в Москве.

## Галерея

Проект в данный момент неактивен, так как является сезонным.

## Моя роль в проекте

В рамках данного проекта я отвечал за запуск проект и полную разработку Front-end части. Мои обязанности включали в себя проектирование, оценка и реализация пользовательского интерфейса, обеспечение его корректного взаимодействия с серверной частью. 
Я тесно сотрудничал с Backend-разработчиками, аналитиками, дизайнерами и тестировщиками, чтобы быстро реализовать проект. Нам удалось в кратчайшие сроки реализовать полностью новый проект и запустить его.

## Технологии, используемые в проекте

  ![NextJS](https://img.shields.io/badge/-NextJS-black?style=for-the-badge&logo=next.js)
  ![Typescript](https://img.shields.io/badge/-Typescript-white?style=for-the-badge&logo=typescript)
  ![SCSS](https://img.shields.io/badge/-SCSS-pink?style=for-the-badge&logo=sass)
  ![Redux Toolkit](https://img.shields.io/badge/-Redux_Toolkit-purple?style=for-the-badge&logo=redux)
  ![Reakit](https://img.shields.io/badge/-Ant_Design-blue?style=for-the-badge&logo=antdesign)

## Принципы и инструменты разработки
- Код-стиль и форматирование: Prettier
- Система контроля версий: Git + GitLab
- Прочие инструменты: maki (Собственная devOps разработка), Cypress, Sonar
- Линтер: ESLint
  <details>
  <summary>Конфиг linter`а</summary>
  
  ```javascript
  {
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": 2018,
    "ecmaFeatures": {
      "jsx": true
    },
    "useJSXTextNode": true
  },
  "env": {
    "browser": true,
    "node": true,
    "commonjs": true,
    "jest": true
  },
  "extends": [
    "plugin:@typescript-eslint/recommended",
    "react-app",
    "airbnb",
    "prettier"
  ],
  "plugins": ["@typescript-eslint", "react-hooks", "jsx-a11y"],
  "rules": {
    "no-use-before-define": 0,
    "react/require-default-props": 0,
    "@typescript-eslint/ban-ts-ignore": 0,
    "no-shadow": 0,
    "arrow-body-style": "warn",
    "@typescript-eslint/ban-types":0,
    "@typescript-eslint/ban-ts-comment":0,
    "@typescript-eslint/no-unused-vars": 1,
    "@typescript-eslint/no-empty-function": 1,
    "@typescript-eslint/no-use-before-define": 2,
    "@typescript-eslint/no-explicit-any": [2, {"ignoreRestArgs": false}],
    "@typescript-eslint/interface-name-prefix": 0,
    "@typescript-eslint/explicit-member-accessibility": 0,
    "import/no-extraneous-dependencies": [2, { "devDependencies": true }],
    "spaced-comment": ["error", "always", { "markers": ["/"] }],
    "react/jsx-filename-extension": [
      1,
      { "extensions": [".js", ".jsx", ".tsx"] }
    ],
    "react-hooks/rules-of-hooks": "error",
    "react-hooks/exhaustive-deps": "warn",
    "@typescript-eslint/explicit-function-return-type": 0,
    "@typescript-eslint/prefer-function-type": 2,
    "no-param-reassign": ["error", { "props": true, "ignorePropertyModificationsFor": ["state"] }],
    "jsx-a11y/label-has-associated-control": [
      2,
      {
        "labelComponents": ["CustomInputLabel"],
        "labelAttributes": ["label"],
        "controlComponents": ["CustomInput"],
        "depth": 3
      }
    ],
    "jsx-a11y/label-has-for": 0,
    "react/jsx-props-no-spreading": 0,
    "import/extensions": ["error", "ignorePackages", {
        "js": "never",
        "jsx": "never",
        "ts": "never",
        "tsx": "never"
      }
    ],
    "react/destructuring-assignment": 1
  },
  "overrides": [
    {
      "files": ["*.js"],
      "rules": {
        "@typescript-eslint/no-var-requires": "off"
      }
    },
    {
      "files": ["style.ts"],
      "rules": {
        "import/no-unresolved": 0
      }
    },
    {
      "files": ["*.ts", "*.tsx"],
      "rules": {
        "no-undef": 0
      }
    }
  ],
  "settings": {
    "import/resolver": {
      "node": {
        "extensions": [".js", ".jsx", ".ts", ".tsx"]
      }
    }
  }
</details>

## Команда
- Общее количество человек: 12
- Роли в команде:
  - Разработчиков: 4
  - Дизайнеров: 1
  - Тестировщиков: 2
  - Lead: 1
  - Аналитиков: 2
  - Product & Project Managment: 2
    
# Основные достижения и результаты



## Особые вызовы и преодоленные препятствия

- **Пожар по дедлайнам**:

## Ссылки

- **Проект**: [go.mos.ru/ploschadki-dlya-organizatorov.](https://go.mos.ru/ploschadki-dlya-organizatorov/)
- **Код проекта**: Код находится под защитой соглашения о неразглашении (NDA), из-за чего, к сожалению, не может быть предоставлен для общего доступа или просмотра.
