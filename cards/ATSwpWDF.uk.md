# `ATSwpWDF.sys`

[Назад до індексу](../README.uk.md) · [English version](ATSwpWDF.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `250FE2B40D9FC73574358858D3922DFD6EE3219E2A8008D786D1D23015E681AC` | `8AEBD5AF8A32EE8280253B13604CD2BEE1C10E5E` | `D8ED748B592CE1374D1DA69CE44E2719` |

## Метадані

- **Ім'я файлу:** `ATSwpWDF.sys`
- **Розмір:** 542880 bytes
- **Архітектура:** 0x14c
- **Компанія:** AuthenTec, Inc.
- **Продукт:**  Swipe Fingerprint Sensor WDF USB Driver
- **Опис:**  AuthenTec Swipe Sensor WDF USB Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`

**Imports:** `MmMapIoSpace`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
