# `snxpserx.sys`

[Назад до індексу](../README.uk.md) · [English version](snxpserx.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C75C74BD1929CB4D1E589C9FC7228224C5FDAE835610CB8AA53BDD3CBAE9AC7` | `AB07B6B292E32E59E67B60842E1AB14ABEF623F8` | `58BC27E1765EFC90ACB0413C4F08306D` |

## Метадані

- **Ім'я файлу:** `snxpserx.sys`
- **Розмір:** 93088 bytes
- **Архітектура:** 0x14c
- **Компанія:** SUNIX Co., Ltd.
- **Продукт:** SUNIX Multi I/O Card
- **Опис:** SUNIX Serial Driver (x86)
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 90

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
