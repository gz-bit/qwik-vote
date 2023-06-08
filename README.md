## install
```
• npm i -g pnpm         // if not there yet
• pnpm create qwik
• pnpm create qwik
	○ qwik-vote
	○ Basic App
	○ Dependencies: Yes
	○ GitHub: Yes
• pnpm qwik add prisma
• pnpm qwik add tailwind
• pnpm qwik add auth
• pnpm add openai        // no qwik integration here!
```

<i>edit .gitignore -> add</i>: <b>*.env</b>

<i>edit vite.config.ts -> add</i>: 
```
optimizeDeps: { 
    include: ['@auth/core'] 
},
```

#### Just a reminder how to get it up

```
• get remote add origin https://github.com/gz-bit/qwik-vote.git
• git add --all
• git commit -m "prisma, tailwind, auth & openai"
• git branch -M main
• git push -u origin main
```

#### And down again
```
• git clone https://github.com/gz-bit/qwik-vote.git
• cd qwik-vote
• pnpm install
```
