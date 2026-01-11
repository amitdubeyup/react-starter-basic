# create-react-app

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

Create React apps with no build configuration.

## 🚀 Tech Stack

- Node.js

## ✨ Features

- Modern and scalable architecture

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/amitdubeyup/create-react-app.git
cd create-react-app

# Install dependencies
npm install
```

## ⚙️ Configuration

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Update the `.env` file with your configuration values.

## 🚀 Usage

```bash
# Production mode
npm start

# Build for production
npm run build

# Run tests
npm test
```

## 📜 Available Scripts

- `npm run build` - cd packages/react-scripts && node bin/react-scripts.js build
- `npm run changelog` - lerna-changelog
- `npm run create-react-app` - node tasks/cra.js
- `npm run e2e` - tasks/e2e-simple.sh
- `npm run e2e:docker` - tasks/local-test.sh
- `npm run postinstall` - cd packages/react-error-overlay/ && yarn build:prod
- `npm run publish` - tasks/publish.sh
- `npm run start` - cd packages/react-scripts && node bin/react-scripts.js start
- `npm run screencast` - node ./tasks/screencast.js
- `npm run screencast:error` - svg-term --cast jyu19xGl88FQ3poMY8Hbmfw8y --out screencast-error.svg --window --at 12000 --no-cursor
- `npm run test` - cd packages/react-scripts && node bin/react-scripts.js test
- `npm run format` - prettier --trailing-comma es5 --single-quote --write 'packages/*/*.js' 'packages/*/!(node_modules)/**/*.js'
- `npm run compile:lockfile` - node tasks/compile-lockfile.js

## 📁 Project Structure

```
create-react-app/
├── package.json
├── .env.example
├── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Amit Dubey**

- GitHub: [@amitdubeyup](https://github.com/amitdubeyup)
