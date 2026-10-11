# `IntcOED_12.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcOED_12.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FA62A1BA471E525DE1825E1E08F7E8B0585BEFE126EFD432AAE8563F5E28F27` | `78687EC2CCE1568ED6318E60C76FE6566E5DB436` | `3119733BB6BAE4837FBFF276DF36CC78` |

## Метадані

- **Ім'я файлу:** `IntcOED_12.sys`
- **Розмір:** 1165904 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) OED
- **Опис:** Intel® Smart Sound Technology (Intel® SST) OED
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
