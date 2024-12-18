

# Smart Watch Shop  

**Live Preview**: [https://htmltask101.netlify.app/] 

## Project Overview  
This project is a **Smart Watch Product Page** built using **HTML, TailwindCSS**, and **JavaScript**. It features dynamic interactivity such as product image updates, size and color selection, quantity management, and a cart modal for checkout functionality.  

---

## Technologies Used  
- **HTML5**  
- **CSS**: TailwindCSS (via CDN)  
- **JavaScript**  
- **Font Awesome**: For icons  

---

## Features  
### 📌 Product Features  
- **Dynamic Product Image Update**: Changes based on selected color.  
- **Size and Color Selection**: Users can choose their preferred size and color for the smart watch.  
- **Quantity Management**: Increase or decrease product quantity with a simple UI.  
- **Interactive Cart Modal**: View cart summary with total quantity and price calculation.  

### 📌 User Interactions  
1. **Add to Cart**: Products with selected size and color can be added to the cart.  
2. **Checkout Button**: Displays the cart modal with dynamically updated items.  
3. **Responsive Design**: Ensures smooth experience across devices.  

---

## Folder Structure  
```
project-root/
│-- index.html   # Main HTML file  
│-- photos/      # Folder for product images  
    │-- lg-a 3.png  
    │-- cyan.png  
    │-- blue.png  
    │-- black.png  
```

---

## How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/smart-watch-shop.git  
   cd smart-watch-shop
   ```  
2. Open the `index.html` file in any modern browser.  

---

## Code Snippets  

### HTML Structure  
```html
<div class="space-y-6 m-3">
    <h1 class="text-3xl font-bold text-gray-900">Classy Modern Smart watch</h1>
    <p class="text-gray-600">Product description goes here.</p>
</div>
```

### Dynamic JavaScript Example  
```javascript
// Update product image when a color is selected
function updateProductImage() {
    productImage.src = selectedColor.image;
}
```

---

## Notes  
- **TailwindCSS** is used for styling (via CDN).  
- **Font Awesome** provides the star ratings and cart icons.  
- Images are located in the `/photos` directory and dynamically loaded using JavaScript.  

---

## Future Enhancements  
- Add a backend to store cart data.  
- Implement payment gateway integration.  

---

## Credits  
- **TailwindCSS**: [https://tailwindcss.com](https://tailwindcss.com)  
- **Font Awesome**: [https://fontawesome.com](https://fontawesome.com)  

