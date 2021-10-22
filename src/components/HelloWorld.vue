<template>
  <div class="hello">
    <img class="viper" alt="Vue logo" src="../assets/viper.jpg">
    <h1>{{ msg }}</h1>
    <img src="https://ppihc.org/wp-content/uploads/2015/09/inline-title.jpg" alt="spacer" />
    <div class="history">
      <p id="main">
        In 1948, the City of Colorado Springs became responsible for maintaining the Pikes Peak Highway through a special-use permit issued by the U.S. 
        National Forest Service, the roads previous caretaker. 
        The road was composed of an entirely dirt surface at the time that the City of Colorado Springs became its caretaker and in the 1950s the first 6 miles of the highway were paved, 
        up to about a mile below the Start Line for the Pikes Peak International Hill Climb. 
        In August 1998, the Pikes Peak chapter of the Sierra Club, the nation’s largest environmental organization, claimed that gravel pollution caused by the 13 unpaved miles of the Pikes Peak Highway violated the Clean Water Act and filed a lawsuit against the City of Colorado Springs and National Forest Service. 
        The City of Colorado Springs did not deny that gravel from the Pikes Peak Highway migrated from the Highway or that streams, wetlands, and reservoirs were impacted by gravity and weather moving the gravel down the mountain. 
      </p>
      <aside>
        <img loading="lazy" src="https://ppihc.org/wp-content/uploads/Pavement-History-Infographic-Copy-768x768.png" />
      </aside>
      <p>
        The City did however argue that the Highway could not be established as a “point source” under the Clean Water Act and that the Sierra Club did not have the legal right to the relief sought. The United States filed a brief in response to the City’s motion arguing that the Highway is a point source and would be 
        required to acquire the appropriate discharge permits and certification. The Sierra Club and City of Colorado Springs reached a settlement in February 1999 and the State of Colorado ordered the City of Colorado Springs to comply with the conditions contained in a Section 401 permit issued by the Water Quality Control Division of the Colorado Department of Public Health and the Environment.
        This permit stated that the City had to implement a plan to correct the erosion and sediment problems caused by the highway before 2012. In addition to the permitting requirements which were projected to cast $14-20 million, the suit called for the City to contribute $300,000 to fund cleanup and remediation projects in 
        addition to $100,000 to assist with the Sierra Club’s legal fees. Although the National Forest Service was a co-defendant in the lawsuit, they were not a party in the settlement because the City of Colorado Springs was/is the party responsible for maintaining the Highway. The City found no other solution to meet the permitting requirements other than paving the remaining 13 miles of dirt that 
        lead to the Summit of Pikes Peak – Americas Mountain. The first mile of paving was installed in 2002 and the project was completed weeks after the 89th Running of the Pikes Peak International Hill Climb in 2011. <strong>***The PPIHC rents the road from the City of Colorado Springs to organize the race each year and was not involved in the decision to pave the top 13 miles of the Pikes Peak Highway.
        The PPIHC places great value in the rich tradition and history that comes with being the second oldest motorsports event in the Western Hemisphere and was not in favor of the paving of the dirt racing surface that had been used since the first race in 1916.***</strong>
      </p>
    </div>
    <br />
    <br />
    <br />
    <blockquote class="blockquote">
      <div class="container">
        <div class="row align-items-start">
          <div class="col">
            <img src="../assets/Icons/finish.svg" width="80px"/>
          </div>
          <div class="col">
            <img src="../assets/Icons/road.svg" width="80px"/>
          </div>
          <div class="col">
            <img src="../assets/Icons/arrow.svg" width="80px"/>
          </div>
          <div class="col">
            <img src="../assets/Icons/checkered-flag.svg" width="80px"/>
          </div>
        </div>
        <div class="row align-items-center">
          <div class="col">
            <h1>1918</h1>
            <span>-</span>
          </div>
          <div class="col">
            <h1>12.42</h1>
            <span>-</span>
          </div>
          <div class="col">
            <h1>156</h1>
            <span>-</span>
          </div>
            <div class="col">
            <h1>14,115</h1>
            <span>-</span>
          </div>
        </div>
        <div class="row align-items-end">
          <div class="col">
            <p>First Race</p>
          </div>
          <div class="col">
            <p>Miles</p>
          </div>
          <div class="col">
            <p>Corners</p>
          </div>
          <div class="col">
            <p>Finish Line(ft)</p>
          </div>
        </div>
      </div>
    </blockquote>
    <div class="thanks">
      <h1>THANK YOU TO ALL OUR RACE SPONSORS</h1>
      <img width="70" height="5" src="https://ppihc.org/wp-content/uploads/2015/09/under-line-pink.png" class="attachment-full size-full" alt="" loading="lazy">
      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://ppihc.org/wp-content/uploads/2017/08/gran-turismo-logo-2.png"  alt="grand turismo" height="110px" width="139px">
          </div>
          <div class="carousel-item">
            <img src="https://ppihc.org/wp-content/uploads/Visit-Colorado-Springs-Horizontal-Resized-for-Web-140x110.png" class="d-block w-100" alt="..." height="110px" width="140px">
          </div>
          <div class="carousel-item">
            <!-- <img src="..." class="d-block w-100" alt="..."> -->
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
width: 100%;

}

.hello h1{
padding-top: 30px;
font-family: 'Raleway', sans-serif;
font-weight: 200;
}

p {
padding: 2vw;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.viper {
object-fit: cover;
display: flex;
flex-wrap: wrap;
justify-content: center;
width: 100%;
z-index: 0;
padding-top: 100px;
}

.history{
padding: 20px;
}


.history p {
padding: 0px;
text-align: left;
}

.history aside img{
max-height: 600px;
float: right;
padding: 20px;
align-content: center;
}

#title{
padding: 40px
}

#text {
font-size: x-large;
font-weight: bold;
}

.blockquote{
  display: flex;
  flex-wrap: wrap;
}

.col img{
  width: 50px;
}

.col h1{
  font-size: 5vw;
  font-weight:100;
  font-weight: 100;
  font-family: 'Roboto', sans-serif;
}

.col span{
  font-size: 8vw;
  color: grey;
}

.col p{
  font-size: 2.25vw;
  margin-top: -10px;
}

.thanks{
    padding-top: 40px !important;
    padding-bottom: 40px !important;
    background-image: url(https://ppihc.org/wp-content/uploads/bk-10.png?id=4214) !important;
    background-position: center !important;
    background-repeat: no-repeat !important;
    background-size: cover !important;
}

.thanks h1{
  color: white;
}

aside img{
  width: 60%;
  object-fit: cover;
}

@media only screen and (min-width: 1020px) {
  aside img{
    width: 60%;
  }
  .history{
    padding-right: 15vw;
    padding-left: 15vw;
  }
  .col h1{
    font-size: 3vw;
  }
  
  .col span{
    font-size: 4vw;
  }

  .col p{
    font-size: 1.25vw;
  }

}
@media only screen and (min-width:1490px){
  aside img{
    width: 40%;
  }
}
</style>
