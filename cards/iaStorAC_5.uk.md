# `iaStorAC_5.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FFE95ED5BCF8EC721B36221C4383E0D0FC698D1B8335589170B6A99CBE92A538` | `1231FBB2A76A523F9A501F0CC81992280B11476E` | `27994B3B42EDDC5BB1DB4E8BAF3FC151` |

## Метадані

- **Ім'я файлу:** `iaStorAC_5.sys`
- **Розмір:** 1017712 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
