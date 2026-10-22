# FastAPI Base

A Kelor Project Base for a full-stack app: the official [Full Stack FastAPI Template](https://github.com/fastapi/full-stack-fastapi-template), with a FastAPI backend in `backend/` and a React frontend in `frontend/`.

## Placeholders

Blocks can add code at these standard placeholders:

| File | Placeholder | For |
| --- | --- | --- |
| `backend/app/main.py` | `# kelor:imports` | imports for the backend's main module |
| `backend/app/main.py` | `# kelor:routes` | routers, included after the API router |
| `frontend/src/main.tsx` | `// kelor:imports` | imports for the frontend's entry point |
| `frontend/src/main.tsx` | `{/* kelor:providers */}` | app-wide components, next to the `<Toaster>` |

Blocks add Python packages to `backend/pyproject.toml` and npm packages to `frontend/package.json` with their `packages` key.

## Changes from the template

- The placeholders above.
- The template's symbolic links under `.agents/skills/` and `.claude/skills/` are removed, because Kelor rejects symbolic links.
- The template's own repository-maintenance workflows (issue and release automation) are removed; its test and deployment workflows are kept.
- This root `README.md` replaces the template's, because Kelor leaves it out of projects. The template's documentation for projects is in `development.md`, `deployment.md`, `backend/README.md` and `frontend/README.md`.

## Use it

Generate a project from this Base in Kelor's Builder, then follow `development.md`.

## Licence

The template is by Sebastián Ramírez and is under the MIT licence; see [LICENSE](LICENSE).
