# `iaLPSS2_UART2_ICL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_ICL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D080F7BD9D0FACC1EC20626FE5F58EB90C6FA854BEBC96989AD043AC61C8304D` | `A7C1930AA72D24253E21493C73CD856743E98BBC` | `4585D72F9A720A9935F9861613DC322D` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_ICL.sys`
- **Розмір:** 312600 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO UART Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
