# `bcmwl63_1.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0C05EF5C9028D374FF1D91993AD5A2C83CEEC3588AE119A550781E9906EACA9B` | `92050E7A357175B2ECC50126617113E32EE38025` | `E8B2717A4387C7E57FE771F84C18A6DE` |

## Метадані

- **Ім'я файлу:** `bcmwl63_1.sys`
- **Розмір:** 10866944 bytes
- **Архітектура:** 0x14c
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
