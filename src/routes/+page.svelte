<div class="container">
    <div class="header">
        <h1> Image Gallery </h1>
        <div class="input-container">
            <input type="text" class = "input">
            <button class="button"> Search </button>
        </div>
    </div>
    <div class="photos"></div>
    <img src="" alt="" class = "image">
    <img src="" alt="" class = "image">
    <img src="" alt="" class = "image">
    <img src="" alt="" class = "image">
</div>




<style>
    .image {
      width: 400px;
      height: 250px;
      margin: 5px;
    }
    .photos {
      display: flex;
      flex-wrap: wrap;
    }
    .container {
      width: 1230px;
      margin: 0 auto;
    }
    .header {
      text-align: center;
      font-size: 20px;
    }
    .input {
      padding: 10px;
      width: 400px;
      border-radius: 20px;
      outline: none;
      border: 1px solid gray;
      font-size: 20px;
    }
    .button {
      padding: 10px;
      font-size: 20px;
      background-color: rgb(123, 97, 97);
      border-radius: 20px;
      border: none;
      color: white;
    }
    .input-container {
      margin-bottom: 40px;
    }
  </style>