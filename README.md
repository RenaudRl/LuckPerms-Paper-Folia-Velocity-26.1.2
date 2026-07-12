# LuckPerms — BTC Fork

Fork de **[LuckPerms](https://github.com/LuckPerms/LuckPerms)** (lucko), adapté au serveur **BornToCraft** — Paper / Folia **26.2**.

## Nos ajouts / correctifs BTC
- **Support Folia** natif : `FoliaSchedulerAdapter` (scheduler régionalisé).
- **Context calculators Folia** : `FoliaPlayerCalculator` + `FoliaTpsCalculator` — contextes de permissions basés sur la région / TPS, enregistrés automatiquement quand Folia est détecté.

## Build
```bash
./gradlew build                # jars dans les modules loader/ (bukkit, etc.)
```

---
Base upstream : `LuckPerms/LuckPerms` · cible Minecraft **26.2**
