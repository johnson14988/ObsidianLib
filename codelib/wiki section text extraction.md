Display a wiki section in a custom webpage
```html
<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <title>Wiki Section Viewer</title>  
</head>  
<body>  
  <h2>Section Content:</h2>  
  <div id="wiki-content">Loading...</div>  
  
  <script>    fetch("https://en.wikipedia.org/w/api.php?action=parse&page=Python_(programming_language)&section=2&format=json&origin=*")  
      .then(res => res.json())  
      .then(data => {  
          document.getElementById("wiki-content").innerHTML = data.parse.text["*"];  
      })  
      .catch(err => {  
        console.error("Failed to load section", err);  
      });  
  </script>  
</body>  
</html>
```