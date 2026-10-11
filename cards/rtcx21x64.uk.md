# `rtcx21x64.sys`

[Назад до індексу](../README.uk.md) · [English version](rtcx21x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C653B13438497D5ED8F1A0F7F24C14C0EC9FFC7E324135C29EB591BF1AAEA94` | `BD796381DED9399E565C6415EC75E50F07E3DEF0` | `F1FF821EC7AEEB7CD2FBCC58FE745E80` |

## Метадані

- **Ім'я файлу:** `rtcx21x64.sys`
- **Розмір:** 539648 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek                                        
- **Продукт:** Realtek PCIe Adapter                                        
- **Опис:** Realtek NetAdapter Driver                                        
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
