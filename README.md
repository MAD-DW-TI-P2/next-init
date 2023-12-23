# next-init
Base de un proyecto next (Componentes, rutas, test y animaciones)

# Primeros pasos

## Iniciar proyecto

npx create-next-app@latest

✔ What is your project named? … next-init
✔ Would you like to use TypeScript? … No / Yes
✔ Would you like to use ESLint? … No / Yes
✔ Would you like to use Tailwind CSS? … No / Yes
✔ Would you like to use `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to customize the default import alias (@/*)? … No / Yes

cd a next-init
npx run dev 
http://localhost:3001

## Componentes y ruteo con variables en la URL

Importo Link donde quiera crear un link: import Link from 'next/link'
Creo link a página: <Link href="/invitations">Invitaciones</Link>
Creo componentes siguiendo la estrcutura de carperta con layout y page (Ver code)
Un componente con link a otros componentes que le pasa una url dinámicamente (Fijate que hay una carpeta que se llama [id]) 

Más info en: https://nextjs.org/docs/app/building-your-application/routing

