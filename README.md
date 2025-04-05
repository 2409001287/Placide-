# Placide-
<!DOCTYPE html>
<html>
  <body>
    <p id="t">Hello World</p>

    <select onchange="t.style.color=this.value">
      <option>black</option>
      <option>red</option>
    </select>

    <select onchange="t.style.fontSize=this.value">
      <option value='20px'>Small</option>
      <option value='40px'>Big</option>
    </select>

    <script>t = document.getElementById("t")</script>
  </body>
</html>
