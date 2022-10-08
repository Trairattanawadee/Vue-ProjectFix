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

                    
                <div class="info-container">

                    <h1 class="heading" > about <span>me</span> </h1>

                    <div class="box-container" style=" margin-left: 20rem;">

                        <div class="box">
                            <p> <span>name : </span> Trairattanawadee Foythong </p>
                            <p> <span>age : </span> 19 </p>
                            <p> <span>email : </span> trairattanawade.foy@bumail.net </p>
                            <p> <span>address : </span> Sisaket, Thailand 33110 </p>
                            <p> <span>freelance : </span> available </p>
                            <p> <span>Commission Avatar : </span> Close (Full) </p>
                            <p> <span>skill : </span> All Photoshop &amp; Voice actor </p>
                            <p> <span>language : </span> thai </p>
                        </div>

                    </div>

                </div>

                    <section class="education">

                        <h1 class="heading"> <span>my</span> Education </h1>

                            <div class="box-container">

                                <div class="box">
                                    <i class="fas fa-briefcase"></i>
                                    <span>2007 - 2015</span>
                                    <h3>Anubandumrongrachanuson school</h3>
                                    <p>1099 Moo 5, Damrong Sathit Road, Nam Om, Kantharalak, Sisaket 33110. </p>
                                    <p>Tel : 045-661467 Email : info@adrs.ac.th</p>
                                </div>

                                <div class="box">
                                    <i class="fas fa-briefcase"></i>
                                    <span>2015 - 2018</span>
                                    <h3>kantharalak wittaya school</h3>
                                    <p>443 Moo 5, Damrong Sathit Road, Nam Om, Kantharalak, Sisaket 33110.</p>
                                    <p> Tel : 045-661420 </p>
                                </div>

                                <div class="box">
                                    <i class="fas fa-briefcase"></i>
                                    <span>2018 - 2020</span>
                                    <h3>St.Mary’s  Business  Administration Technological College (MBAC)</h3>
                                    <p>888 Dejudom  Rd. Soi 4,  Muang Nakhonratchasima,  Nakhonratchasima 30000</p>
                                    <p> Tel : 044 - 205316  Fax : 044 - 274778 Email:web.mbac@gmail.com </p>
                                </div>

                            </div>                           
                    </section>

                    <section class="skills">

                        <h1 class="heading"> <span>my</span> skills </h1>

                            <div class="box-container">
                                <div class="box">
                                    <img src="src/icon-1.png">
                                    <h3>Photoshop</h3>
                                </div>
                                <div class="box">
                                    <img src="src/icon-2.png">
                                    <h3>Animate</h3>
                                </div>
                                <div class="box">
                                    <img src="src/icon-4.png">
                                    <h3>Ligtroom</h3>
                                </div>
                                <div class="box">
                                    <img src="src/icon-3.png">
                                    <h3>Unity</h3>
                                </div>
                                <div class="box">
                                    <img src="src/icon-5.png">
                                    <h3>MAYA</h3>
                                </div>
                                <div class="box">
                                    <img src="src/icon-6.png">
                                    <h3>Microsoft Office</h3>
                                </div>
                            </div>
                    </section>
            </div>
        </b-container>
    </div>

</template>