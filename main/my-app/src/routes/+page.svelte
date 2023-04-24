<script>
  import "../app.css";
  let speed;

  const news_API =
    "https://api.worldnewsapi.com/search-news?source-countries=in&text=India&api-key=99e9473c641141b08e3bff49deedffc1";
</script>

<div class="header">
  <div class="name">
    <h1 id="hf1">News</h1>
    <h1 id="hf2">Type.</h1>
  </div>

  <select id="dropdown" name="options">
    <option value="option1">Times Of India</option>
    <option value="option2">Hindustan Times</option>
    <option value="option3">The Hindus</option>
  </select>
</div>
<div class="box" />
<div class="main_type">
  <p>
    Leaders said the Udaipur declaration on reserving 50% organisational posts
    for those below 50, the 'one-family, one-ticket' norm (serving and ex-party
    chiefs excluded), capping tenures, enhancing representation to socially
    backwards, minorities and women, could be brought as resolutions.
  </p>

  <h1 id="timer">30</h1>
  <label
    style="font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif"
    for="to_restart color:gray">press space to restart</label
  >
  <div class="data">
    <h2 id="speed">Speed: 50</h2>
    <h2 id="Accuracy">Accuracy: 100%</h2>
  </div>
</div>

<style>
  h1,
  p {
    font-family: "Inter", sans-serif;
    color: white;
  }

  p {
    font-size: 1.8rem;
  }

  h1 {
    font-size: 2.5rem;
  }

  #hf1 {
    color: #71c9ce;
  }
  #hf2 {
    color: white;
    font-weight: 400;
  }

  .name {
    display: flex;
  }
  .header {
    margin: 1rem 5rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  select {
    height: 50px;
    width: 250px;
    padding: 5px 10px;
    border-radius: 10px;
    border: none;
    background-color: #393e46;
    font-size: 1.3rem;
  }
  .box {
    width: 100vw;
    height: 1px;
    background-color: #ffffff;
    margin-top: -30px;
  }

  .main_type {
    margin: 10rem 5rem;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #timer {
    font-family: "Roboto", sans-serif;
    font-size: 3rem;
    margin-top: 2rem;
    /* display: none; */
  }
  h2,
  label {
    display: none;
  }

  select,
  h2 {
    font-family: "Montserrat", sans-serif;
    color: white;
  }

  label {
    color: gray;
    margin-top: 10px;
  }

  h2 {
    margin: 5px;
  }
  .data {
    margin-top: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
  }
</style>
