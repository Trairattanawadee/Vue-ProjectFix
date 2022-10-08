<template>
    <div>
        <b-container> 
            <div style="box-shadow: 0px 0px 5px 2px #c0d1db; margin-top: 7rem; min-height: max-content; background-color: #F8F8FF;" >
                <b-row style="padding: 2rem 4rem;">
                    <b-col cols="4">
                        <b-img src="src\logo.png" fluid alt="Responsive image"></b-img>
                    </b-col>

                    <b-col cols="8">
                        <b-nav class="float-right" style="padding: 0.5rem; margin-top: 2rem; border-top: 2.5px solid #83cffc;border-bottom: 2.5px solid #83cffc">
                            <b-nav-item><NuxtLink to="/"> Home </NuxtLink></b-nav-item>
                            <b-nav-item><NuxtLink to="/about"> About me </NuxtLink></b-nav-item>
                            <b-nav-item><NuxtLink to="/work"> My work </NuxtLink></b-nav-item>
                            <b-nav-item><NuxtLink to="/contact"> Contact </NuxtLink></b-nav-item>
                        </b-nav>
                    </b-col>
                </b-row> 
                
                <section class="contact">

                    <div>

                        <div class="info-container">                           

                            <div>
                                <div class="float-center" style="text-align: center; padding: 0.5rem; margin: 1.5rem; border: 5px solid #83cffc;">
 
                                    <h1 class="heading"> contact <span>me</span> </h1>
                                    <h3>รับทำ Avatar Vrchat สอบถามข้อมูล INBOX นะคะ </h3>

                                    <p> address :Sisaket, Thailand 33110</p>
                                    <p> email :cumcumsavatar@gmail.com</p> 
                                    <p> number : +66635139960</p> 
                                </div>

                                <div class="share">
                                    <a href="https://www.facebook.com/people/Trairattanawadee-Foythong/100004524570292/" class="fab fa-facebook-f"></a>
                                    <a href="https://twitter.com/Lucky_Smile27" class="fab fa-twitter"></a>
                                    <a href="https://www.instagram.com/zerial_ls/" class="fab fa-instagram"></a>
                                </div>
                            </div>
                    
                        </div>
                        <div class="row" style="text-align: center; padding: 0.5rem; margin: 1.5rem;">
                            <form>

                                <div class="inputBox" >
                                    <input type="text" placeholder="your name">
                                    <input type="number" placeholder="your number">
                                </div>

                                <div class="inputBox">
                                    <input type="email" placeholder="your email">
                                    <input type="text" placeholder="your subject">
                                </div>

                                <textarea name="" placeholder="your message" id="" cols="30" rows="10"></textarea>

                                <input type="submit" value="send message" class="btn">

                            </form>
                        </div>
                    </div>

                </section>

            </div>
        </b-container>
    </div>

</template>