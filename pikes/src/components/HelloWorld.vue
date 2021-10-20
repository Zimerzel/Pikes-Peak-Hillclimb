<template>
  <div class="hello">
    <img class="viper" alt="Vue logo" src="../assets/viper.jpg">
    <h1>{{ msg }}</h1>
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
        lead to the Summit of Pikes Peak – Americas Mountain. The first mile of paving was installed in 2002 and the project was completed weeks after the 89th Running of the Pikes Peak International Hill Climb in 2011. ***The PPIHC rents the road from the City of Colorado Springs to organize the race each year and was not involved in the decision to pave the top 13 miles of the Pikes Peak Highway.
        The PPIHC places great value in the rich tradition and history that comes with being the second oldest motorsports event in the Western Hemisphere and was not in favor of the paving of the dirt racing surface that had been used since the first race in 1916.***
      </p>
    </div>
    <br />
    <br />
    <br />
    <div>
      <div id="cards">
        <b-card img-src="https://img.redbull.com/images/c_fill,g_auto,w_860,h_1229/q_auto,f_auto/redbullcom/2013/07/01/1331598901564_23/peugeot-208-t16-pikes-peak-loeb" img-alt="Card image" img-left class="mb-3">
          <b-card-title id="title">
              <img src="../assets/Icons/finish.svg" width="80px"/>
          </b-card-title>
          <b-card-subtitle id="text">
            1918
          </b-card-subtitle>
          <b-card-text id="text">
            First Race
          </b-card-text>
          <b-card-title id="title">
              <img src="../assets/Icons/road.svg" width="80px"/>
          </b-card-title>
          <b-card-subtitle id="text">
            12.42
          </b-card-subtitle>
          <b-card-text id="text">
            Miles
          </b-card-text>
        </b-card>

        <b-card img-src="https://bloximages.newyork1.vip.townnews.com/gazette.com/content/tncms/assets/v3/editorial/e/9e/e9eb8bfa-5c84-11e9-ac7e-47ceeec68d58/5caf835d058b0.image.jpg?resize=1200%2C680" img-alt="Card image" img-right class="mb-3" >
          <b-card-title id="title">
              <img src="../assets/Icons/arrow.svg" width="80px"/>
          </b-card-title>
          <b-card-subtitle id="text">
            156
          </b-card-subtitle>
          <b-card-text id="text">
            Corners
          </b-card-text>
          <b-card-title id="title">
              <img src="../assets/Icons/checkered-flag.svg" width="80px"/>
          </b-card-title>
          <b-card-subtitle id="text">
            14,115
          </b-card-subtitle>
          <b-card-text id="text">
            Finish Line Elevation (ft)
          </b-card-text>
        </b-card>
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

.mb-3{
background-color: rgb(58, 60, 66);
color: rgb(0, 0, 0);
width:100%;
}

.mt4 {
  width:100%;
}

.mt-4 img{
max-width: 450px;
object-fit: cover;

}

#cards{
display: flex;
flex-wrap: wrap;
}

.card-img-left, .card-img-right{
  display: flex;
  flex-wrap: wrap;
  width: 60%;
  object-fit: cover;
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
}
@media only screen and (min-width:1490px){
  aside img{
    width: 40%;
  }
}
</style>
