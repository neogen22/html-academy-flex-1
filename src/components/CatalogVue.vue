<template>
    <div class="header-catalog">
        <span class="flex-catalog">
            <span>All categories</span>
            <span>/</span>
            <span>Woman</span>
            <span>/</span>
            <span>Jackets</span>
        </span>
        <span class='header-of-header-catalog'>Denim Collection Fall 2019</span>
        <img src="\public\61.svg">
    </div>
    <select>
        <option>Filter by</option>
    </select>
    <div class="catalog-flex">
        <div class="catalog-flex-item">
            <img src="\public\9.svg">
            <span>Jacket</span>
            <span>40$</span>
        </div>
        <div class="catalog-flex-item">
            <img src="\public\2.svg">
            <span>Jacket</span>
            <span>70$</span>            
        </div>
        <div class="catalog-flex-item">
            <img src="\public\4.svg">
            <span>Jacket</span>
            <span>60$</span>
        </div>
        <div class="catalog-flex-item">
            <img src="\public\11.svg">
            <span>Jacket</span>
            <span>50$</span>
        </div>
        <div class="catalog-flex-item">
            <img src="\public\15.svg">
            <span>Jacket</span>
            <span>40$</span>
        </div>
        <div class="catalog-flex-item">
            <img src="\public\1.svg">
            <span>Jacket</span>
            <span>110$</span>            
        </div>
        <div class="catalog-flex-item">
            <img src="\public\3.svg">
            <span>Jacket</span>
            <span>35$</span>
        </div>
        <div class="catalog-flex-item">
            <img src="\public\13.svg">
            <span>Jacket</span>
            <span>85$</span>
        </div>
    </div>
    <span class="showing">Showing 9 of 45 items</span>
    <div>
        <svg class='svg-line-1' width="40.000000" height="2.000000" viewBox="0 0 40 2" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <defs/>
            <line id="Line" x1="0.000000" y1="1.000000" x2="40.000000" y2="1.000000" stroke="#151C22" stroke-opacity="1.000000" stroke-width="2.000000"/>
        </svg>
        <svg class='svg-line-2' width="199.000000" height="2.000000" viewBox="0 0 199 2" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <defs/>
            <line id="Line" x1="0.000000" y1="1.000000" x2="159.000000" y2="1.000000" stroke="#E5E5E5" stroke-opacity="1.000000" stroke-width="2.000000"/>
        </svg>
    </div>
    <button>Load more</button>
</template>
<style scoped>
    button,
    button:active,
    button:focus  {
        margin-top: 41px;
        margin-bottom: 130px;
        margin-left: 583px;
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
    }
    .svg-line-1 {
        margin-left: 584px;
    }
    .svg-line-2 {
        position: absolute;
        margin-top: 12px
    }
    .showing {
        color: rgb(21, 28, 34);
        font-family: 'Work Sans';
        font-size: 18px;
        font-weight: 400;
        line-height: 21px;
        letter-spacing: 0%;
        text-align: left;
        margin-left: 583px;
    }
    .catalog-flex {
        display: flex;
        flex-direction: row;
        gap: 66px;
        margin-left: 98px;
        flex-wrap: wrap;
        margin-bottom: 83px;
    }
    .catalog-flex-item {
        display: flex;
        flex-direction: column;
        & img {
            width: 243px;
            height: 270px;
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
    select {
        width: 243px;
        height: 50px;
        margin-left: 1025px;
        margin-top: 40px;
        margin-bottom: 40px;
        color: rgb(21, 28, 34);
        font-family: 'Work Sans';
        font-size: 18px;
        font-weight: 500;
        line-height: -1px;
        letter-spacing: 0%;
        text-align: left;
    }
    .flex-catalog {
        display: flex;
        flex-direction: row;
        column-gap: 10px;
        position: absolute;
        color: rgb(114, 122, 130);
        font-family: 'Work Sans';
        font-size: 18px;
        font-weight: 500;
        line-height: -1px;
        letter-spacing: 0%;
        padding-top: 73px;
        padding-left: 298px;
        & span:last-child {
            color: rgb(21, 28, 34);
        }
    }
    .header-catalog {
        height: 260px;        
        background-color: rgb(241, 242, 244);
        & img {
            margin-left: 699px;
            height: 260px;
        }
        & .header-of-header-catalog {
            position: absolute;
            color: rgb(21, 28, 34);
            font-family: 'Work Sans';
            font-size: 32px;
            font-weight: 700;
            line-height: 125%;
            letter-spacing: 0%;
            text-align: left;
            padding-top: 125px;
            padding-left: 298px;
            width: 272px;
        }
    }
</style>