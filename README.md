# NEEC Mini Drone

Este projeto tem como objetivo replicar o drone Flix e, futuramente, desenvolver novas funcionalidades.

## Organização dos Ficheiros

| Pasta / Ficheiro | Conteúdo |
|---|---|
| `docs/assets/` | Modelos 3D para impressão (`.stl`) e modelos editáveis (`.step`). |
| `docs/assembly.md` | Instruções e imagens de montagem do drone. |
| `docs/usage.md` | Instruções para compilar, carregar o firmware, configurar e testar o drone. |
| `flix/` | Código do firmware do ESP32 (`flix.ino` e restantes ficheiros). |
| `gazebo/` | Ficheiros e instruções para simular o drone no Gazebo. |
| `tools/pyflix/` | Biblioteca Python para comunicar com o drone, obter telemetria e enviar comandos de controlo. |
| `Makefile` | Comandos para compilar o firmware e executar a simulação. |

## Esquemas Elétricos

Os esquemas de ligação, incluindo as ligações dos motores, MOSFETs e IMU ao ESP32, encontram-se no README original do Flix.

## Projeto Original

Este projeto é baseado no **Flix**, desenvolvido por Oleg Kalachev.

GitHub: https://github.com/okalachev/flix

Para informações mais detalhadas, consultem a documentação original.
