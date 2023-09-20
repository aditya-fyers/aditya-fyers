<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Typing Animation</title>
<style>
  .typing-animation {
    display: inline-block;
    overflow: hidden;
    border-right: .15em solid orange;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: .15em;
    animation: typing 2s steps(30) infinite;
  }
  
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }
</style>
</head>
<body>
  <div class="typing-animation">Hello there</div>
</body>
</html>
