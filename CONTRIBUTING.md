# Contributing Guide

> ¡Gracias por querer mejorar este proyecto!  
> Sigue estas reglas para que tu aporte se integre rápido y sin conflictos.

## Índice
1. Requisitos previos  
2. Flujo de trabajo (GitFlow)  
3. Convenciones de nombres  
4. Estándar de mensajes de commit (Conventional Commits)  
5. Pull Requests y revisiones  
6. Estilo de código  
7. Pruebas y cobertura  
8. CI/CD y variables secretas  
9. Seguridad y reporte de vulnerabilidades  
10. Código de conducta  

---

## 1. Requisitos previos
| Tool | Versión mínima | Comando de verificación |
|------|----------------|-------------------------|
| Git  | 2.40           | `git --version` |
| Node | 20 LTS         | `node -v` |
| npm  | 10 +           | `npm -v` |
| Azure CLI | 2.4+      | `az version` |

Instala dependencias con:

```bash
npm ci
