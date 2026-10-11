# `IntcAudioBus_9.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `77EE4DD8AFA92E656563D243519C0E12EFCAF6B483AC8AA81FFDCFCE3C5D0B0C` | `6BBBB9A249227FC01ABBF99FA15EE827140C8C78` | `7963B5F1304EBB1117B7DEC10D81982D` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_9.sys`
- **Розмір:** 302872 bytes
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
