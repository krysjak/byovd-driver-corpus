# `Apfiltr_1.sys`

[Назад до індексу](../README.uk.md) · [English version](Apfiltr_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D0973CC3C08726715B6C116E25539F79BD1960CF746ACFE668B7789EB04BF58` | `07F423D96F9A82BF915A0B66300AA58DA80CC1B5` | `0ECE1F5364EF287EAFC728880D2CA0E9` |

## Метадані

- **Ім'я файлу:** `Apfiltr_1.sys`
- **Розмір:** 610048 bytes
- **Архітектура:** 0x8664
- **Компанія:** Alps Electric Co., Ltd.
- **Продукт:** Alps Touch Pad Driver
- **Опис:** Alps Touch Pad Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
