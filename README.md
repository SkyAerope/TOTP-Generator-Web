# TOTP 生成器

一个静态网页，输入密钥，生成TOTP验证码。

|<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/95f83488-41f0-43b3-bda1-d2d746760d3a" /> | <img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/3492a087-4fc3-42e6-bb17-bc0bec9ad84b" /> |
| :---: | :---: |
| 空 | 输入密钥后 |

## 部署

### 部署到服务器
使用Caddy或Nginx等Web服务器serve静态网页，或者部署到GitHub Pages、Vercel、Netlify。

### 本地使用

直接打开 `index.html` 使用。

## 使用

1. **设置2FA时保存密钥**：在设置Google Authenticator等身份验证应用程序时，解析二维码获取密钥，或是显示明文密钥，将其保存到安全的地方。

2. **使用密钥获取验证码**：
   - 打开部署好的TOTP生成器网站。
   - 在输入框中输入2FA密钥。
   - 网站会生成TOTP验证码。
   - 点击卡片复制生成的TOTP验证码，用于验证。

## 注意事项

- 保管好密钥。
- 使用本工具时，请确保系统时间准确，否则可能生成错误。

## LICENSE

[MIT](LICENSE).
