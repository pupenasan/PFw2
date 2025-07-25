# Глобальна змінна PFwCFG 

## Загальний опис

Змінна `PFwCFG` призначена для: 

- збереження конфігураційних параметрів для всього ПЛК
- збереження `DUMMY` змінних (болванок)
-  

| name     | type/bit  | descr                | note          |
| -------- | --------- | -------------------- | ------------- |
| TSKCNT   | UINT      | кількість задач      |               |
| ANMB     | UINT      | номер останньої зони | 0 - одна зона |
| TMPDIVAR | DIVAR_CFG |                      |               |
| TMPAIVAR | AIVAR_CFG |                      |               |
| TMPDOVAR | DOVAR_CFG |                      |               |
| TMPAOVAR | AOVAR_CFG |                      |               |