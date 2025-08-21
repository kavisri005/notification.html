# notification.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Notification Feature</title>
<style>
  body {
    font-family: Arial, sans-serif;
    padding: 20px;
  }
  .toggle-container {
    margin-bottom: 20px;
  }
</style>
</head>
<body>

<h2>Profile Notification Settings</h2>
<div class="toggle-container">
  <label>
    <input type="checkbox" id="notifToggle">
    Enable Notifications
  </label>
</div>

<button onclick="simulateAnswer()">Simulate Answer Event</button>
<button onclick="simulateUpvote()">Simulate Upvote Event</button>

<script>
  const notifToggle = document.getElementById('notifToggle');

  
  notifToggle.checked = localStorage.getItem('notificationsEnabled') === 'true';

  
  notifToggle.addEventListener('change', () => {
    if (notifToggle.checked) {
      Notification.requestPermission().then(permission => {
        if (permission === 'granted') {
          localStorage.setItem('notificationsEnabled', 'true');
          alert("Notifications enabled!");
        } else {
          notifToggle.checked = false;
          localStorage.setItem('notificationsEnabled', 'false');
          alert("Permission denied.");
        }
      });
    } else {
      localStorage.setItem('notificationsEnabled', 'false');
      alert("Notifications disabled!");
    }
  });

  // Function to show notification
  function showNotification(title, body) {
    const enabled = localStorage.getItem('notificationsEnabled') === 'true';
    if (enabled && Notification.permission === 'granted') {
      new Notification(title, {
        body: body,
        icon: 'https://cdn-icons-png.flaticon.com/512/1827/1827349.png'
      });
    }
  }

  
  function simulateAnswer() {
    showNotification("New Answer", "Someone answered your question!");
  }
  function simulateUpvote() {
    showNotification("Upvote", "Someone upvoted your question!");
  }
</script>

</body>
</html>
