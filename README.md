### Deploy react app to github pages
- Install package
```bash
$ npm install --save gh-pages
```

- Update scripts in `package.json`
```json
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build",
```
- Run deploy command
```bash
$ npm run deploy
```

### Apps
[Bitnami docker info](https://ghp.x2stech.vn/bitnami-docker-info)
