---
title: '我的第一篇测试文章'
description: '这是我在 Mac 上发布的第一篇测试文章，用来验证本地开发到线上部署的完整流程。'
pubDate: 2026-09-30
tags: ['test', 'astro']
draft: false
---

今天是2026年09月30日 ，这是一篇测试文章，用来验证：

- 本地 `pnpm dev` 能正常预览
- GitHub 能正常提交推送
- Cloudflare 能自动部署到线上

## 一个代码块测试

```ts
function hello(name: string): string {
  return `你好，${name}！`;
}

console.log(hello('Michael'));