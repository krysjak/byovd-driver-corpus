# `IntcOED_9.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B3CF1AEB96F2E92E265A55FAEBD84C71DD958C6D037BB5A9FC994A92758BFC38` | `46FC5959B2BB673D32C156A47A1B84014226481F` | `BF63C148FD3C50EDF6F5BAD740270D90` |

## Метадані

- **Ім'я файлу:** `IntcOED_9.sys`
- **Розмір:** 1278200 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) OED
- **Опис:** Intel® Smart Sound Technology (Intel® SST) OED
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
