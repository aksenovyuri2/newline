# Бустра · финансовый маркетплейс

Главная страница финансового маркетплейса Бустра.

## Превью

Открыть `index.html` напрямую в браузере или через локальный сервер:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Бренд-система

```
Background       #F4EFE6   warm sand
Surface          #FFFFFF
Surface warm     #FAF7F0
Ink              #15282C   warm dark
Hairline         #DCD3C0

Primary (loans)  #1F4E5F   deep petrol
Primary deep    #163A47
Primary soft     #E5EFF1

Copper           #A0876A   warm details
Forest           #2D4A30   trust ribbon
```

**Типографика:** Manrope 800 для display, Inter 500/400 для body.

## Регуляторика

- В реестре финансовых маркетплейсов Банка России
- 353-ФЗ — раскрытие ПСК
- 156-ФЗ — отдельное согласие на запрос в БКИ
- 152-ФЗ — обработка персональных данных

Без «без отказа», без фейковых таймеров, без pre-checked согласий.

## Структура

- `index.html` — главная страница (segment-switcher hero, без калькулятора)
