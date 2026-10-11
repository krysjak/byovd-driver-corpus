# `IntcAudioBus_5.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BEF7ACA9CD2D5BEEF750BF1D8A43BB6B594E65917B8992DD62ACABC9F75A21C` | `29669DD3C0202FE331373E549201061EED5EAB1D` | `6663819A48612F5209F15D6C90DB0E02` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_5.sys`
- **Розмір:** 363080 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Smart Sound Technology BUS
- **Опис:** Intel(R) Smart Sound Technology BUS
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
