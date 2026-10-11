# `fsfreedomewintun.sys`

[Назад до індексу](../README.uk.md) · [English version](fsfreedomewintun.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8C0487353F66F3DBC786A0AA05C0CB440DAAE4168AA77FBB08A512CC3783FBED` | `B89E19945E8C3160EB82A0CB7ED4D48C882DED2D` | `3A10D5E81FEE5AF6C10E17C9FA1714E5` |

## Метадані

- **Ім'я файлу:** `fsfreedomewintun.sys` (Ідентичні копії: `fsfreedomewintun_1.sys`)
- **Розмір:** 31248 bytes
- **Архітектура:** 0x8664
- **Компанія:** F-Secure Corporation
- **Продукт:** F-Secure Freedome Wintun Driver
- **Опис:** F-Secure Freedome Wintun Driver
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
