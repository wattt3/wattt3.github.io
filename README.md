# wattt3.github.io

[Astro](https://astro.build/) + [AstroPaper](https://github.com/satnaing/astro-paper) 테마로 만든 개인 블로그입니다.

## 글 쓰기

`src/content/posts/`에 마크다운 파일을 추가하고 `main`에 push하면 GitHub Actions가 https://wattt3.github.io 로 배포합니다.

```bash
pnpm install
pnpm dev      # http://localhost:4321
pnpm build    # 배포 전 빌드 확인
```

사이트 정보(제목, 소개, 소셜 링크 등)는 `astro-paper.config.ts`에서 바꿉니다.
