# Guía de contribución — RAMBLE Network

Gracias por querer contribuir a RAMBLE. Sigue estas pautas para que el proceso sea limpio y ordenado.

## Flujo de trabajo

```
dev (desarrollo activo)
 └── feature/nombre-feature
 └── fix/nombre-bug
      └── PR → dev → revisión → merge
                └── main (producción, solo releases)
```

## Antes de empezar

- Comprueba que no existe ya un issue o PR similar
- Para cambios grandes, abre un issue primero para discutirlo
- Usa el template de issue correspondiente

## Estilo de código

- **Java:** seguimos las convenciones estándar de Java
- Nombres de clases en `PascalCase`, métodos y variables en `camelCase`
- Constantes en `UPPER_SNAKE_CASE`
- Comentarios en inglés o español, pero consistente dentro del mismo archivo
- No subas código comentado o `System.out.println` de debug

## Commits

Formato: `tipo: descripción corta`

```
feat: añadir sistema de clases RPG
fix: corregir duplicación de items al morir
refactor: reorganizar estructura del BackendAPI
docs: actualizar README de Survival
chore: actualizar dependencias de Gradle
```

## Pull Requests

- Siempre hacia la rama `dev`, nunca directamente a `main`
- Rellena el template de PR completo
- Al menos 1 aprobación antes de hacer merge
- Asegúrate de que compila antes de abrir el PR

## Lo que NO hacer

- ❌ No subas IPs, contraseñas, tokens ni claves de API
- ❌ No hagas push directo a `main` ni `dev`
- ❌ No mezcles varios cambios no relacionados en un mismo PR
- ❌ No borres ramas protegidas

## Contacto

¿Dudas? Abre un issue o contacta en Discord.
