# `IntcAudioBus_3.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E3D3DCF65B23E9CD4B5596EBB085C2CD9FB6B3A454DF660D322CA0802A1F8476` | `0BCC6F37629F651D0CAB317BB7612294F84695A6` | `CE010229FFDDC33BEF5E7EF2E3AEADF8` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_3.sys`
- **Розмір:** 279928 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Опис:** Intel® Smart Sound Technology (Intel® SST) Bus
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
