<template>
    <div class="contact">
            <br/>
        <div id="cont">
            <h1> Contact Us</h1>
            <img src="https://ppihc.org/wp-content/uploads/2015/09/inline-title.jpg" alt="deco break"/>
            <br/>
            <iframe width="600" height="450" style="border:0" loading="lazy" allowfullscreen src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJLZ12AlBbE4cR8bLuFdj70V8&key=AIzaSyCnzWZuKfAzAXehmGcjwBQcciP8slDHFQM"></iframe>
            <br/>
            <div id="contact-container">
                <div class="contact-info">
                    <div>
                        <div>
                            <h2>Office Address</h2>
                            <aside>
                                <img src="../assets/Icons/map.svg" alt="map icon"/>   
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
                                <img src="../assets/Icons/phone.svg" alt="phone icon"/>   
                            </aside>
                        <p>Main: 719.685.4400</p>
                    </div>
                    <br />
                    <div>
                        <h2>General Information</h2>
                            <aside>
                                <img src="../assets/Icons/email.svg" alt="email icon"/>   
                            </aside>
                        <p>Information@pphic.org</p>
                        <br />
                        <h2>Staff Email</h2>
                        <p> zach.imerzel@gmail.com</p>
                    </div>
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
    padding-top: 20vh;
    background-color: rgb(255, 255, 255);

}

.contact h1{
    color: rgb(0, 0, 0);
}

#contact-container{
    padding-right:7vw;
    padding-left: 7vw;
    margin-bottom: 50px;
}

.contact-info{
background-color: #2c3e50;
padding: 40px;
background-image: url("https://ppihc.org/wp-content/uploads/bk-10.png?id=4214");
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
    margin-right: 400px;
}
aside img{
    width:40px;
}


@media only screen and (max-width: 900px) {
.contact{
    padding-right: 4vw;
    padding-left: 4vw
}

.contact-info p{
    font-size: 12px;
}

aside{
margin-right: 10px;
padding-bottom: 10px
}

aside img{
    width:30px;
}

}

</style>