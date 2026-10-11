# `AtihdWT6_1.sys`

[Назад до індексу](../README.uk.md) · [English version](AtihdWT6_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C2CC65D95969206710A0B671EF50C74FF5CEA89873778362ECC76975490B2ED` | `9E69E51E9647E4AE6455C92954C8F3E8CC8CC19B` | `E4E2AAD101A16EE511B73F251A1686E5` |

## Метадані

- **Ім'я файлу:** `AtihdWT6_1.sys` (Ідентичні копії: `AtihdWT6_2.sys`)
- **Розмір:** 259992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
