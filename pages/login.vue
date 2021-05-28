<template>
  <div></div>
</template>

<script>
console.log(this.location);
this.location = `https://fluffyscratch.hampton.pw/auth/getKeys/v2?redirect=${Buffer.from(
  this.location.host + "/login/finish",
  "utf-8"
).toString("base64")}`;
</script>