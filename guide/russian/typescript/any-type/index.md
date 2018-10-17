---
title: Any Type
localeTitle: Любой тип
---
# Любой тип

Любой тип инструктирует Typcript приостанавливать проверку типов для указанных переменных. Полезно при работе с динамическим контентом, для которого вы не знаете тип, и для перехода вашей кодовой базы на Javascript на машинописный текст. Вы можете использовать неявный ввод Javascript с переменными, объявленными с типом Any.

```typescript
  let notSure: any = 4; 
  notSure = "maybe a string instead"; 
  notSure = false; 

```