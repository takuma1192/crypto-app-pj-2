<template>
  <div class="chart-page">
      <div class="header-wrap">
        <h1>Crypto App</h1>
        <p>ログアウト</p>
      </div>
      <div class="title">
        <h2>・銘柄一覧</h2>
      </div>
      <div class="detail">
        <div class="lists">
          <h2>【現物取引】</h2>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-BTC.svg" />
              <p>BTC</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-ETH.svg" />
              <p>ETH</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-BCH.svg" />
              <p>BCH</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-LTC.svg" />
              <p>LTC</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-XRP.svg" />
              <p>XPR</p>
            </div>
            <button class="button">詳細</button>
          </div>
        </div>
        <div class="lists">
          <h2>【レバレッジ取引】</h2>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-btc-jpy.svg" />
              <p>BTC/JPY</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-eth-jpy.svg" />
              <p>ETH/JPY</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-bch-jpy.svg" />
              <p>BTH/JPY</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-ltc-jpy.svg" />
              <p>LTC/JPY</p>
            </div>
            <button class="button">詳細</button>
          </div>
          <div class="item">
            <div class="logo">
              <img src="./assets/icon-xrp-jpy.svg" />
              <p>XPR/JPY</p>
            </div>
            <button class="button">詳細</button>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
@charset "UTF-8";

/*
html5doctor.com Reset Stylesheet
v1.6.1
Last Updated: 2010-09-17
Author: Richard Clark - http://richclarkdesign.com
Twitter: @rich_clark
*/

html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

.chart-page {
  height: 100%;
  background: #E5E5E5;
}

.header-wrap {
  display: flex;
  justify-content: space-between;
}

.header-wrap h1 {
  font-size: 60px;
  font-weight: bold;
  text-decoration: underline;
  padding: 20px;
}

.header-wrap p {
  font-size: 20px;
  font-weight: bold;
  text-decoration: underline;
  padding: 40px;
}

.title {
  font-size: 40px;
  padding: 20px;
}

.detail {
  display: flex;
  justify-content: space-around;
}

.detail h2 {
  font-size: 40px;
}

.lists {
  margin-bottom: 30px;
} 

.lists h2 {
  padding: 8px;
}

.item {
  display: flex;
}

.item button {
  white-space: nowrap;
  font-size: 30px;
  margin: 10px 40px;
  padding: 0 50px;
  background: #ffffff;
  border: none;
  border-radius: 30px;
  
}

.logo {
  width: 100%;
  display: flex;
  background: #ffffff;
  margin: 10px;
  padding: 10px 200px 10px 20px;
}

.logo img {
  width: 100%;
  height: 100px;
}

.logo p {
  font-size: 40px;
  font-weight: bold;
  margin: 30px;
  padding-left: 45px;
}
</style>
