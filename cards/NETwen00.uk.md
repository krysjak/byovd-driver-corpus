# `NETwen00.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwen00.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `54C4942BF73EAE73CE62D256529EB20F4E48E4C9468E8235AA0AE6263212EE5B` | `28774098B54803A92BD8FEEEE558FCE2A3AAC3A2` | `B59A695291BA2996324042C24AA880DE` |

## Метадані

- **Ім'я файлу:** `NETwen00.sys`
- **Розмір:** 2672608 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
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
