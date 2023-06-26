# label 한번에 적용하기
## access token 발급
* 깃허브 personal access token을 발급

## github-label-sync 설치
```bash
npm install -g github-label-sync
```

## label.json 설정
[labels.json](labels.json) 참고

## 적용
```bash
npx github-label-sync --access-token {엑세스토큰} --labels labels.json {레포지토리명}
```
