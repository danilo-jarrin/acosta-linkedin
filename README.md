# acosta-linkedin

Skill de Claude Code que actúa como **director de LinkedIn** con el **Modelo
Lara Acosta**: perfil como landing page, posts escritos con foto (PAS / SLAY),
rutina diaria de comentarios y conexiones, y embudo a lead magnet y email.

Cualquier persona puede empezar **desde cero**: la primera vez, el skill la
entrevista (ventajas injustas, SMPV, estado del perfil, tiempo disponible) y
crea su perfil de LinkedIn.

Skill hermano para Instagram / vídeo corto:
[`caleb-content`](https://github.com/danilo-jarrin/caleb-content). Si usas los
dos, comparten tu identidad y tu depósito de dolores.

## Instalar

```bash
git clone https://github.com/danilo-jarrin/acosta-linkedin.git ~/.claude/skills/acosta-linkedin
```

Abre Claude Code y di algo como *"quiero empezar en LinkedIn desde cero"* o
*"qué publico hoy en LinkedIn"*.

## Tus datos no van en este repo

```
~/.claude/contenido-datos/<tu-nombre>/linkedin/perfil.md
~/.claude/contenido-datos/<tu-nombre>/linkedin/progreso.md
```

`git pull` actualiza el método sin tocar tu historia. Al terminar la
entrevista, el skill te ofrece guardar tus datos en un repo **privado** propio.

## Actualizar el método

```bash
git -C ~/.claude/skills/acosta-linkedin pull
```

## Estructura

```
SKILL.md                                El director: alta, etapas y reglas
references/
├── metodo-acosta.md                    Método destilado
├── fuente-modelo-acosta-analisis.txt   Fuente en crudo, con citas
└── plantilla-perfil.md                 Plantilla del perfil que se crea en el alta
```

## Aviso

Resumen no oficial elaborado a partir de fuentes públicas sobre el método de
Lara Acosta (entrevistas, artículos y vídeos). No está afiliado a ella.
