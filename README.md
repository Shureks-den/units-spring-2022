# units-spring-2022
Семинар №1 - Юнит-тесты на TypeScript

**Перед установкой убедитесь, что у вас установлен npm**

**Установить проект:**

- форкаем репозиторий
- клонируем и переходим в папку проекта `cd units-spring-2022`
- проверяем версию ноды `node -v`. подходят 14, 16 версии, если ниже - лучше обновите.
- выполняем `npm ci`

**Запустить проект:**

- `npm start`

**Запустить тесты:**

- прогон тестов `npm run test`
- покрытие `npm run test-coverage`
- обновить снапшоты `npm run test-update-snap`
- линтер `npm run lint`
- линтер с фиксом ошибок `npm run lint --fix`

**Документация по тестам:**

https://create-react-app.dev/docs/running-tests

_jest:_

https://jestjs.io/docs/ru/getting-started

https://jestjs.io/docs/ru/expect

_jest моки:_

https://jestjs.io/docs/ru/bypassing-module-mocks

_enzyme:_

https://enzymejs.github.io/enzyme/

https://medium.com/@acesmndr/testing-react-functional-components-with-hooks-using-enzyme-f732124d320a

**Условия сдачи практики:**

1. Написать юнит-тесты на каждую функцию в sortOrders
    - используйте [test.each](https://jestjs.io/docs/en/api#testeachtablename-fn-timeout) для одинаковых выходных значений
2. **Замокать** функцию getDate и написать юнит-тесты на компонент Order. Не забудьте сбросить/очистить замоканное.
3. Добиться покрытия не менее 90% по всем модулям
4. Соблюсти принципы автоматизации и не применить анти-паттерны
5. Скинуть пулл-реквест с пройденным ci (укажите имя и фамилию в названии ПР) до конца семинара в [таблицу](https://docs.google.com/spreadsheets/d/1Yp26pHnBmF7a6jXQmM3fj-k0Jw17dBntnN1aoIlcOZ4/edit?usp=sharing) и пройти ревью своих коллег (исправить все замечания и получить 2 апрува)
6. Выбрать себе минимум 2 пулл-реквеста на проверку, указать свое имя в графе "Проверяющий №_".
7. После получения апрувов по ревью написать [@emdobryanskaya](https://t.me/emdobryanskaya), чтобы получить баллы.
