# Node Boilerplate 🌱
Basic initial settings to start a Node project with TypeScript.

## Installation
1. Clone the repository

```javascript
git clone https://github.com/ecthon/node-boilerplate.git
cd node-boilerplate
```

2. Install the dependencies:
```javascript
npm install
```

## Running the Project
```javascript
npm run dev
```
This will start the server using tsx to watch the src/server.ts file for changes and restart automatically.

## Project Structure
```
node-boilerplate/</br>
├── src/</br>
│   └── server.ts
├── exemple.env
├── package.json
├── tsconfig.json
└── README.md
```

## Typescript Settings
Centralized Recommendations for TSConfig bases.</br>
https://github.com/tsconfig/bases?tab=readme-ov-file

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "_version": "20.1.0",

  "compilerOptions": {
    "lib": ["es2023"],
    "module": "node16",
    "target": "es2022",

    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "moduleResolution": "node16"
  }
}
```

## License
This project is licensed under the ISC License. See the LICENSE file for more details.

## Author
Created by [@ecthon](https://www.linkedin.com/in/ecthon/). 👾