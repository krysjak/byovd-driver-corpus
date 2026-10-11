# `bcmwl63a_2.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63a_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2F23CF298A7FE8D792F7010AE8F8B21A6538D0EF272EB26BBCF0D50D4998870F` | `9391C2EFBF98DF64CF1B13FF7F0F687FA60C3B46` | `924C5566BB6849EF83C8273AB71EC692` |

## Метадані

- **Ім'я файлу:** `bcmwl63a_2.sys`
- **Розмір:** 11762944 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Corp
- **Продукт:** Broadcom WiFi Driver wireless driver
- **Опис:** Broadcom WiFi Driver wireless driver
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
