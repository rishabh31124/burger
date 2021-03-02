<template>
    <figure class="burger">
            <div class="burger__hero">
                <img src="img/Burger.jpg" alt="Burger-photo" class="burger__img">
            </div>
            <div class="burger__content">
                <div class="burger__title">
                    <h1 class="burger__heading">Burger VEGETALE</h1>
                    <div class="burger__tag burger__tag-1">
                        #Vegetarian
                    </div>
                    <div class="burger__tag burger__tag-2">
                        #Italian
                    </div>
                </div>
                <p class="description">
                    yummy veggie burger with tasty olives , crisp proppers.fresh arugula and original tomato italian sauce
                </p>
                <div class="burger_det">
                    <p class="burger_detail"><span class="emoji">#</span>850 Kcal</p>
                    <p class="burger_detail"><span class="emoji">#</span>30 min</p>
                    <p class="burger_detail"><span class="emoji">#</span>4.7/5</p>
                </div>
            </div>
            
            <div class="burger__price">
                Rs.120/-
            </div>
    </figure>
    
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.burger{
    display: flex;
    max-width: 800px;
    border-radius: 4px;
    box-shadow: 0 30px 80px 10px rgba(231, 215, 215, 0.932);
    align-items: stretch;
    overflow: hidden;

}
.burger__img{
    width: 110%;
    display: block;
    height: 110%;

}
.burger__content{
    background: rgba(226, 201, 148, 0.938);
    flex: 1;
    padding: 35px 30px;
    flex-direction: column;
    align-items: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.burger__hero{
    flex: 0 0 45%;
}
.burger__price{
    background: linear-gradient(to bottom , #faddcf,hsl(34, 93%, 62%));
    flex: 0 0 50px;
    font-size: 18px;
    writing-mode: vertical-rl;
    align-items: center;
    color: white;
    display: flex;
    align-self: center;
}
.burger__title{
    display: flex;
    align-items: center;
    flex: 2;
    margin-right: auto;
    margin-bottom: 10px;

}
.burger__heading{
    font-size: 20px;
    
}
.burger__tag{
    font-size: 15px;
    margin-left: 7px;
    color: white;
    padding: 2px 7px;
    border-radius: 100px;
    text-transform: uppercase;
}
.burger__tag-1{
    background-color: #d1b28e;
}
.burger__tag-2{
    background-color: #ec8556;
}
.description{
    font-size: 14px;
}
.burger_det{
    display: flex;
   align-items: center;
   margin-top: auto;
}
.burger_detail{
    display: flex;
    font-size: 15px;
    text-transform: uppercase;
    margin-right: 20px;
    font-weight: 700;
    align-items: center;
}
.emoji{
    font-size: 20px;
    margin-right: 3px;
    
}

</style>
