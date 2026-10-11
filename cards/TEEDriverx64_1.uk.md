# `TEEDriverx64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverx64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4158BE66A9DED8555FD62844EDE908B7B5C64DEDA55B32BFC8BDE3534B0ABA91` | `8E5667C32DE29B689B194FC810BF82438BA2C0BE` | `124B5296DF58E1F0ED3E9122431B136D` |

## Метадані

- **Ім'я файлу:** `TEEDriverx64_1.sys`
- **Розмір:** 178976 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
