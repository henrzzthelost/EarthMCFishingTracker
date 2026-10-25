# EarthMC Fishing Tracker (Fabric 1.21.11)

Projeto cliente para Minecraft Java 1.21.11/Fabric. Inclui estrutura de HUD, ecrã de controlo, histórico persistente e exportação CSV.

## Estado importante
Este é um projeto inicial, não um JAR pronto e testado. A captura automática ainda precisa de ser implementada/testada com o protocolo real de pesca do Terra Nostra. A API do jogo também pode exigir pequenos ajustes após a primeira compilação. A classificação incluída é uma referência inicial à tabela de tesouros da wiki e deve ser confirmada contra a configuração atual do servidor.

## Compilar
Requer Java 21 e Gradle 9.x. Na pasta do projeto:
`gradle build`

O JAR remapeado ficará em `build/libs/`.

## Instalar
Depois de compilar e testar, colocar o JAR em `.minecraft/mods/` junto com Fabric Loader e Fabric API compatíveis.

Os dados são guardados em `.minecraft/config/earthmc-fishing-tracker.json`.
