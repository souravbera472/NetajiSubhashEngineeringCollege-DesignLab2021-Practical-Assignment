<template>
  <div>
    <br />
    <v-row class="row1">
      <h1>ABC High School</h1>
      <v-spacer></v-spacer>
       <v-btn class="text">
         courses
       </v-btn>

        <v-icon class="btn"
        large>mdi-format-list-bulleted</v-icon>
    </v-row>
    <img class="img" width="100%" :src="'image/1st.PNG'" alt />
     <img class="img2" width="100%" :src="'image/2nd.PNG'" alt />
     <img class="img2" width="100%" :src="'image/3rd.PNG'" alt />
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>
<style scoped>
.row1 {
  background-color: rgb(24, 24, 82);
  margin-left: 1px;
  height: 100px !important;
}
h1 {
  margin-top: 2%;
  color: white;
}
.text{
  margin-top: 2.5%;
  border: 6px solid rgb(32, 165, 226);
  
}
.btn{
  margin-left: 2%;
  color:white !important;
  margin-right: 3%;
  cursor: pointer;
}
</style>
