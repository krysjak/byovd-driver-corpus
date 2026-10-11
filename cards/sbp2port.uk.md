# `sbp2port.sys`

[Назад до індексу](../README.uk.md) · [English version](sbp2port.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7027E3FE0FB1F3BD5600927ECA4A6D0C763FF3695F14B59A757B668BB9D6E55B` | `D3EF60831401036B748853ACBFF1714BE4A17939` | `B611E8E1919F41054E750CDA92AA2485` |

## Метадані

- **Ім'я файлу:** `sbp2port.sys` (Ідентичні копії: `sbp2port_1.sys`)
- **Розмір:** 148912 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SBP-2 Protocol Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
