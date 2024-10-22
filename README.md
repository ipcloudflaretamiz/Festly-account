<div>
  <button class="btn" onclick="copyToClipboard()">کپی کردن</button>
</div>
<pre><code>کد vcl فستلی</code></pre>

<script>
  function copyToClipboard() {
    const el = document.createElement('textarea');
    el.value = 'کد vcl فستلی';
    document.body.appendChild(el);
    el.select();
    document.execCommand('copy');
    document.body.removeChild(el);
    alert('متن کپی شد!');
  }
</script>
