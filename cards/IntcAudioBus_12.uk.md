# `IntcAudioBus_12.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_12.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9F935B5D232771FC1DC4C4352CC3B3945B094C12D8C00C3854FEB25B581149B0` | `E967E633A949F5935E83F4FD906FFCE681E17611` | `754683F220721E84FDAF6C641BB21CB3` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_12.sys`
- **Розмір:** 292432 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Опис:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
