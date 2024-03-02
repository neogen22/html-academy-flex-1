<template>    
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
</template>
<style scoped>
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
</style>