## Connect Server

```
Linha 29 ./ui/components/AddServerView/index.tsx
const defaultServerUrl = new URL('https://open.rocket.chat/');
passa para 
const defaultServerUrl = new URL('https://chat.void.pt/');
```

## Menu Bar Links

```
Ficheiro ./ui/main/menuBar.ts
Documentation
shell.openExternal('https://docs.rocket.chat/');
Report Issue
shell.openExternal('https://github.com/RocketChat/Rocket.Chat/issues/new');
Learn More
shell.openExternal('https://rocket.chat');
```