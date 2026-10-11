# `TEEDriverGscW8x64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8F31DE9401E98A32E834457444342C49F0DDD5EEE9436D3655E9671E4F89071C` | `310C7D6927A086673DA19C1782A805EBBCD0E37E` | `ECC0CAEDEF7DCF123AEC2FBB9FA7AA54` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_3.sys`
- **Розмір:** 276416 bytes
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
