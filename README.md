# Placide-
<!DOCTYPE html>
<html>
  <body>
    <p id="hello">Hello World</p>

    <select onchange="hello.style.color=this.value">
      <option>black</option>
      <option>red</option>
      <option>blue</option>
    </select>

    <select onchange="hello.style.fontSize=this.value">
      <option value="20px">Small</option>
      <option value="30px">Medium</option>
      <option value="40px">Large</option>
    </select>

    <script>
      const hello = document.getElementById("hello");
    </script>
  </body>
</html>
