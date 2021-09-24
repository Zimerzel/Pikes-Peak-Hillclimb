<template>
  <div class="hello">
    <img alt="Vue logo" src="../assets/viper.jpg">
    <h1>{{ msg }}</h1>
    <div class="history">
      <p>
        In 1948, the City of Colorado Springs became responsible for maintaining the Pikes Peak Highway [1] through a special-use permit issued by the U.S. 
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
        required to acquire the appropriate discharge permits and certification. [2] The Sierra Club and City of Colorado Springs reached a settlement in February 1999 and the State of Colorado ordered the City of Colorado Springs to comply with the conditions contained in a Section 401 permit issued by the Water Quality Control Division of the Colorado Department of Public Health and the Environment.
        [3] This permit stated that the City had to implement a plan to correct the erosion and sediment problems caused by the highway before 2012. [4] In addition to the permitting requirements which were projected to cast $14-20 million, the suit called for the City to contribute $300,000 to fund cleanup and remediation projects in 
        addition to $100,000 to assist with the Sierra Club’s legal fees. Although the National Forest Service was a co-defendant in the lawsuit, they were not a party in the settlement because the City of Colorado Springs was/is the party responsible for maintaining the Highway. [5] The City found no other solution to meet the permitting requirements other than paving the remaining 13 miles of dirt that 
        lead to the Summit of Pikes Peak – Americas Mountain. The first mile of paving was installed in 2002 and the project was completed weeks after the 89th Running of the Pikes Peak International Hill Climb in 2011. ***The PPIHC rents the road from the City of Colorado Springs to organize the race each year and was not involved in the decision to pave the top 13 miles of the Pikes Peak Highway.
        The PPIHC places great value in the rich tradition and history that comes with being the second oldest motorsports event in the Western Hemisphere and was not in favor of the paving of the dirt racing surface that had been used since the first race in 1916. [6]***
      </p>
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

img {
object-fit: cover;
display: flex;
flex-wrap: wrap;
justify-content: center;
width: 100%;
}

.history{
padding: 20px;
}

.history aside img{
/* height: 600px;
float: right;
padding: 20px; */

}
</style>
