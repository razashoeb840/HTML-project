# HTML-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SRDIGITALAB</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}

body {
    background-color: #0e0e0e;
    color: #f5f5f5;
    font-family: 'Poppins', sans-serif;
}

#background-video {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
    opacity: 0.4;
}

header {
    text-align: center;
    padding: 2rem 0;
    background-color: rgba(0, 0, 0, 0.7);
    position: sticky;
    top: 0;
    z-index: 999;
    box-shadow: 0 2px 10px rgba(226, 9, 9, 0.5);
}

header h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
    font-family: 'Orbitron', sans-serif;
    color: #00f7ff;
    font-weight: bold;
}

header p {
    margin-bottom: 1rem;
    font-size: 1.2rem;
    color: #ff6200;
}

header nav {
    margin-top: 1rem;
}

header nav a {
    margin: 0 1.5rem;
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.5rem;
    font-family: 'Cursive', sans-serif;
    position: relative;
   
}

header nav a:hover {
    color: #00f7ff;
}

.menu-section {
    padding: 2rem;
    text-align: center;
    

}

.menu-section h2 {
    font-size: 3rem;
    color: #ff6200;
    margin-bottom: 1.5rem;
    font-family: 'Orbitron', sans-serif;
    
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
    
}

.menu-item {
    background-color: #1a1a1a;
    padding: 1.5rem;
    border-radius: 10px;
    box-shadow: 5px 10px 8px 2px rgba(6, 208, 239, 0.662);
    transition: transform 0.3s ease;
    position: relative;
    /* overflow: hidden; */
    background: linear-gradient(135deg, #2d4b68, #0a0a0a);
   
}

.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

.menu-item h3 {
    font-size: 1.8rem;
    margin: 1rem 0;
    color: #00f7ff;
}

.menu-item p {
    font-size: 1.2rem;
    color: #cccccc;
   
}

.price {
    font-size: 1.7rem;
    color: #1ace47;
    font-weight: bold;
    margin: 1rem 0;
   font-family: cursive;
}

button {
    padding: .7rem 1.5rem ;
    border: none;
    background-color: #ff6200;
    color: #ffffff;
    font-size: 1rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  

}

button:hover {
    background-color: #00f7ff;
    color: #0e0e0e;
}

footer {
    text-align: center;
    padding: 2rem;
    background-color: #0e0e0e;
    color: #f5f5f5;
    margin-top: 3rem;
    font-size: 0.9rem;
    font-family: 'Orbitron', sans-serif;
    letter-spacing: 1px;
}


.menu-item:hover {
    transform: scale(1.05);
}


#profile-pic {
    position: absolute;
    top: 20px;
    right: 20px;
    width: 70px;
    height: 70px;
    border-radius: 50%;
    border: 2px solid #00ff55;
    box-shadow: 0px 0px 10px rgba(11, 192, 120, 0.5);
}


</style>
</head>
<body>

<video autoplay muted loop id="background-video">
    <source src="https://cdn.pixabay.com/video/2023/04/15/159052-818026310_large.mp4" type="video/mp4">
</video>

<header>
    <h1 STYLE="font-family:Verdana, Geneva, Tahoma, sans-serif;">SR Digital Lab</h1>
    <p>Your Gateway to Futuristic Tech</p>
    <nav>
        <a href="#smartphones">Smartphones</a>
        <a href="#laptops">Laptops</a>
        <a href="#wearables">Wearables</a>
        <a href="#gaming">Gaming</a>
    </nav>
  <a href="SRloginpage.html"> <img src="https://scontent.faip1-1.fna.fbcdn.net/v/t39.30808-1/449833309_1913411629101496_601315898549013672_n.jpg?stp=dst-jpg_s200x200&_nc_cat=103&ccb=1-7&_nc_sid=0ecb9b&_nc_ohc=AhEvvHQKZ8sQ7kNvgE-DYET&_nc_zt=24&_nc_ht=scontent.faip1-1.fna&_nc_gid=A53TQMdDVX0yBZBouA-HmIM&oh=00_AYAKQrUkRT4fIM27ssSF7DLWyZTwXq-QYf5CZe0270ILkw&oe=67282945" alt="Profile Picture" id="profile-pic"></a> 

</header>

