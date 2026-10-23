Usage: PASSWORD='...' node encrypt.mjs <input.html> <output index.html>
Keep template.html next to encrypt.mjs. Output decrypts in the browser (AES-256-GCM, PBKDF2-SHA256 600k). Never commit the password.
Tested 2026-10-23 in headless Chromium: wrong password rejected, right one opens the tool.
