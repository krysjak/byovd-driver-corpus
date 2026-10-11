# `amdsbs.sys`

[Назад до індексу](../README.uk.md) · [English version](amdsbs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AFA0A9EACCC36CFC88AC41DCD0149AC6F9763D12C898397E831D80F202EF4402` | `3D2ED79A4B29BF3D29C6BA549F8B1BD56400764C` | `C516B52D95F7581C2F6D15D83771C472` |

## Метадані

- **Ім'я файлу:** `amdsbs.sys` (Ідентичні копії: `amdsbs_1.sys`)
- **Розмір:** 260512 bytes
- **Архітектура:** 0x8664
- **Компанія:** AMD Technologies Inc.
- **Продукт:** AMD Technology AHCI Compatible Controller
- **Опис:** AMD Technology AHCI Compatible Controller Driver for Windows - AMD64 platform
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