<section class="menu-section" id="smartphones">
    <h2>Smartphones</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcQddUjRGGUw0sw7NPyxT56XX7pOtns1mPK_jNBoNh5Cdf0bhcwIayOTX9Q0WBUGtQ9zMpeNf-QSJgPJbK5kTjTyCTVBFhzRMum47xUq0_3fenG0q8NFJCqM&usqp=CAE" alt="smartphone" onclick="showModal('iPhone 16', '4K 120 fps Dolby Vision, highest resolution.')">
            <h3>iphone 16</h3>
            <p> Takes video capture to a whole new level with 4K 120 fps Dolby Vision, our highest resolution .</p>
            <p class="price" style="color: #19dd15; ">Rs 99,999</p>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcRVqccKDcx_oEeZoBLLDlmJmd8Avv1P4jcu5H_YNwYPNw-mqD17x8_UGUOEDxo1awWfYD-LLuMpBrpWaI7lzWghzIq3IO-uomqIPOchzsT_D2CIVL37JlqR&usqp=CAE" alt="smartphone">
            <h3>UlefoneArmor 25T Pro 5G Rugged </h3>
            <p>6.7" OLED display with dynamic refresh rate.</p>
            <p class="price" style="color: #19dd15;">Rs 70,000</p>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
          <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRzIM0zFkBbKizU0fKQHGJZ4njSk7w9EOUNovTpojp9DYO9QDGrWt2ovC5PoRvjqXP7dZegm4VZFno30I8RCBIPZHylwvfdlm-d1mLH48t0kv3cj8DsriI89Q&usqp=CAE" alt="smartphone">
          <h3>The T2 Pro 5g</h3>
          <p>A 3d Curved Amoled Screen Providing A Bright Display With A Peak Brightness Of 1300 Nits. Improve Your Performance With The Mediatek Dimensity.</p>
          <p class="price" style="color: #19dd15;">Rs 24,999</p>
          <button>Add to Cart</button>
      </div>
      <div class="menu-item">
        <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcSUlB2HtqJkUwaLap3T3EQkFl8w7n9e1h0tvGwoZwNL6UaunQWDN42kP5Drzw-_Rg3kVy9Lusil4LItZkAsDmk61aHOlUYx8zC6O2feO3fZ6X4mKkG8qm7_&usqp=CAE" alt="smartphone">
        <h3>Samsung galaxy s24 ultra</h3>
        <p>a powerhouse in the world of smartphones. This cutting-edge device boasts a stunning titanium black exterio.</p>
        <p class="price" style="color: #19dd15;">Rs 131,000</p>
        <button>Add to Cart</button>
    </div>
    <div class="menu-item">
      <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcR3FD8Y88NqF73kDxOrXmGGj-WEgbP9sRVJFM1b8tVk4vq_Se_7JSTtTiDINiHbmeD7kSvqknvKj9RqyzkFnhM3GPMBmDH5VCNHc0Q1Urb6DeT4L8swbwt-_Q&usqp=CAE" alt="smartphone">
      <h3>Motrola G13</h3>
      <p>Time To Stand Out Of The Crowd With A Super Premium And Ultra-modern Design Phone.</p>
      <p class="price" style="color: #19dd15;">Rs 10,999</p>
      <button>Add to Cart</button>
  </div>
  
  
    </div>
</section>


