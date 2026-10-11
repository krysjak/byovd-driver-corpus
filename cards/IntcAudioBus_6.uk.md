# `IntcAudioBus_6.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `17CAB5D27EDCBEBDA9539A17710BEA7A8D649A596D80046E390D30AFA5FE4D3B` | `28C8A99F4DED2AA2B9429216C3219FBD2FE40EAC` | `FBED23189F8FB107DBCC25C0FB224AA7` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_6.sys`
- **Розмір:** 292936 bytes
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
