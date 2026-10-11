# `iaStorAC_3.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A19FAB6A0246C3FF0702331DD90B9B624953AC7143237A3D6CC8A3BB6F1EEC1B` | `F23563C4DA34A80AD416DB5B77379D9599C23042` | `2BAEBB93462A50A4348A72479553ACEB` |

## Метадані

- **Ім'я файлу:** `iaStorAC_3.sys`
- **Розмір:** 1547496 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
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
