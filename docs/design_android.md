# Android 端设计 — Jetpack Compose

## 架构

- **MVVM** + Jetpack Compose
- 最低支持 Android 8.0 (API 26)
- 使用 Room 做本地收藏存储

## 核心页面

1. `HomeScreen` — 大按钮 + 动画结果展示
2. `CategoryScreen` — 分类筛选（LazyColumn）
3. `FavoritesScreen` — 收藏列表

## 依赖

- Compose BOM
- Lifecycle ViewModel
- Room
- Coil（图片加载）
