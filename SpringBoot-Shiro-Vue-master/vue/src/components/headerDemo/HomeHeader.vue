<template lang = "jade">
  -var c = 'homeHeader'
  -var wrap = c + '__wrap'

  div(class="#{wrap}")
    div(class="logo")
      img(src='../../common/img/logo/GTSlogo.jpg' width="226" height="48")
      | &nbsp;&nbsp;&nbsp;&nbsp;
      span Ark Regulation Database
      | &nbsp;&nbsp;&nbsp;
      img(src='../../common/img/logo/copslogo.jpg' width="50" height="55")

</template>

<script>
  export default {
    name: "homeHeader",
    data() {
      return {
      }
    },
    methods: {
    },
  }
</script>

<style>
  @c homeHeader {
    @d wrap {
      .logo {
        img {
          padding-top: 10px;
          /*width: 226px;*/
          /*height: 48px;*/
          vertical-align:bottom;
        }
        span {
          background-color: rgba(255, 102, 0, 1);
          white-space: nowrap;
          font-family: 'Arial Bold', 'Arial Regular', 'Arial';
          font-weight: 700;
          font-style: normal;
          font-size: 40px;
        }
      }

    }
  }
</style>
