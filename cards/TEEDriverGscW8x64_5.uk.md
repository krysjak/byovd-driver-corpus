# `TEEDriverGscW8x64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5BD982E85DEEC1BD8D7E1D1869B3C21AA81E321DED4E7F0DD79401917DC1493D` | `AC5A5F69769C1A68F76B0168939916C17D2C3249` | `B9A2C5E17F3F6C9C07651AD2B88A0622` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_5.sys`
- **Розмір:** 279736 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
