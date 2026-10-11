# `cht4sx64.sys`

[Назад до індексу](../README.uk.md) · [English version](cht4sx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FFAA9ABF91808E2569206A5A5D5D3542B02860965D8F1EA5790307648CD1E4D3` | `B35F32FD33B8B3D7F3ED58B7B856190A867C3DE6` | `ECB99F55AA110AC10B7D4795CB66464F` |

## Метадані

- **Ім'я файлу:** `cht4sx64.sys` (Ідентичні копії: `cht4sx64_1.sys`)
- **Розмір:** 320944 bytes
- **Архітектура:** 0x8664
- **Компанія:** Chelsio Communications
- **Продукт:** Chelsio Communications iSCSI Controller
- **Опис:** Chelsio iSCSI VMiniport Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
