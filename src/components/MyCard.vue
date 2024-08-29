<template lang="">
    <div class="card">
      <img :src="image" alt="name" style="width:100%">
      <div class="container">
        <h4><b>ชื่อกรีก : {{namegreek}}</b></h4>
        <p>ชื่อโรมัน : {{nameroman}}</p>
        <p>สมญานาม : {{nickname}}</p>
        <p>รายละเอียด : {{detail}}</p>
      </div>
  </div>
</template>
<script>
export default{
    props: ["namegreek","nameroman","nickname","detail","image"]
}
</script>
<style scoped>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
}
img{
    width: 50px;
    height: 400px;
}
</style>