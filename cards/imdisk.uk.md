# `imdisk.sys`

[Назад до індексу](../README.uk.md) · [English version](imdisk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9840607B61897ACBC5AF13F12D013494D0507E0A80E9BE063525BCB22369B560` | `409E03F912D7822DFE63DA2CD739BF92A2563C73` | `E8F81F9BA6245ECAE906957117CD7204` |

## Метадані

- **Ім'я файлу:** `imdisk.sys`
- **Розмір:** 63976 bytes
- **Архітектура:** 0x8664
- **Компанія:** Olof Lagerkvist
- **Продукт:** imdisk
- **Опис:** ImDisk Virtual Disk Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
