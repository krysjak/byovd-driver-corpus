# `dlusbaudio_x64.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EB6674CAD3282E2A520AB55A28B0A38A59B3D3DCC16088D58FA4A807F404E986` | `1259B6E10E1C7F539ECD655E872342C11303AD52` | `36AB6683C7490748E4E6C1ABC19EF802` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_x64.sys`
- **Розмір:** 237784 bytes
- **Архітектура:** 0x8664
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
