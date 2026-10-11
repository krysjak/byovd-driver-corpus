# `bcmwl63a_1.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63a_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3581B68F147D37BE4B482A18291E91AAD8340A1BF512485FD87508EB435EB0DF` | `7E016D0DCD721EE96F1334E5C6DA1093002AB9F2` | `1465EFCC24785AF61D24E791E285CA09` |

## Метадані

- **Ім'я файлу:** `bcmwl63a_1.sys`
- **Розмір:** 11703560 bytes
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