<section class="menu-section" id="smartphones">
  <h2>Laptops</h2>
  <div class="menu-grid">
      <div class="menu-item">
          <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTJ_CB7ozYUQhITJAlc1iKPL_CS1JYGtCvj0aQrz25hYv2yIeT2Vvl8HjxVRQIEloUC4qcLMZ-p96NeMAtQkwMSoj-R9Sm0626GFERdoSJ6Zlmn2TxFcb1kvA&usqp=CAE" alt="smartphone">
          <h3>Lenevo idealpad3</h3>
          <p>Cloud Grey Features: Processor: AMD Ryzen 5 5500U | Speed: 2.1GHz.</p>
          <p class="price" style="color: #19dd15;">Rs 39,999</p>
          <button>Add to Cart</button>
      </div>
      <div class="menu-item">
          <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcR9tHMkhaJJANvuSxrE2mVRosvvQZuhwDjfJv79OjWXX8us6Vdl43bDoi_V-nbh9saboon3A8ZU7t0H-W4b0fva6fHaxmgPHtdPiAahyXYmg1SDnpJF8Uvfzw&usqp=CAE" alt="smartphone">
          <h3> Samsung Galaxy Book4</h3>
          <p>Blast through heavy workloads and multitask seamlessly with the supercharged Intel Core Ultra processor</p>
          <p class="price" style="color: #19dd15;">Rs 70,000</p>
          <button>Add to Cart</button>
      </div>
      <div class="menu-item">
        <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcQMqA9yP8uZGxX2SEtjeRxdmQ4_WnHIebeKHbaIh2kMjg7t-uZLSaW6HvoVvep0myUqV4ZKNFTMPk26XzQ3k0bFuLEe-oUhI0Mcb1FH8hmojQn9R4CjM5LV&usqp=CAE" alt="smartphone">
        <h3>AMD Ryzen 7</h3>
        <p>7435HS Mobile Processor 3.1GHz (20MB Cache, up to 4.5 GHz, 8 cores, 16 Threads)</p>
        <p class="price" style="color: #19dd15;">Rs 68,999</p>
        <button>Add to Cart</button>
    </div>
    <div class="menu-item">
      <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcQGLI26ZJyR2kGP2g8yX38ejB2n2XshKeQuVUbZ0nav64Gz6lhAwJog3hT4WUTwX0mf38fxkDF6rtdB0Q6SXPbmMt7jv9mSUaN8cjD6VVekuTlpNsT-pzZFjQ&usqp=CAE" alt="smartphone">
      <h3> Msi Thin 15</h3>
      <p>Amd Ryzen 7035hs Series Processor, Featuring Up To 8 Cores And 16 Threads. </p>
      <p class="price" style="color: #19dd15;">Rs 65,000</p>
      <button>Add to Cart</button>
  </div>
  <div class="menu-item">
    <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcSuSqT_AwFu-KUudB_slGyl1EDl5o9tm380Nr2cjPcmA2WvQCuDLZu4ozuV1sJzXsHEzTVDuXyei_VSwGMqp-Zs2Kpo30JsqiIgN3UwfDc3F0u1xuCW4Not&usqp=CAE" alt="smartphone">
    <h3>HP victus ryzon5</h3>
    <p>Windows 11 Home operating system for user-friendly performance 8GB RAM and 512 GB SSD ROM.</p>
    <p class="price" style="color: #19dd15;">Rs 50,649</p>
    <button>Add to Cart</button>
</div>


  </div>
</section>

<section class="menu-section" id="smartphones">
  <h2>Wearables</h2>
  <div class="menu-grid">
      <div class="menu-item">
          <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTa7_ZwM5M5otYIFIzsDFJP073Pm60lXUw8jIYYvcnmsH5D-k7gBkmdSUsppFutC6R-JA5ZJmTQbRO-pvEp-AnH-rHhzRXc5pXZxRi08O4A3mxCPhzjmkF3&usqp=CAE" alt="smartphone">
          <h3>Boasting a vibrant 1.46" </h3>
          <p>" Always On AMOLED display that delivers crystal-clear visuals NoiseFit Endeavour is equipped with SoS Technology.</p>
          <p class="price" style="color: #19dd15;">Rs 3,999</p>
          <button>Add to Cart</button>
      </div>
      <div class="menu-item">
          <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcRtJsV6feiehIm5GkVFgpPkgYwVRL4RKs-MyC5KO_LKQXrqJSLzZ45Qv3NYYR-nPyLMBRi5yL6r2YEiCPJPzkxttAgqljxUs6SJXFTRuVhg2fz3rvBy7vBx&usqp=CAE" alt="smartphone">
          <h3>Touch Screen Earphones Sport Smartwatch sr19</h3>
          <p> With HD large screen. restore nature's pure color. clear and vivid. See more sports information, and call alerts,</p>
          <p class="price" style="color: #19dd15;">Rs 9,972</p>
          <button>Add to Cart</button>
      </div>
      <div class="menu-item">
        <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcS94N_czuMZQjRf3JQixEzWoqsNMON3XiUu4cucGMyACjcyX5qd8gNom2oT7zd6KprPXri5D7dJgkLz8Dem8t-wy4uJ-8XCyqh6aqwDMUzUP0fYfp3zsirJ&usqp=CAE" alt="smartphone">
        <h3>53 Sport Earphone</h3>
        <p>Bluetooth 5.3, a leap in connection and pairing: Compared with BT5.2.</p>
        <p class="price" style="color: #19dd15;">Rs 2,499</p>
        <button >Add to Cart</button>
    </div>
    <div class="menu-item">
      <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcTYGEo9GYCsaRpcR7XgZccIjW3fc8-vnOM5ZSQ40c9LNW0aa79cK2HVDk3v85YkreF6xCGkrHAOajldM7zpXLnBMQ1WOJ5tiJi2caK40tWe&usqp=CAE" alt="smartphone">
      <h3>Zebra WT6400 Wearable Mobile Computer</h3>
      <p>Wearable Mobile Computer has been designed from the ground up to be worn on the wrist. The WT6400 features a touchscreen.</p>
      <p class="price" style="color: #19dd15;">279,455</p>
      <button>Add to Cart</button>
  </div>
  <div class="menu-item">
    <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRJ2MDwUjHSPjJJ7zeX6_Ahjem5EAsEMZmOr4iglJhBC5rbyY1EUNKYt6ylVuYxltPC1Xp8qxp7lEPuxUuSnGhW7NOYkos9AXrn3PZbeLrQC8rIo0ZfPhdZ&usqp=CAE" alt="smartphone">
    <h3>2024 Smart Ring</h3>
    <p>Express yourself through fashion while staying informed about your vital signs with the New 2024 Smart Ring - a cutting-edge accessory that merges modern trends with .</p>
    <p class="price" style="color: #19dd15;">Rs 4,599</p>
    <button >Add to Cart</button>
