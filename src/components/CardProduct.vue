<template>
    <body>
        <div class="container-test">
            <div class="container-pictures-card">
                <img src="\public\55.svg">
                <img src="\public\56.svg">
                <img src="\public\57.svg">
                <img src="\public\58.svg">
                <img src="\public\59.svg">
            </div>
            <div class="card-overalls">
                <div class="header">Overalls</div>
                <p class="card-overalls-p">
                    Overalls in washed organic cotton denim. Collar, button fly, and adjustable belt at waist. Chest pockets with flap. Long, gently flared sleeves and straight legs with front pockets and back pockets.
                </p>
                <p class="color">Color</p>
                <div class="card-ellipses">
                    <img src="\public\Ellipse.svg">
                    <img src="\public\Ellipse1.svg">
                    <img src="\public\Ellipse2.svg">
                </div>
                <p class="size">Size</p>
                <div class="card-sizes">
                    <span>XS</span>
                    <span>S</span>
                    <span>M</span>
                    <span>L</span>
                    <span>XL</span>
                </div>
                <p class="price">$160</p>
                <button>Add to cart</button>
            </div>
        </div>
        <div class="you">
            <span>You may also like</span>
            <span>View all</span>
            <div class="line"></div>
        </div>
        <div class="card-container-end">
            <div class="card-container-end-inside-card">
                <img src="\public\64.svg">
                <span>Overalls</span>
                <span>$140</span>
            </div>
            <div class="card-container-end-inside-card">
                <img src="\public\60.svg">
                <span>Overalls</span>
                <span>$110</span>
            </div>
            <div class="card-container-end-inside-card">
                <img src="\public\21.svg">
                <span>Overalls</span>
                <span>$110</span>
            </div>
            <div class="card-container-end-inside-card">
                <img src="\public\41.svg">
                <span>Overalls</span>
                <span>$110</span>
            </div>
        </div>
    </body>    
</template>
<script>

</script>
<style scoped>
    body {
        margin: 0 auto;
    }
    img {
        margin-left: 0;
        padding-left: 0;
    }
    .card-container-end {
        display: flex;
        flex-direction: row;
        column-gap: 30px;
        margin-left: 98px;
    }
    .card-container-end-inside-card {
        display: flex;
        flex-direction: column;
        padding-bottom: 130px;
        & img {
            width: 270px;
            height: 349px;
            padding-bottom: 25px;
        }
        & span {
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 18px;
            font-weight: 500;
            line-height: -1px;
            letter-spacing: 0%;
            text-align: left;
            
        }
        & span:last-child {
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 16px;
            font-weight: 700;
            line-height: 19px;
            letter-spacing: 0%;
            text-align: left;
            padding-top: 15px;
        }
    }
    .you {
        margin-top: 130px;
        margin-left: 98px;
        color: rgb(21, 28, 34);
        font-family: 'Work Sans';
        font-size: 32px;
        font-weight: 700;
        line-height: 38px;
        letter-spacing: 0%;
        text-align: left;
        padding-bottom: 70px;
        & span:nth-child(2) {
            padding-left: 822px;
            font-size: 18px;
            font-weight: 500;
        }
        .line {
            width: 80px;
            border: 1px solid rgb(21, 28, 34);
            margin-left: 1090px;
            height: 1px;
        }
    }
    p {
        margin: 0;
        padding: 0;
    }

    div {
        box-sizing: border-box;
    }
    button {
        background-color: black;
        color: white;
        width: 200px;
        height: 64px;        
        margin-left: 70px;
        border: none;
        font-family: "Work Sans", sans-serif;
        font-size: 16px;
        font-weight: 700;
        line-height: 19px;
        letter-spacing: 0%;
    }
    .price {
        color: rgb(21, 28, 34);
        font-family: "Work Sans";
        font-size: 18px;
        font-weight: 700;
        line-height: 21px;
        margin-bottom: 50px;
        margin-left: 70px;
    }
    .card-sizes {
        margin-left: 70px;
        display: flex;
        gap: 20px;
        color: rgb(114, 122, 130);
        font-family: "Work Sans", sans-serif;
        font-size: 18px;
        font-weight: 500;
        margin-bottom: 30px;
        & span:nth-child(2) {
            color: rgb(21, 28, 34)
        }
    }
    .size {
        color: rgb(21, 28, 34);
        font-family: "Work Sans", sans-serif;
        font-size: 18px;
        font-weight: 500;
        margin-bottom: 20px;
        margin-left: 70px;
    }
    .color {
        color: rgb(21, 28, 34);
        font-family: "Work Sans", sans-serif;
        font-size: 18px;
        font-weight: 500;
        margin-bottom: 18px;
        padding-left: 70px;
    }
    .card-ellipses {
        display: flex;
        gap: 30px;
        margin-left: 70px;
        margin-bottom: 35px;
    }
    
    .card-overalls-p {
        color: rgb(21, 28, 34);
        font-family: "Work Sans", sans-serif;
        font-size: 16px;
        font-weight: 400;
        line-height: 19px;
        width: 370px;
        height: 87px;
        padding-left: 70px;
        margin-bottom: 50px;
        letter-spacing: 0%;
        text-align: left;
    }
    .container-test {
        display: flex;
        gap: 130px;
        flex-direction: row;
        margin-top: 80px;
    }
    .card-overalls {
        background: rgb(241, 242, 244);
        width: 668px;
        height: 656px;
    }
    .container-pictures-card {
        display: flex;
        flex-direction: row;
        width: 400px;
        flex-wrap: wrap;
        gap: 20px;        
        margin-left: 168px;
    }
    .header {
        color: rgb(21, 28, 34);
        font-family: "Work Sans", sans-serif;
        font-size: 32px;
        font-weight: 700;
        line-height: 38px;
        margin-top: 63px;
        padding-left: 70px;
        margin-bottom: 30px;
    }


</style>