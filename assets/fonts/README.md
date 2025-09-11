# থিমে বাংলা ফন্ট (Noto Serif Bengali) ব্যবহার গাইড

এই ডকুমেন্টেশনে দেখানো হলো কিভাবে **Noto Serif Bengali** ফন্ট আপনার থিমে যুক্ত করবেন।  

---

## 1. CDN ব্যবহার

ফন্ট CDN এর মাধ্যমে সহজে ব্যবহার করতে চাইলে আপনার `style.css` বা থিমের CSS ফাইলে নিচের কোডটি যোগ করুন:

```css
@import url('https://cdnmx.pages.dev/assets/fonts/noto_serif_bengali/font.css');

body, article, h1, h2, h3, h4, h5, h6, 
a, span, p, table, tr, td, input, 
div, button, label, select, 
.mubarok-topbar, .mubarok-main-menu, .mubarok-breadcrumb, 
.mubarok-copyrights-area, 
form span.required {
    font-family: 'Noto Serif Bengali', Arial, sans-serif !important;
}
