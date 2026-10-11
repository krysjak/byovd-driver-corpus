# `expressvpn-tun.sys`

[Назад до індексу](../README.uk.md) · [English version](expressvpn-tun.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `784D93A908D9E543272072D49DC4224D09DB2052983E66BDE32E4AF6921DAD9F` | `DB28B6C763110095FDA71925053DAD5317141CF3` | `4E72AE539702BF5A979B8B382D7F8027` |

## Метадані

- **Ім'я файлу:** `expressvpn-tun.sys` (Ідентичні копії: `expressvpn-tun_1.sys`)
- **Розмір:** 41976 bytes
- **Архітектура:** 0x8664
- **Компанія:** ExpressVPN
- **Продукт:** ExpressVPN Wintun Driver
- **Опис:** ExpressVPN Wintun Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
