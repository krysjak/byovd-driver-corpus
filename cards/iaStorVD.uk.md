# `iaStorVD.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorVD.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5FCD7E16D48F729AA713678E19CD46B2CC61ED552C70773AF773D127DC55399A` | `D5CE5D3B89166D1C1DC0FD433364D072D36BC5BF` | `22E3AD3786EDF46C2A9CF4B1B950B843` |

## Метадані

- **Ім'я файлу:** `iaStorVD.sys`
- **Розмір:** 1545408 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
