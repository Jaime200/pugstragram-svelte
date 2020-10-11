<script>

</script>
<style>

.Header {
    background-color: white;
    position: fixed;
    width: 100%;    
}

.Header__container{
    display: grid;
    justify-content: center;
    grid-template-columns: minmax(auto, 936px);
    background-color: white;
    border-bottom: 1px solid rgba(38, 38, 38, 0.4);
}

.Header__content{
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;
padding: 0.5em;
}

.Header__nav ul{
    list-style-type: none;
}

.Header__nav ul li {
    display: inline-block;
    margin: 0 0 0 1em;
}

h1 {
    padding: 0;
    margin: 0;
    font-size: 28px;
    color: black;
    font-family: "Pacifico", cursive;
    cursor: pointer;
    position: relative;
    background: #fff;
    mix-blend-mode: multiply;
    display: inline-block;
  }

  h1:before {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at top left, #f09433, #bc1888);
    mix-blend-mode: screen;
    position: absolute;
    top: 0;
    left: 0;
  }
</style>
<header class="Header">
    <div class="Header__container">
        <div class="Header__content">
            <div class="Header__content-logo">
                    <h1>Pugstagram</h1>
            </div>
            <div class="Header__nav">
                <ul>
                    <li><i class="fas fa-heart"></i></li>
                    <li><i class="fas fa-user-alt"></i></li>
                </ul>
            </div>
        </div>
    </div>
    
</header>