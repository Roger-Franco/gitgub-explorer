// configurações para instalar o TypeScript:
yarn add typescript -D 
yarn tsc --init //inicializa o TypeScript
// e altera o tsconfig para isso:
{
  "compilerOptions": {
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "jsx": "react-jsx",
    "noEmit": true,
    "strict": true,
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "allowSyntheticDefaultImports": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true
  },
  "include": ["src"]
}

// yarn add @babel/preset-typescript -D
//mudei o webconfig e o babel.config

// yarn add @types/react-dom -D

// yarn add @types/react -D   // se der erro na importacao do react

