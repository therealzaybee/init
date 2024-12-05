# vite, vue, shadcn-vue Library Starter

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

"include": ["src/**/*.ts", "src/**/*.tsx", "src/**/*.vue", "example/**/*"]
here "example/**/*" is included in the `tsconfig` because if we don't we won't get autocomplete for the props in the example dir when we test it out. 

"baseUrl", "include" are important otherwise the `class-variance-authority/types` generates wrong type which is `class-variance-authority/dist/types`, here `dist` comes as an extra thing for some reason.