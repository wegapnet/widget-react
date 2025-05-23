# 💬 Wegap Widget for React / ویجت ویگپ برای React

This repository contains the official React version of the Wegap widget.  
این مخزن شامل نسخه رسمی ویجت ویگپ برای برنامه‌های React است.

---

## 📦 Installation / نصب

```bash
npm install @wegapnet/widget-react
# or
yarn add @wegapnet/widget-react
```

---

## 🚀 Quick Usage / استفاده سریع

```jsx
import { WegapWidget } from '@wegapnet/widget-react';

function App() {
  return (
    <div>
      <h1>My App / اپلیکیشن من</h1>
      <WegapWidget
        authKey="YOUR_AUTH_KEY"
        theme="light"
        position="bottom-right"
        language="fa"
      />
    </div>
  );
}
```

---

## ⚙️ Config Options / تنظیمات

| Prop Name | Type   | Description EN                                      | توضیح فارسی |
|-----------|--------|------------------------------------------------------|--------------|
| authKey   | string | Your unique authentication key                      | کلید احراز هویت شما |
| theme     | string | Theme mode: `light` or `dark`                       | تم: روشن یا تیره |
| position  | string | Widget position: `bottom-right`, `bottom-left` etc | موقعیت ویجت در صفحه |
| language  | string | Default language: `fa`, `en`, `ar`, ...            | زبان پیش‌فرض ویجت |

---

## 📄 Documentation / مستندات کامل

- [See full guide in Wegap Wiki](https://wegap.net/wiki/react/نصب-و-راه-اندازی/راهنمای-ویجت-ویگپ/دانشیار-ویگپ-id-8911)
- مشاهده راهنما در ویکی ویگپ ↑
