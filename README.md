<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Redirecting…</title>
    <script>
      // Set a simple cookie
      document.cookie = "loggedIn=true; path=/; max-age=3600";

      // Redirect after setting cookie
      window.location.href = "https://example.com"; // Replace with your real destination
    </script>
  </head>
  <body>
    <p>Redirecting…</p>
  </body>
</html>
