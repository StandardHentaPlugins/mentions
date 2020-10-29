# HENTA Плагин: common/mentions [![Build Status](https://travis-ci.com/StandardHentaPlugins/mentions.svg?branch=master)](https://travis-ci.com/StandardHentaPlugins/mentions)
Обращения к боту в беседах.

```js
const mentionsPlugin = henta.getPlugin('common/mentions');
```

## Включение
Чтобы плагин работал нужно указать handler ***check-mentions*** в конфиге bot.json. Рекомендуется указывать этот обработчик первым в списке.

## Настройка обращений
Все обращения настраиваются в public.json в поле mentions. Обращения пишутся строго в нижнем регистре, от самого длинного к самому короткому.

```json
{
  "mentions": [ "msk", "мск", "/" ]
}
```