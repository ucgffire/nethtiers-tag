# Noland Tier Tagger

Minecraft 1.21 **Fabric** client modu. [Noland Tierlist](https://nethtiers.com) verilerini oyuncu isimlerinin yanında gösterir.

## Özellikler

- API: `https://nethtiers.com/api/players/{mcName}`
- Nametag, tab listesi ve chat'te tier gösterimi
- Format: `[HT3] Steve` veya `[HT3 - Sword] Steve`
- 5 dakika cache
- Client-side only
- Kit seçimi ve 3 ikon stili
- Enable/disable tiers
- Oyuncu arama ekranı (skin + tierler)

## Kurulum

1. Fabric Loader 1.21.x
2. Fabric API
3. Mod JAR → `.minecraft/mods`

## Derleme

```bash
gradlew build
```

Java 21+ gerekir.

## Komutlar

- `/nolandtiers settings` — Ayar ekranı
- `/nolandtiers search <oyuncu>` — Oyuncu ara

## Config

`.minecraft/config/noland-tier-tagger.json`
