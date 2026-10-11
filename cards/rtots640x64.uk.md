# `rtots640x64.sys`

[Назад до індексу](../README.uk.md) · [English version](rtots640x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F62D9F3E8DA87C45605FE8B8D2F365BC005F4784B49DCF40C5E87E5593AEDB5B` | `5265CF4BE90F577755D293EE8356108D82F634A6` | `61DC9559AFD1E1C9195C7EC0D27A8259` |

## Метадані

- **Ім'я файлу:** `rtots640x64.sys`
- **Розмір:** 1460736 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek                                        
- **Продукт:** Realtek 8125/8126/8136/8168/8169 PCI/PCIe Adapters                                        
- **Опис:** Realtek 8125/8126/8136/8168/8169 NDIS 6.40 64-bit Driver                                        
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
