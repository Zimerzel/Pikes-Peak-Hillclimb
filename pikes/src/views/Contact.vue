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
                <img src="" />
                <h2>Office Adress</h2>
                <p>1631 Mesa Avenue, Suite E</p>
                <br />
                <p>Colorado Springs, CO 80906</p>
                <br />
                <img src="" />
                <h2>Phone Number</h2>
                <p>Main: 719.685.4400</p>
                <br />
                <img src="" />
                <h2>General Information</h2>
                <p>Information@pphic.org</p>
                <br />
                <img src="" />
                <h2>Staff Email</h2>
                <p> zach.imerzel@gmail.com</p>
            </div>
        </div>
    </div>
</template>
<style scoped>
iframe{
    width: 85%;
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
padding: 20px;
}

.contact-info h2{
    padding: 10px;
    color: white;
}

.contact-info p{
    display: inline;
    padding: 10px;
    color: white;
}
</style>