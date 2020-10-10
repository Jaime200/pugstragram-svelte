<script>

</script>
<style>

.Header {
    background-color: white;
    border-bottom: 1px solid rgba(38, 38, 38, 0.4);
}

.Header__container{
    display: grid;
    justify-content: center;
    grid-template-columns: minmax(auto, 936px)
}

.Header__content{
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;
}

.Header__nav ul{
    display: flex;
    flex-direction: row;
    list-style-type: none;
}

.Header__nav ul li {
    margin-right: 20px;
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