# `dlusbaudio.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `910E1BD4099BAF59304E5C71D8CB806F8DE380A1A57B9D6FF6900169B8453820` | `E259C434C6CC498807E4ADF2D24D2D6AD627D963` | `4585CB5CA4711D9D8BFB1CD6BFF25029` |

## Метадані

- **Ім'я файлу:** `dlusbaudio.sys`
- **Розмір:** 176344 bytes
- **Архітектура:** 0x14c
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
