# `cmgfve.sys`

[Назад до індексу](../README.uk.md) · [English version](cmgfve.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5A8CCA31E631895A0A7AAD94F1A1819A18C2635F4861A7BEAF1C127B1F582087` | `B08F2F1B34D0924ACE53849550BCD25C1FA30E7F` | `CAD1D9716CD60F4710B7229EFF73AADE` |

## Метадані

- **Ім'я файлу:** `cmgfve.sys`
- **Розмір:** 295520 bytes
- **Архітектура:** 0x14c
- **Компанія:** Dell Inc.
- **Продукт:** CmgFVE.sys (32b,rls)
- **Опис:** Credant Full Volume Encryption Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 90

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
