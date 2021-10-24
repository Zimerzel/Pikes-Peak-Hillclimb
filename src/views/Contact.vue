<template>
    <div class="contact">
        <Contact />
                <br/>
        <h1> Contact Us</h1>
        <img src="https://ppihc.org/wp-content/uploads/2015/09/inline-title.jpg" />
        <br/>
        <iframe width="600" height="450" style="border:0" loading="lazy" allowfullscreen src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJLZ12AlBbE4cR8bLuFdj70V8&key=AIzaSyCnzWZuKfAzAXehmGcjwBQcciP8slDHFQM"></iframe>
        <br/>
        <div id="contact-container">
            <div class="contact-info">
                <div>
                    <div>
                        <h2>Office Adress</h2>
                        <aside>
                            <img src="../assets/Icons/map.svg" />   
                        </aside>
                        <p>1631 Mesa Avenue, Suite E</p>
                        <br />
                        <p>Colorado Springs, CO 80906</p>
                    </div>
                </div>
                <br />
                <div>
                    <h2>Phone Number</h2>
                        <aside>
                            <img src="../assets/Icons/phone.svg" />   
                        </aside>
                    <p>Main: 719.685.4400</p>
                </div>
                <br />
                <div>
                    <h2>General Information</h2>
                        <aside>
                            <img src="../assets/Icons/email.svg" />   
                        </aside>
                    <p>Information@pphic.org</p>
                    <br />
                    <h2>Staff Email</h2>
                    <p> zach.imerzel@gmail.com</p>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
iframe{
    width: 85%;
    margin-top: 30px;
}

.contact {
    padding-top: 15vh;
    background-color: rgb(255, 255, 255);
}

.contact h1{
    color: rgb(0, 0, 0);
}

#contact-container{
    padding-right:7vw;
    padding-left: 7vw;
}

.contact-info{
background-color: #2c3e50;
padding: 40px;
}

.contact-info h2{
    padding: 20px;
    color: white;
}

.contact-info p{
    display: inline;
    padding: 20px;
    color: white;
}

aside{
    display: flex;
    flex-wrap: wrap;
    position: relative;
    float: left;
    width:80px;

}
aside img{
    position: absolute;
    width:40px;
    top:-10px;
    left: 20vw;
}

@media only screen and (max-width:1120px){
  aside img{
    margin-left: -15vw;
  }
}

@media only screen and (min-width:1124px){
  aside img{
    margin-left: -2vw;
  }
}
</style>