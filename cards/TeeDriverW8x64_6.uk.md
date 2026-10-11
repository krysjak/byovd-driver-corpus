# `TeeDriverW8x64_6.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8x64_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `903B37C0954BF84EFD9FA11195FADF9C50EED83DC2F521C8659052500061F011` | `9D0FA9188D007C50FE9C155BC88C480EE9813A62` | `12AE4DD10B08A72FD814D502377EC709` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8x64_6.sys`
- **Розмір:** 228808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
