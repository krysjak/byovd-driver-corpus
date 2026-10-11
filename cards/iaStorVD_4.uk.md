# `iaStorVD_4.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorVD_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3DF428F5DCA091BD58CDDB05FD4EBCE45E68D9B013242F7A0C4B8B94BDE1E2FD` | `213289BDB02C50C63A46DBB8A21487C04BECF6A1` | `453ECC094388E89AD431A2A1E4D92D1D` |

## Метадані

- **Ім'я файлу:** `iaStorVD_4.sys`
- **Розмір:** 1587376 bytes
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
