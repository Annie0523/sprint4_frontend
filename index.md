---
layout: post
title: The Travelers
search_exclude: true
description: A website for travelers
hide: true
menu: nav/home.html
---
  <title>Travel Platform - Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background: #f4f7fc;
      color: #333;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background-color: #03a9f4;
      color: white;
    }
    header .logo {
      font-size: 2rem;
      font-weight: 500;
    }
    nav button {
      background: none;
      color: white;
      border: 2px solid white;
      padding: 10px 20px;
      margin-left: 15px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    nav button:hover {
      background-color: #0277bd;
    }
    .destinations {
      text-align: center;
      padding: 100px 20px;
      background-image: url('https://assets.thehansindia.com/h-upload/2023/04/15/1346887-road-trips.jpg/1500x600'); /* Sample Image URL */
      background-size: cover;
      color: white;
      background-position: center;
    }
    .destinations h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      font-weight: 600;
      color: white;
    }
    .destinations p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .buttons-container {
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    .buttons-container button {
      padding: 15px 30px;
      font-size: 1rem;
      background: #ff5722;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .buttons-container button:hover {
      background-color: #e64a19;
    }
    .section-title {
      font-size: 1.5rem;
      font-weight: 500;
      text-align: center;
      margin: 50px 0 20px;
    }
    .card-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      padding: 0 50px;
    }
    .card {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      cursor: pointer;
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 20px;
    }
    .card-title {
      font-size: 1.2rem;
      font-weight: 500;
      margin-bottom: 10px;
    }
    .card-text {
      font-size: 0.9rem;
      color: #777;
    }
    .comment-section {
      text-align: center;
      margin-top: 50px;
    }
    .comment-section button {
      padding: 10px 20px;
      background-color: #0288d1;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    .comment-section button:hover {
      background-color: #0277bd;
    }
  </style>

  <!-- Header Section -->
  <header>
    <div class="logo">TravelSphere</div>
    <nav>
      <button>Home</button>
      <button>Explore</button>
      <button>Profile</button>
    </nav>
  </header>

  <!-- Destinations Section -->
  <section class="destinations">
    <h1>Explore the World, there must be a place thats perfect for you!</h1>
    <p>Your journey begins here. Discover, connect, and share your travel experiences.</p>
    <div class="buttons-container">
      <button>Register</button>
      <button>Log In</button>
    </div>
  </section>

  <!-- Featured Destinations Section -->
  <section>
    <h2 class="section-title">Featured Destinations</h2>
    <div class="card-container">
      <div class="card">
       <img src="https://www.ancient-origins.net/sites/default/files/styles/article_image/public/field/image/The-Great-Wall-of-China.jpg?itok=JM77k6Tz/400x200" alt="Attraction 1">
        <div class="card-content">
          <div class="card-title">Great Wall of China</div>
          <p class="card-text">China's most spectacular and majestic man-made building spans the entire country and represents China's long history.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://media.cntraveler.com/photos/6244a325633ca4951bd9a1d9/16:9/w_2580,c_limit/Great%20Sand%20Dunes%20National%20Park_josh-gordon-ONxt3hLkvs0-unsplash.jpg/400x200" alt="Attraction 2">
        <div class="card-content">
          <div class="card-title">Death valley's Starnight</div>
          <p class="card-text">Best location in United States for stargazing, an incredible experience under the starry night.</p>
        </div>
      </div>
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTc9-DW8OD8RwGAI6RC966ZQc1xIbdzkk19WsO_EQl-rxXf8GfDotNW0Sk5xNY0GqOdeP0&usqp=CAU/400x200" alt="Attraction 3">
        <div class="card-content">
          <div class="card-title">Zhangjiajie National Forest Park</div>
          <p class="card-text">The stunning landscape that inspired Avatar's floating mountains.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Leave a Comment Section -->
  <section class="comment-section">
    <button>Leave a Comment</button>
  </section>

