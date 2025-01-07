# Vintera_rocnikovy_projekt_displej

Tento projekt je implementací FreeTouchDeck, jednoduchého a přizpůsobitelného ovládacího panelu na bázi dotykového displeje. FreeTouchDeck umožňuje ovládání počítače, aplikací nebo chytrých zařízení prostřednictvím vlastního uživatelského rozhraní běžícím na ESP32. 

## VIDEO rozpracovaného projektu: https://youtu.be/yFMjkvpptjk

## Obsah
1. [Úvod](#Úvod)
2. [Funkce](#Funkce)
3. [Použité technologie](#Použité-technologie)
4. [Hardware](#Hardware)
5. [Konfigurace](#Konfigurace)
6. [Citace](#Citace)

## Úvod
FreeTouchDeck je minimalistická a uživatelsky přívětivá alternativa k napr Stream decku. Uživatelské rozhraní je přizpůsobtelné, mohu nahrát vlastní obrázky ikonek a vlastní funkce tlačítek. 

## Funkce
- Přizpůsobitelné tlačítka s možností nahrávání vlastních ikon.
- Více stránek pro ovládání různých aplikací nebo zařízení.
- Bezdrátová komunikace přes Wi-Fi (Konfigurace) a Blueooth (následné používání).
- Snadná konfigurace pomocí webového rozhraní.

## Použité technologie
- Programovací jazyk: C++
- Platforma: Arduino Framework
- Hardwarový modul: ESP32
- Ovládání: Dotykový displej a webové rozhraní

## Hardware
Pro realizaci tohoto projektu budete potřebovat následující komponenty:
- **ESP32**
- **3.5" dotykový displej** ILI9488 TFT s dotykovou funkcí
- 3D tištěný rámeček
- vodiče

## Konfigurace
- Po prvním spuštění se ESP32 přepne do režimu Access Point. Připojte se k síti s názvem `FreeTouchDeck` a otevřete adresu `192.168.4.1` v prohlížeči.
- Nastavte připojení k domácí Wi-Fi síti a přizpůsobte tlačítka dle vašich potřeb.

## Citace
- WATTS, DustinWatts. A Bluetooth ESP32 TFT + Touch Macro Keypad). Online. Licence: MIT License. Dostupné z: https://www.instructables.com/A-Bluetooth-ESP32-TFT-Touch-Macro-Keypad/. [cit. 2025-01-06].
