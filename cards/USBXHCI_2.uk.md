# `USBXHCI_2.SYS`

[Назад до індексу](../README.uk.md) · [English version](USBXHCI_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A2E321ADE62313F915CC4D5E82D44350B978A57972C2DA827A94AC0D75B91C18` | `99516E7B751DD21288991A9B8DD000B15C5352C6` | `F4587E8D460660C7C9BC97FFE3582867` |

## Метадані

- **Ім'я файлу:** `USBXHCI_2.SYS` (Ідентичні копії: `USBXHCI_3.SYS`)
- **Розмір:** 726400 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB XHCI Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