</div>

  </div>
</section>

<section class="menu-section" id="smartphones">
    <h2>Gaming</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcSrQeEO3v-1Elqf-kGeH7htcZmjNSPwwq10spHRE_QlsYFNdFYBUNbJ72pxRLVP7Z4w7ucV-zaShzhbRiBxPqRsaV4GvE0OonEDuO4O2ykmbpoGDT0GDEo5EA&usqp=CAE" alt="smartphone">
            <h3>PUBG MOBILE GAME CONVERTER </h3>
            <p>Bluetooth 5.0 connection, non emulator, high-speed shooting without delay, support for Android, for IOS system.</p>
            <p class="price" style="color: #19dd15;">Rs 1,999</p>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcRkouB23-4vo0Wg0K1Gom92mF6uBobO3j_ejFqqjj0OBpa-9Or2wvzzdtHhhRuLpKhZqo-rMUgebC4TMVqtigI6mc4SFTV3MAEoqnI9zZBKxKnJ2LWiHB4m&usqp=CAE" alt="smartphone">
            <h3>esportic 4K Ultra HD TV Video Game</h3>
            <p>Massive Childhood Classic Games】Preloaded With 9 Emulators(PS-1/ATARI/MAME/SFC/FC/GBA/GB/GBC/MD)And Equipped With A 64GB TF Card</p>
            <p class="price" style="color: #19dd15;">Rs 2,569</p>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
          <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcSa_9hcDc2EEmYgWrojVcbMR86z2fO_9FM9X3Jx0kEwEl9445qF_srWmL5ZiQk0uaczV80k_t00kQtWrkdQ5PpCgwi156CxuzJnE17oqZNfrmKMbi2etJkz&usqp=CAE" alt="smartphone">
          <h3>NextTech Plug & Play Video TV Game</h3>
          <p>Immerse yourself in a nostalgic journey with over 20,000 retro classic games pre-installed on this console. Relive the cherished memories of your youth with a single device.</p>
          <p class="price" style="color: #19dd15;">Rs 2,099</p>
          <button >Add to Cart</button>
      </div>
      <div class="menu-item">
        <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcQROluqoJrC1VJSKb3fBGnxe-HDC8Bv_y4xsgY77S9cIV0DUs1pB6q8zO_Sea_gPrkUwgU9noq_9dminMD1wcpeERNhQF3_5Q&usqp=CAE" alt="smartphone">
        <h3>Wireless Gaming Keyboard and Mouse Rainbow</h3>
        <p>2.4g Wireless Enables The Keyboard To Achieve Long-range Wireless Control. Plug & Play, Keyboard And Mouse Share An Intelligent Nano Receiver, </p>
        <p class="price" style="color: #19dd15;">Rs 11,299</p><br>
        <button>Add to Cart</button>
    </div>
    <div class="menu-item">
      <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcR63z9aitDxLBYh_ts7qG-EW05V_uVRPgxJWCdd9M5YVHlCgf0S9ScYb0ogcsMKp_gsR2YDtme4pdH9z_EZ8yFZy9fwvtMmGW7supOMNoEPsYu6v0JA9p8F&usqp=CAE" alt="smartphone">
      <h3>Tech King X6</h3>
      <p>X6 4.3 inch 8GB Handheld Game Built-in 1500 Game Support 10 Emulators</p><br><br><br><br>
      <p class="price" style="color: #19dd15;">Rs 999</p>
      <button >Add to Cart</button>
  </div>
  
    </div>
  </section>
<footer>
    <p>SR Digital Lab © 2024 | Redefining the Digital World | SHOEB RAZA</p>
</footer>


</body>
</html>