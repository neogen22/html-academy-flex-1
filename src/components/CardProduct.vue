<template>
    <body>
        <div class="container-nav">
            <span>Woman</span>
            <span>Man</span>
            <span>New</span>
            <span class="nimes">Nîmes</span>
            <svg width="20.003906" height="20.004089" viewBox="0 0 20.0039 20.0041" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <defs/>
            <path id="Vector" d="M9 17C4.58203 17 1 13.4183 1 9C1 4.58173 4.58203 1 9 1C13.418 1 17 4.58173 17 9C17 13.4183 13.418 17 9 17ZM19 19L14.6504 14.65" stroke="#151C22" stroke-opacity="1.000000" stroke-width="2.000000" stroke-linejoin="round" stroke-linecap="round"/>    
            </svg>
            <svg width="22.000000" height="20.000000" viewBox="0 0 22 20" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">	
            <defs/>
            <path id="Vector" d="M8.27344 19C7.77148 19 7.36328 18.6162 7.36328 18.1429C7.36328 17.6695 7.77148 17.2857 8.27344 17.2857C8.77539 17.2857 9.18164 17.6695 9.18164 18.1429C9.18164 18.6162 8.77539 19 8.27344 19ZM18.2734 19C17.7715 19 17.3633 18.6162 17.3633 18.1429C17.3633 17.6695 17.7715 17.2857 18.2734 17.2857C18.7754 17.2857 19.1816 17.6695 19.1816 18.1429C19.1816 18.6162 18.7754 19 18.2734 19ZM1 1L4.63672 1L7.07227 12.4771C7.15625 12.8718 7.38281 13.2263 7.7168 13.4785C8.04883 13.7308 8.46484 13.8648 8.89062 13.8571L17.7266 13.8571C18.1543 13.8648 18.5703 13.7308 18.9023 13.4785C19.2344 13.2263 19.4629 12.8718 19.5449 12.4771L21 5.28571L5.54492 5.28571" stroke="#151C22" stroke-opacity="1.000000" stroke-width="2.000000" stroke-linejoin="round" stroke-linecap="round"/>
            </svg>
        </div>
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
        <footer>
            <div class="footer-header">Nîmes</div>
            <div class="footer-header-flex">
                <span>Shop</span>
                <span>Delivery</span>
                <span>Service</span>
                <span>Sitemap</span>
                <span>Contacts</span>
            </div>
            <div class="footer-icons-flex">
                <img src="\public\Facebook.svg">
                <img src="\public\Instagram.svg">
                <img src="\public\D.svg">
                <img src="\public\Twi.svg">
            </div>
        </footer>
    </body>    
</template>
<style scoped>
    body {
        margin: 0 auto;
    }
    footer {
        background-color: rgb(21, 28, 34);
        color: white;
        height: 222px;
        & .footer-icons-flex {
            display: flex;
            flex-direction: row;
            column-gap: 30px;
            margin-left: 604px;
            margin-top: 37px;
            margin-bottom: 50px;
        }
        & div {
            color: rgb(255, 255, 255);
            font-family: 'Work Sans';
            font-size: 24px;
            font-weight: 700;
            line-height: -1px;
            letter-spacing: 0%;   
            text-align: center;
        }
        & div span {
            color: rgb(255, 255, 255);
            font-family: 'Work Sans';
            font-size: 18px;
            font-weight: 500;
            line-height: -1px;
            letter-spacing: 0%;
            text-align: left;
        }
        & .footer-header-flex {
            display: flex;
            flex-direction: row;
            column-gap: 35px;
            margin-left: 445px;
            margin-top: 35px;
        }
        & .footer-header {
            padding-top: 50px
        }
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
    .container-nav {
        display: flex;
        column-gap: 35px;
        margin-left: 98px;
        align-items: baseline;
        box-sizing: border-box;        
        & span {
            color: rgb(21, 28, 34);
            font-family: "Work Sans", sans-serif;
            font-size: 16px;
            font-weight: 500;
            letter-spacing: 0%;
        }
        .nimes {
            color: rgb(21, 28, 34);
            font-family: "Work Sans", sans-serif;
            font-size: 24px;
            font-weight: 700;
            margin-left: 326px;
            margin-right: 439px;
        }
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