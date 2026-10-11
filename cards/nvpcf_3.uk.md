# `nvpcf_3.sys`

[Назад до індексу](../README.uk.md) · [English version](nvpcf_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `57A86410C5C1B2E96954D99AD86BC41BA7C29D690394F54FE2488BB7ECF22E73` | `06AC62174A791F277A7B34CD0160F3B84E3F398A` | `24FA8DB0202610E572227D707EF90B03` |

## Метадані

- **Ім'я файлу:** `nvpcf_3.sys`
- **Розмір:** 208000 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPCF
- **Опис:** NVIDIA Platform Controllers and Framework
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 115

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
