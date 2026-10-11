# `iaStorAVC.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAVC.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A46A34E6DC1573D29B87AD22B336C6A7358A657A416B1643C0D3DAD671D81692` | `AD6BE9C81E05628AF93FF3BA070EDCCE381F8422` | `76B3DFB22C302DBA9FA58C62D9668D04` |

## Метадані

- **Ім'я файлу:** `iaStorAVC.sys` (Ідентичні копії: `iaStorAVC_1.sys`)
- **Розмір:** 885568 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver (inbox)
- **Опис:** Intel(R) Rapid Storage Technology driver (inbox) - x64
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
