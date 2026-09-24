# Hanabi

影视商城首版骨架，支持会员订阅与单片购买。

## 功能

- 商品与影片目录
- Stripe、微信支付、支付宝的支付适配层
- 订单驱动的观看权益
- Cloudflare Stream 短时签名令牌的受控播放
- Supabase 数据库初始化脚本

## 本地运行

1. 复制 `.env.example` 为 `.env.local` 并填写服务端凭证。
2. 在 Supabase SQL Editor 执行 `supabase/schema.sql`。
3. 运行 `npm install`，再运行 `npm run dev`。

不要提交支付或视频服务密钥。
