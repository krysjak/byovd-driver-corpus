# `iaStorA.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorA.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `44B44A433A0B13A010C97CF0D30CF6CBF7332C6E00F33887BDF60ACB3F1887B2` | `D2F18F7DED48CB3C24956D7FF54080F4F22CB010` | `146A719B71FC6CB7AFF3585CBDD53259` |

## Метадані

- **Ім'я файлу:** `iaStorA.sys`
- **Розмір:** 506728 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel Rapid Storage Technology driver 
- **Опис:** Intel Rapid Storage Technology driver - x86
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
