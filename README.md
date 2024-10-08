# intello-ui

intello-ui es una librería de componentes React inspirada en shadcn-ui, diseñada para proporcionar componentes de UI reutilizables y personalizables utilizando TypeScript y Tailwind CSS.

## Instalación

Para comenzar a usar intello-ui en tu proyecto, sigue estos pasos:

1. Instala los paquetes necesarios:

   ```bash
   npm install @intello-ui/react @intello-ui/cli
   ```

   o si prefieres usar yarn:

   ```bash
   yarn add @intello-ui/react @intello-ui/cli
   ```

2. Inicializa intello-ui en tu proyecto:

   ```bash
   npx @intello-ui/cli init
   ```

   Este comando creará los archivos de configuración necesarios para Tailwind CSS y añadirá los estilos globales requeridos por intello-ui.

## Uso

Después de la instalación e inicialización, puedes empezar a usar los componentes de intello-ui en tu proyecto React:

```jsx
import { Button } from "@intello-ui/react";

function MyComponent() {
  return (
    <Button variant="primary" size="md">
      Click me!
    </Button>
  );
}
```

## Componentes disponibles

Actualmente, intello-ui ofrece los siguientes componentes:

- Button

(Añade aquí más componentes a medida que los vayas creando)

## Personalización

intello-ui utiliza Tailwind CSS para estilizar sus componentes, lo que permite una fácil personalización. Puedes modificar el archivo `tailwind.config.js` generado durante la inicialización para ajustar los colores, tamaños y otros aspectos de diseño según tus necesidades.

## Desarrollo

Si deseas contribuir a intello-ui o personalizarlo más allá de lo que permite la configuración de Tailwind, puedes clonar el repositorio y seguir estos pasos:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/intello-ui.git
   cd intello-ui
   ```

2. Instala las dependencias:

   ```bash
   pnpm install
   ```

3. Ejecuta los scripts de desarrollo:
   ```bash
   pnpm run dev
   ```

## Estructura del proyecto

intello-ui está organizado como un monorepo utilizando pnpm workspaces. La estructura básica es la siguiente:

```
intello-ui/
├── packages/
│   ├── react/        # Componentes React
│   └── cli/          # CLI para la inicialización
├── package.json
└── pnpm-workspace.yaml
```

## Contribuir

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request en el repositorio de GitHub.

## Licencia

[MIT](https://choosealicense.com/licenses/mit/)
