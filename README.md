<div class="animated-header-container">
  <h1>Hello world, I'm Syam 👋</h1>

  <style>
    @keyframes gradientBackground {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      66% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    .animated-header-container {
      font-family: system-ui, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji';
      display: flex;
      flex-direction: column;
      margin: 0;
      text-align: center;
      width: 800px;
      height: 120px;
      background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
      background-size: 600% 400%;
      animation: gradientBackground 10s ease infinite;
      border-radius: 10px;
      color: white;
      justify-content: center;
      align-items: center;
    }

    .animated-header-container h1 {
      font-size: 40px;
      line-height: 1.3;
      letter-spacing: 5px;
      text-transform: uppercase;
      text-shadow: 
        0 1px 0 #efefef,
        0 2px 0 #efefef,
        0 3px 0 #efefef,
        0 4px 0 #efefef,
        0 12px 5px rgba(0, 0, 0, 0.1);
      animation: fadeIn 1s ease 0s normal forwards 1;
      margin: 0;
      padding: 10px;
    }
  </style>
</div>