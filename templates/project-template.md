# Project Template

This template provides a standardized structure for new projects at Displace Agency.

## Project Structure

```
project-name/
├── README.md
├── package.json
├── .gitignore
├── .env.example
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── utils/
├── public/
├── docs/
│   ├── setup.md
│   ├── deployment.md
│   └── api.md
└── tests/
    ├── unit/
    └── integration/
```

## Required Files

### README.md Template
```markdown
# [Project Name]

Brief description of the project.

## Setup
1. Clone the repository
2. Install dependencies: `npm install`
3. Copy .env.example to .env and configure
4. Start development server: `npm run dev`

## Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run test` - Run tests
- `npm run lint` - Lint code

## Documentation
- [Setup Guide](docs/setup.md)
- [Deployment Guide](docs/deployment.md)
- [API Documentation](docs/api.md)
```

### package.json Basics
```json
{
  "name": "project-name",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "test": "jest",
    "lint": "eslint ."
  },
  "dependencies": {},
  "devDependencies": {}
}
```

### .gitignore Template
```
node_modules/
.next/
.env
.env.local
.env.production
.vercel
dist/
build/
*.log
.DS_Store
coverage/
```

## Best Practices

1. **Naming**: Use kebab-case for project names
2. **Documentation**: Include comprehensive setup instructions
3. **Environment**: Always include .env.example with required variables
4. **Testing**: Set up testing framework from the start
5. **Linting**: Configure ESLint and Prettier for code consistency

## Checklist

- [ ] Repository created with proper naming
- [ ] README.md with setup instructions
- [ ] .env.example with all required variables
- [ ] package.json with all necessary scripts
- [ ] .gitignore configured
- [ ] Basic folder structure created
- [ ] Testing framework configured
- [ ] Linting rules set up
- [ ] Initial documentation created

---

*This template should be customized based on the specific technology stack and requirements of each project.*