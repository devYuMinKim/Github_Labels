# Github_Labels
> github label 간편하게 적용하기

### Start development
1. install `github-label-sync`
  ```bash
  npm install -g github-label-sync
  ```

2. prepare access-token
3. setting label.json <br>
   - download `label.json` file <br>
   - You can change `name`, `color`, and `description`.
4. Now you can apply to your Repository!
   Enter this command
```bash
github-label-sync --access-token [access-token] --labels labels.json [account]/[Repository name]
```
