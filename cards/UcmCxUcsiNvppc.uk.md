# `UcmCxUcsiNvppc.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxUcsiNvppc.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `23853223F434BC3BCCEC7FB1BC1F974E87E7032B41CB588BBD1B44C30952FECD` | `ECFA5F51C661AC60162F68744D1BBB7C78C6682C` | `5C100BA18C44C4F8D36211284B5F4C1D` |

## Метадані

- **Ім'я файлу:** `UcmCxUcsiNvppc.sys`
- **Розмір:** 709008 bytes
- **Архітектура:** 0x8664
- **Компанія:** NVIDIA Corporation
- **Продукт:** NVPPC
- **Опис:** NVIDIA PPC Function Driver.
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
