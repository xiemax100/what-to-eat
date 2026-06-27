# iOS 端设计 — SwiftUI

## 架构

- **MVVM** + SwiftUI
- 最低支持 iOS 16.0
- 使用 SwiftData 做本地收藏存储

## 核心页面

1. `HomeView` — 大转盘/大按钮 + 结果展示
2. `CategoryView` — 分类筛选
3. `FavoritesView` — 收藏列表

## 依赖

- 无第三方依赖，纯原生
- 图片用 SF Symbols + 本地资源
