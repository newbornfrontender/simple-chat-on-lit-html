<h1 align="center">Простой чат на lit-html</h1>

Это простой чат, базирующийся на Twilio Chat. В качестве инструментов сборки выступают: parcel-bundler, TypeScript, lit-html

> В качестве менеджера пакетов используется Yarn

<h2 align="center">Мотив</h2>

Данное приложение создано для проверки возможностей lit-html

<h2 align="center">Команды</h2>

<table>
  <thead>
    <tr>
      <th>Команда</th>
      <th>Описание</th>
    </tr>
  </thead>
  <tbody>
    <!-- Команда: clean -->
    <tr>
      <td>
        <code>$ yarn clean</code>
      </td>
      <td>Удаляет ".cache" и "dist" директории</td>
    </tr>
    <!-- Команда: move -->
    <tr>
      <td>
        <code>$ yarn move</code>
      </td>
      <td>Переносит статические ресурсы в "dist" директорию</td>
    </tr>
    <!-- Подтаблица: TSLint -->
    <tr>
      <td colspan="2">
        <p align="center">
          <b>TSLint</b>
        </p>
        <blockquote>
          <p>TSLint - это расширяемый инструмент статического анализа, который проверяет TypeScript код на удобочитаемость, наличие функциональных ошибок и способен исправлять их</p>
        </blockquote>
        <table>
          <thead>
            <tr>
              <th>Команда</th>
              <th>Описание</th>
            </tr>
          </thead>
          <tbody>
            <!-- Команда: tslint:check -->
            <tr>
              <td>
                <code>$ yarn tslint:check</code>
              </td>
              <td>Проверяет "tslint.json" на наличие конфликтующих правил</td>
            </tr>
          </tbody>
        </table>
      </td>
    </tr>
    <!-- Подтаблица: Prettier -->
    <tr>
      <td colspan="2">
        <p align="center">
          <b>Prettier</b>
        </p>
        <blockquote>
          <p>Prettier - инструмент форматирования кода c поддержкой множества языков, минимумом конфигурации и максимумом навязанных правил</p>
        </blockquote>
        <table>
          <thead>
            <tr>
              <th>Команда</th>
              <th>Описание</th>
            </tr>
          </thead>
          <tbody>
            <!-- Команда: prettier:list -->
            <tr>
              <td>
                <code>$ yarn prettier:list</code>
              </td>
              <td>Выводит список файлов, которые можно отформатировать</td>
            </tr>
          </tbody>
        </table>
      </td>
    </tr>
    <!-- Команда: serve -->
    <tr>
      <td>
        <code>$ yarn serve</code>
      </td>
      <td>Запускает сервер разработки с горячей перезагрузкой</td>
    </tr>
    <!-- Команда: build -->
    <tr>
      <td>
        <code>$ yarn build</code>
      </td>
      <td>Собирает и минифицирует приложение для публикации</td>
    </tr>
  </tbody>
</table>

<h2 align="center">Лицензия</h2>

[MIT](/LICENSE)
