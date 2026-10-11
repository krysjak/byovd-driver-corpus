# `droidcamaudio.sys`

[Назад до індексу](../README.uk.md) · [English version](droidcamaudio.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AD10D5D6F5CA02A114FC2890C9D5B8A595B8E244CCB89810304788A34B57C49A` | `49E3963ADD926E0962DAAD373AEAECAF36738E12` | `1E948F1455E3467D5B83A547FCEC093D` |

## Метадані

- **Ім'я файлу:** `droidcamaudio.sys`
- **Розмір:** 33808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Windows (R) Win 7 DDK provider
- **Продукт:** DroidCam
- **Опис:** Virtual Audio Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
