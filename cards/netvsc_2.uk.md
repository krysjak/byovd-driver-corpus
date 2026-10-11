# `netvsc_2.sys`

[Назад до індексу](../README.uk.md) · [English version](netvsc_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6DE23BFD7C244E7B25040675BBF187E132EE030558B0AA91974B6EA4C2606940` | `689BBC02DD9D96D68ABFDAC05DAAFEFE4547886A` | `CC308EDAFDF5BED513BFF64C9E738126` |

## Метадані

- **Ім'я файлу:** `netvsc_2.sys` (Ідентичні копії: `netvsc_3.sys`)
- **Розмір:** 398744 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Virtual NDIS Miniport
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
