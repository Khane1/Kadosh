  <script>
    import { page } from '$app/stores';
  </script>

  <div class="error-container specialFont">
    <h1>🥖 {$page.status} 🥨</h1>
    <p>Oops! Looks like this page is toast!</p>
    <p class="sub-text">Our bakers couldn't find the recipe you're looking for.</p>
    <div class="bakery-items">
      <span>🥐</span>
      <span>🎂</span>
      <span>🥯</span>
      <span>🍪</span>
    </div>
    <a href="/">Back to the bakery</a>
  </div>

  <style>
    .error-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      padding: 1rem;
      background-color: #fff8e8;
    }

    h1 {
      font-size: 4rem;
      margin-bottom: 1rem;
      color: #8b4513;
    }

    p {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #6b3000;
    }

    .sub-text {
      font-size: 1.2rem;
      color: #8b4513;
      margin-bottom: 2rem;
    }

    .bakery-items {
      font-size: 3rem;
      margin-bottom: 2rem;
      animation: float 3s ease-in-out infinite;
    }

    .bakery-items span {
      margin: 0 0.5rem;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    a {
      text-decoration: none;
      padding: 0.8rem 1.6rem;
      background-color: #8b4513;
      color: white;
      border-radius: 4px;
      transition: background-color 0.2s;
    }

    a:hover {
      background-color: #6b3000;
    }
  </style>
