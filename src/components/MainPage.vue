<template>
    <div class="header-main-page">
        <img src="\public\matheus.png">
        <div>
            <span>The quality you deserve</span>
            <span>DENIM</span>
            <button>Check new collection</button>            
        </div>
    </div>
    <div class="header">        
        <span class="header-small">Bestsellers</span>
        <div>
            <span class="header-s">View all</span>
            <div></div>
        </div>
    </div>
    <div class="flex">
        <div class="flex-inside">
            <img src="\public\63.svg">
            <span>Jacket</span>
            <span>$120</span>
        </div>
        <div class="flex-inside">
            <img src="\public\64.svg">
            <span>Overalls</span>
            <span>$140</span>
        </div>
        <div class="flex-inside">
            <img src="\public\62.svg">
            <span>Jacket</span>
            <span>$90</span>
        </div>
        <div class="flex-inside">
            <img src="\public\65.svg">
            <span>Overalls</span>
            <span>$160</span>
        </div>
    </div>
    <div class="header">        
        <span class="header-small">News</span>
        <div>
            <span class="header-s">View all</span>
            <div></div>
        </div>
    </div>
    <div class="flex-news">
        <img src="\public\67.png">
        <div>
            <span>G- Star Updates Its Sustainable Collection</span>
            <span>Feb 12, 2020</span>
            <span>G-Star Raw is pushing the sustainability movement forward with a collection of stretch denim items for spring 2020 which is particularly designed for reuse...</span>
            <button>Read more...</button>
        </div>
    </div>
    <div class="header">        
        <span class="header-small">Shop by category</span>
        <div>
            <span class="header-s">View all</span>
            <div></div>
        </div>
    </div>
    <div class="flex">
        <div class="flex-inside">
            <img src="\public\5.svg">
            <span>Jeans</span>
        </div>
        <div class="flex-inside">
            <img src="\public\52.svg">
            <span>Shirts</span>
        </div>
        <div class="flex-inside">
            <img src="\public\53.svg">
            <span>Jackets</span>
        </div>
        <div class="flex-inside">
            <img src="\public\54.svg">
            <span>Overalls</span>
        </div>
    </div>
</template>
<style scoped>
    .flex-news {
        display: flex;
        flex-direction: row;
        margin-left: 98px;
        margin-top: 71px;
        & div {
            width: 400px;
            height: 397px;
            background-color: rgb(241, 242, 244);
            margin-top: 31px;
            & span {
                display: block;
                width: 358px;
                color: rgb(21, 28, 34);
                font-family: 'Work Sans';
                font-size: 24px;
                font-weight: 700;
                line-height: 28px;
                letter-spacing: 0%;
                text-align: left;
                padding-top: 52px;
                padding-left: 43px;
            }            
            & span:nth-child(2) {
                color: rgb(0, 0, 0);
                font-family: 'Work Sans';
                font-size: 18px;
                font-weight: 400;
                line-height: 21px;
                letter-spacing: 0%;
                text-align: left;
                padding-top: 27px;
            }
            & span:nth-child(3) {
                display: block;
                color: rgb(114, 122, 130);
                font-family: 'Work Sans';
                font-size: 18px;
                font-weight: 400;
                line-height: 21px;
                letter-spacing: 0%;
                text-align: left;
                width: 310px;
                padding-top: 13px;
            }
            button,
            button:active,
            button:focus  {
                width: 200px;
                height: 64px;
                background-color: black;
                color: white        ;
                font-family: 'Work Sans';
                font-size: 16px;
                font-weight: 700;
                line-height: 19px;
                letter-spacing: 0%;
                text-align: center;
                border: none;
                margin-top: 24px;
                margin-left: 43px;
            }
        }
        & img {
            width: 700px;
            height: 370px
        }

    }
    .flex {
        display: flex;
        flex-direction: row;
        column-gap: 30px;
        margin-left: 98px;
        margin-bottom: 108px;
    }
    .flex-inside {
        display: flex;
        flex-direction: column;
        & img {
            width: 270px;
            height: 349px;
        }
        & span {
            padding-top: 25px;
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 18px;
            font-weight: 500;
            line-height: -1px;
            letter-spacing: 0%;
            text-align: left;
        }
        & span:last-child {
            padding-top: 15px;
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 16px;
            font-weight: 700;
            line-height: 19px;
            letter-spacing: 0%;
            text-align: left;
        }
    }
    .header {
        margin-left: 98px;
        margin-top: 130px;
        margin-bottom: 70px;
        display: flex;
        align-items: baseline;
        justify-content: space-between;       
        width: 1170px;
        .header-small {
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 32px;
            font-weight: 700;
            line-height: 38px;
            letter-spacing: 0%;
        }
        .header-s {            
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 18px;
            font-weight: 500;
            line-height: -1px;
            letter-spacing: 0%;
            text-align: right;
        }
        & div {
            display: flex;
            flex-direction: column;
        }
        & div div{
            border: 1px solid rgb(21, 28, 34);
            width: 70px;
        }
    }
    .header-main-page {
        & img {
            position: absolute;
            margin-top: 50px;
            margin-left: 668px;
        }
        & div {
            margin-left: 263px;
        }
        height: 617px;
        background-color: rgb(241, 242, 244);
        & span:first-child {
            display: block;
            padding-top: 192px;
            color: rgb(114, 122, 130);
            font-family: 'Work Sans';
            font-size: 18px;
            font-weight: 400;
            line-height: 21px;
            letter-spacing: 0%;
            text-align: left;
            margin-bottom: 25px;
        }
        & span:nth-child(2) {
            color: rgb(21, 28, 34);
            font-family: 'Anton';
            font-size: 128px;
            font-weight: 400;
            line-height: -1px;
            letter-spacing: 0%;
            text-align: left;            
        }
        & button,
            button:active,
            button:focus {
            display: block;
            width: 219px;
            height: 64px;
            background-color: black;
            color: white;
            text-align: center;
            color: rgb(255, 255, 255);
            font-family: 'Work Sans';
            font-size: 16px;
            font-weight: 700;
            line-height: 19px;
            letter-spacing: 0%;
            margin-top: 50px;
            border: none;
          }
    }
</style>