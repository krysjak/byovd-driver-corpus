# `TEEDriver.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriver.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BC7DCC7722A4A1AC9F8D705F8819C9D227696A9538BBF6A52EB7C27969FD3A21` | `F9D9801659D05CE175AA30D18BC00DB160752BEC` | `113412F2962F700710BB22FCFE266B65` |

## Метадані

- **Ім'я файлу:** `TEEDriver.sys`
- **Розмір:** 85464 bytes
- **Архітектура:** 0x14c
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
