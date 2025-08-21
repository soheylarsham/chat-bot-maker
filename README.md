
<!DOCTYPE html>
<html lang="fa" dir="rtl">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>چت بات هوشمند جمینی</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
      :root {
        --primary-color: #3b82f6;
        --font-family: 'Vazirmatn', sans-serif;
      }
      body {
        font-family: var(--font-family);
      }
      ::-webkit-scrollbar {
        width: 8px;
        height: 8px;
      }
      ::-webkit-scrollbar-track {
        background: transparent;
      }
      ::-webkit-scrollbar-thumb {
        background: #4a5568; /* gray-700 */
        border-radius: 10px;
      }
      ::-webkit-scrollbar-thumb:hover {
        background: #2d3748; /* gray-800 */
      }
      .gradient-bg {
        background-image: linear-gradient(to right, var(--primary-color), #8b5cf6);
      }
       .gradient-text {
        background-image: linear-gradient(to right, var(--primary-color), #8b5cf6);
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
      }
    </style>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <script type="importmap">
{
  "imports": {
    "react-dom/": "https://esm.sh/react-dom@^19.1.1/",
    "react": "https://esm.sh/react@^19.1.1",
    "react/": "https://esm.sh/react@^19.1.1/",
    "@google/genai": "https://esm.sh/@google/genai@^1.13.0"
  }
}
</script>
</head>
  <body class="bg-gray-900 text-gray-200">
    <div id="root"></div>
    <script type="module" src="./index.tsx"></script>
  </body>
</html>
