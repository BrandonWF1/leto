# Лето в городе для организаторов

## Описание проекта

Проект представляет собой платформу, предоставляющую возможность организовать мероприятие на летней площадке в Москве и МО. 
Основные функциональности включают в себя: выбор места для мероприятия с возможностью фильтрации и картой, выбор дополнительных опций и формата мероприятия, форма для бронирования и оплаты. Пользователи могут фильтровать площадки, искать подходящее место на карте, а также просматривать детальную информацию по каждому пространству, переходя на соответствующую детальную страницу.

## Назначение проекта

Этот проект был разработан с целью предоставления удобного и интуитивно понятного инструмента для организации летних мероприятий в Москве.

## Галерея

Проект в данный момент неактивен, так как является сезонным.

## Моя роль в проекте

В рамках данного проекта я отвечал за запуск проект и полную разработку Front-end части. Мои обязанности включали в себя проектирование, оценка и реализация пользовательского интерфейса и обеспечение его корректного взаимодействия с серверной частью. 
Я тесно сотрудничал с Backend-разработчиками, аналитиками, дизайнерами и тестировщиками, чтобы ускоирть разработку. Нам удалось в кратчайшие сроки реализовать полностью новый проект и запустить его.

## Технологии, используемые в проекте

  ![NextJS](https://img.shields.io/badge/-NextJS-black?style=for-the-badge&logo=next.js)
  ![Typescript](https://img.shields.io/badge/-Typescript-white?style=for-the-badge&logo=typescript)
  ![SCSS](https://img.shields.io/badge/-SCSS-pink?style=for-the-badge&logo=sass)
  ![Redux Toolkit](https://img.shields.io/badge/-Redux_Toolkit-purple?style=for-the-badge&logo=redux)
  
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
    "ecmaVersion": 2021,
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
    "prettier",
    "next/core-web-vitals",
    "plugin:sonarjs/recommended"
  ],
  "plugins": ["@typescript-eslint", "react-hooks", "jsx-a11y", "unused-imports", "sonarjs"],
  "rules": {
    "sonarjs/prefer-immediate-return": "warn",
    "sonarjs/cognitive-complexity": ["warn", 15],
    "sonarjs/no-duplicate-string": "warn",
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
    "react/destructuring-assignment": 1,
    "unused-imports/no-unused-imports": "error"
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
- Общее количество человек: 22 (2 команды)
- Роли в команде:
  - Front-end разработчиков: 4
  - Back-end разработчиков: 4
  - Дизайнеров: 2
  - Тестировщиков: 4
  - Lead: 2
  - Аналитиков: 4
  - Product & Project Managment: 4
    
# Основные достижения и результаты
- **Тесное межкомандное взаимодействие**: Ежедневные стендапы, дополнительные созвоны с разработчикам из другой команды, совместное код-ревью, а также внедрение единых стандартов написания кода, чтобы минимизировать недопонимание.
- **Создание полностью нового масштабного проекта за 2 недели**: Проект был успешно запущен в срок, несмотря на все сложности и переработки.
- **Быстрая и слаженная работа разработки и тестирования**: Мы смогли организовать процесс параллельной разработки и тестирования, что значительно ускорило выпуск проекта.

## Особые вызовы и преодоленные препятствия

- **Крайне сжатые сроки**:
  
Проект требовалось запустить в рекордные сроки — всего за 2 недели.
Задачи были разбиты на мелкие этапы и приоритизированы, чтобы команды могла работать максимально эффективно.
Как представитель ведущей команды, лично взял на себя ответственность за самые сложные компоненты, такие как интерактивная карта и система фильтров.

- **Переработки**:

Из-за сжатых сроков приходилось работать сверхурочно, чтобы успеть завершить проект в срок.

– **Организация работы двух команд**:

Проект разрабатывался силами двух команд, что требовало четкой координации и синхронизации.
Мы наладили регулярные встречи между командами для обсуждения прогресса и решения возникающих вопросов.

## Ссылки

- **Проект**: [go.mos.ru/ploschadki-dlya-organizatorov.](https://go.mos.ru/ploschadki-dlya-organizatorov/)
- **Код проекта**: Код находится под защитой соглашения о неразглашении (NDA), из-за чего, к сожалению, не может быть предоставлен для общего доступа или просмотра.
