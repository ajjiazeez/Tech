Tech Thozhan - How to Access Admin
==================================

CORRECT URLs (choose one):

1. Open directly (file:// or http://):
   - admin.html
   Example: file:///C:/Users/Azeez/OneDrive/Desktop/websiteclone-main3/websiteclone-main/admin.html

2. When using a local web server (e.g. "npx serve" or "python -m http.server"):
   - http://localhost:3000/admin    (serves admin/index.html)
   - http://localhost:3000/admin.html

WRONG URL:
   - products.html/admin  (products.html is a FILE, not a folder - this path does not exist)

PRODUCTS SYNC:
   Products added in the admin are saved to browser localStorage and appear automatically on products.html.
   Open products.html in the same browser to see the products. They sync in real-time.

To run a local server (for /admin to work):
   - In the websiteclone-main folder, run: npx serve
   - Or: python -m http.server 8000
   - Then open: http://localhost:8000/admin
