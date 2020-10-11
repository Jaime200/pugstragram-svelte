<script>
import Comments from './Comments.svelte'
</script>

<div class="Card">
    <div class="Card__container">
        <div class="Card__header">
            <div class="Card__user">
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
                <h2>Elmo.pug</h2>
                <span>Bogota Colombia</span>
            </div>            
            <div class="Card__settings">
                <i class='fas fa-ellipsis-h' ></i>
            </div>
        </div>
        <div class="Car__photo">
            <figure>
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
            </figure>
        </div>   
        <div class="Card__icons">
            <div class="Card__icons--first">
                <i class="fas fa-heart"></i>
                <i class="fas fa-paper-plane"></i>
            </div>
            <div class="Card__icons--second">
                <i class="fas fa-bookmark"></i>
            </div>             
        </div>  

        <div class="Card__description">
            <h3>elmo.pug</h3>
            <span>Hola</span>
            <Comments/>
        </div>
          
    </div>
</div>