# 用于监控sdk包的测试

## 项目结构

```
react-test-sdk/
├── public/                  # 静态资源目录
│   └── vite.svg             # Vite logo
├── src/                     # 源代码目录
│   ├── pages/               # 页面组件
│   │   ├── demoPage.tsx     # 示例页面
│   │   ├── clickPage/       # 点击事件测试页面
│   │   │   └── clickPages.tsx
│   │   └── whiteScreenPage/ # 白屏测试页面
│   │       └── whiteScreen.tsx
│   ├── router/              # 路由配置
│   │   └── index.tsx
│   ├── api/                 # API接口
│   │   └── index.ts
│   ├── assets/              # 静态资源
│   │   └── react.svg        # React logo
│   ├── interface/           # 类型定义
│   │   └── index.ts
│   ├── index.css            # 全局样式
│   ├── main.tsx             # 应用入口
│   └── vite-env.d.ts        # Vite环境类型
├── test/                    # 测试目录
│   └── test.js              # 测试用例
├── .gitignore               # Git忽略配置
├── package.json             # 项目依赖配置
└── vite.config.ts           # Vite配置
```

