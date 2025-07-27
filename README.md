# 🔐 Stylish Login Page with Fixed Blurred Background

This project is a modern, clean login page built with **HTML** and **CSS**.  
It features a centered login form with a **blurred, fixed background image** that does not zoom or stretch when the screen is resized.  

---

## 📸 Features

- ✅ Fixed full-screen background image  
- ✅ Blur effect using `filter: blur()`  
- ✅ Fully centered login box  
- ✅ Stylish inputs and hover animations  
- ✅ Responsive structure for different screen sizes

---

## 🧠 How the Background Works

Instead of applying the background image directly to the `body`, we use a separate `div` with `id="bg"` and place it behind all content using `z-index: -1`. This ensures the image stays stable and does **not zoom or move** on different screen sizes.

### Example structure:

```html
<body>
  <div id="bg"></div>
  <div id="container">
    <!-- Login form here -->
  </div>
</body>
