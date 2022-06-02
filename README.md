# study-react-todo-app
Reactがノリで書けなくなってきたので学ぶ

# Install

```bash
$ docker compose up
$ docker compose exec frontend /bin/bash
root@79093d32318c:/app# yarn create vite
yarn create v1.22.17
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...

success Installed "create-vite@2.9.4" with binaries:
      - create-vite
      - cva
✔ Project name: … study-react
✔ Select a framework: › react
✔ Select a variant: › react

Scaffolding project in /app/study-react...

Done. Now run:

  cd study-react
  yarn
  yarn dev

Done in 23.85s.


root@79093d32318c:/app# cd frontend/
root@79093d32318c:/app# npm install
root@79093d32318c:/app# npm run dev -- --h 0 --port 80
```
