# zova
Social media creator
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZOVA - Connect. Create. Earn.</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f6f8;
      color: #111;
    }

    header {
      background: #ffffff;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 18px;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 8px rgba(0,0,0,.08);
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    .search {
      background: #f0f2f5;
      border: none;
      padding: 11px 15px;
      border-radius: 25px;
      width: 38%;
      outline: none;
    }

    .login {
      background: #111;
      color: white;
      border: none;
      padding: 10px 18px;
      border-radius: 20px;
    }

    .container {
      max-width: 900px;
      margin: 20px auto;
      padding: 0 12px;
    }

    .welcome {
      background: white;
      padding: 22px;
      border-radius: 15px;
      margin-bottom: 18px;
    }

    .welcome h1 {
      font-size: 27px;
      margin-bottom: 8px;
    }

    .welcome p {
      color: #666;
    }

    .create {
      background: white;
      padding: 15px;
      border-radius: 15px;
      margin-bottom: 18px;
    }

    .create textarea {
      width: 100%;
      border: none;
      background: #f1f3f5;
      border-radius: 12px;
      padding: 14px;
      resize: none;
      outline: none;
      font-size: 15px;
    }

    .post-btn {
      margin-top: 10px;
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 10px;
      background: #111;
      color: white;
      font-size: 16px;
      font-weight: bold;
    }

    .post {
      background: white;
      border-radius: 15px;
      margin-bottom: 18px;
      overflow: hidden;
    }

    .post-header {
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 15px;
    }

    .avatar {
      width: 42px;
      height: 42px;
      border-radius: 50%;
      background: #111;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    }

    .post-text {
      padding: 0 15px 15
