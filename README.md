<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  سایت ایمیل فیک
<pre><code class="language-bash">www.mohmal.com</code></pre>
  سایت ساخت پسوورد
<pre><code class="language-bash">passwordsaz.ir</code></pre>
  کد vcl
<pre><code class="language-bash">if (req.http.Upgrade) {
  return (upgrade);
}</code></pre>
اینباند مرزبان
<pre><code class="language-bash"> {
      "tag": "VLESS + WS",
      "listen": "0.0.0.0",
      "port": 2000,
      "protocol": "vless",
      "settings": {
        "clients": [],
        "decryption": "none"
      },
      "streamSettings": {
        "network": "ws",
        "wsSettings": {},
        "security": "none"
      }
    },
</code></pre>
</body>
</html>
