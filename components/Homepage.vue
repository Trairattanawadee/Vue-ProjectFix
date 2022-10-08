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

                <div>
                    <b-carousel 
                        id="carousel-fade"
                        style="text-shadow: 0px 0px 2px #000; margin: 4rem;"
                        fade
                        indicators
                        img-width="1024"
                        img-height="480"
                        >
                        <b-carousel-slide
                        img-src="src\S1.png"
                        ></b-carousel-slide>
                        <b-carousel-slide
                        img-src="src\S2.png"
                        ></b-carousel-slide>
                        <b-carousel-slide
                        img-src="src\S3.png"
                        ></b-carousel-slide>
                    </b-carousel>
                </div>

                <div class="p-4 p-md-5 mb-4 rounded text-bg-dark">
                    <div class="float-center" style="text-align: center; padding: 0.5rem; margin: 1.5rem; border: 5px solid #83cffc;">

                        <h1 class="heading"> Wellcome <span>!!!</span> </h1>
                        <h3> I'm <span>Trairattanawadee Foythong</span> </h3>

                        <p>Freelance For Graphics, Photography, Photoshop And Design And Create Avatars In VrChat,</p>
                        <p>Is An Admin Of Cumcum's Avatar Page With Many Works To View,</p> 
                        <p> Currently Studying In The Faculty Of Engineering Multimedia And Entertainment Bangkok University.</p> 
                    </div>
                </div>
            </div>
        </b-container>
    </div>

</template>