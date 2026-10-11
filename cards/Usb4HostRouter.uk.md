# `Usb4HostRouter.sys`

[Назад до індексу](../README.uk.md) · [English version](Usb4HostRouter.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `89B96F603775EA22AFB955A0DA6A848B921931666C34775E6ABB0842566CC371` | `7538B5D3A23FDAF1F3446886CB9B6CB256FF55DC` | `6E31FDC711D2E58E6600FDFFF61B8A01` |

## Метадані

- **Ім'я файлу:** `Usb4HostRouter.sys`
- **Розмір:** 714224 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB4(TM) Host Router Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
