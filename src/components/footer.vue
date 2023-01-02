<template>
  <div>
       <div class="footer-header">
        <div class="footer-hold">

            <div class="items-hold">
            <div class="footer-items">
                <h5>THE(iBox) MOVEMENT</h5>
                <a href="#"><p>(iBox) BLOG</p></a>
                <a href="#"><p>Press</p></a>
                <a href="#"><p>FAQs & Contact</p></a>
            </div>

            <div class="footer-items">
                <h5>GET INVOLVED</h5>
                <a href="#"><p>Donate</p></a>
                <a href="#"><p>Careers</p></a>
                <a href="#"><p>The ONE Campaign</p></a>
            </div>

            <div class="footer-items">
                <h5>STAY CONNECTED</h5>
                <a href="#"><span class="fab fa-facebook-f"></span></a>
                <a href="#"><span class="fab fa-twitter"></span></a>
                <a href="#"><span class="fab fa-instagram"></span></a>
            </div>

            <div class="footer-items">
                <h5>LET'S KEEP IN TOUCH</h5>
                <input type="text" placeholder="Enter your email address...">
                <input type="button" value="JOIN">
                <br>    

                <div class="confirm">
                    <input id="checkbox" type="checkbox">
                    <p>Yes, I'd like to hear about how can I help fight <br> extreme poverty with the READBAR Campaign.</p>
                </div>

            </div>
        </div>
        
        </div>
    </div>

    <div class="last-footer">
        <div class="campaign">
            <b-navbar-brand class="logoFooter" href="#">iBox.com</b-navbar-brand>
            <ul>
                <li><a href="#">PRIVACY POLICY</a></li>
                <li><a href="#">TERMS OF SERVICE</a></li>
                <a href="https://t.me/thereacts"><h4 class="divFcz">By Dev FCZ :)</h4></a>
            </ul>
        </div>
    </div>
  </div>
</template>

<style>
    .footer-header {
    line-height: 28px;
    margin-top: 120px;
    padding-top: 55px;
    padding-bottom: 55px;
    padding-left: 80px;
    padding-right: 80px;
    background-color: #1A1A1A;
}

.footer-header p {
    color: #7A7B7D;
    font-size: 13.5px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

.confirm {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
    margin-right: 70px;
}

.confirm p {
    margin-left: -58px;
    line-height: 17px;
}

.confirm [type='checkbox'] {
    margin-right: 70px;
}

.footer-header h5 {
    color: #5A5A5A;
    padding-bottom: 10px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

.footer-header a {
    text-decoration: none;
    transition: all 0.4s;
}

.footer-header a:hover {
    text-decoration: underline;
    color: #7A7B7D;
}

.fa-facebook-f,
.fa-twitter,
.fa-instagram {
    color: #7A7B7D;
    margin-right: 15px;
    font-size: 19px;
    cursor: pointer;
    transition: all 0.2s;
}

.fa-facebook-f:hover,
.fa-twitter:hover,
.fa-instagram:hover {
    color: rgb(68, 70, 70);
}

.footer-items [type='text'] {
    border-radius: 1px;
    background-color: #383838;
    padding: 14px 25px;
    border: none;
    outline: none;
    color: #fff;
}

.footer-items [type='text']::placeholder {
    color: #7A7B7D;
}

.footer-items [type='button'] {
    border: none;
    outline: none;
    background-color: #2A2A2A;
    color: #fff;
    position: absolute;
    padding: 14px 25px;
    border-radius: 1px;
    cursor: pointer;
}

.footer-items [type='button']:hover {
    background-color: #252525;
}

.footer-header span {
    color: #7A7B7D;;
}

.items-hold {
    display: flex;
    justify-content: space-between;
}

.last-footer {
    background-color: #0E0E0E;
}

.campaign {
    display: flex;
    justify-content: space-between;
    padding-left: 72px;
    padding-right: 144px;
    align-items: center;
    padding-top: 25px;
    padding-bottom: 25px;
}

.campaign ul {
  list-style: none;
}

.campaign a {
    text-decoration: none;
    color: #5A5A5A;
    transition: all 0.4s; 
    font-size: 0.83em;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

.campaign a:hover {
    text-decoration: underline;
    color: #7A7B7D;
}

.campaign img {
    width: 150px;
    cursor: pointer;
}

.divFcz {
  display: flex;
  justify-content: center;
  align-items: center;
}

.campaign .logoFooter {
  font-size: 21px;
}

.campaign .logoFooter:hover {
  text-decoration: none;
}
</style>