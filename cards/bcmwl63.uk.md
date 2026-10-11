# `bcmwl63.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BD9A9F370B47C58FE424E8D95E3D1505520DCE4BBE98B87F23C7701352A6460` | `33D21B0CB57B653CAB095882B6006272FBBA0BA5` | `D1D29204E4738A68C7E909988D8EC084` |

## Метадані

- **Ім'я файлу:** `bcmwl63.sys`
- **Розмір:** 10768136 bytes
- **Архітектура:** 0x14c
- **Компанія:** Broadcom Corp
- **Продукт:** Broadcom WiFi Driver wireless driver
- **Опис:** Broadcom WiFi Driver wireless driver
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
