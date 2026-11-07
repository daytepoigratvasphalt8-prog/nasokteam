# NasokTeam — сайт

Сайт команды NasokTeam: Nasok Launcher, Nasok Server, Nasok Installer, моды, CaseLab и заказы плагинов.

**Открыть:** https://daytepoigratvasphalt8-prog.github.io/nasokteam/

## Как поменять ссылки

Все ссылки собраны в одном месте — в конце `index.html`, объект `LINKS`:

```js
const LINKS = {
  telegram: "https://t.me/NasokTeamHab",
  launcher: "https://t.me/NasokTeamHab",   // прямая ссылка на скачивание лаунчера
  caselab: "https://daytepoigratvasphalt8-prog.github.io/caselab/",
  funpay: ""                                // ссылка на ваши лоты FunPay — появится кнопка «Заказать на FunPay»
};
```

Тексты проектов правятся прямо в `index.html`, всё на одной странице, без сборки.
