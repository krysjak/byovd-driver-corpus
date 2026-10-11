# `dlusbaudio_3.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D0E621AD7FBAC75061B460C59026E5F2B840B01B4F46D13DCD651CEC87EEB967` | `84E7FF6DD3A2F3C598253E682F44C3484F1298E9` | `147CF0256EC0BC39412ADBC43163A404` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_3.sys`
- **Розмір:** 168264 bytes
- **Архітектура:** 0x14c
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
