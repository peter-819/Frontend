<template>
  <div class="userNav">
    <img src="@/assets/pictures/navigation/user1.jpg" class="userImg">
    <div class="navFont userName">杨天悦</div>
    <img src="@/assets/pictures/navigation/svgs/triangle_black.svg" class="triangle">
    <img src="@/assets/pictures/navigation/notifications_gradient_24dp.png" class="messageIcon">
  </div>
</template>

<script>
import '@/assets/css/font.css'
export default {
  name: 'user'
}
</script>

<style>
  .userNav{
    display: flex;
    vertical-align: middle;
    align-items: center;
  }

  .userImg{
    width: 50px;
    border-radius: 50px;
  }

  .userName{
    line-height: 50px;
    margin-left: 15px;
  }

  .triangle{
    height: 13px;
    width: 13px;
    margin-left: 10px;
    transform: rotate(90deg);
  }

  .messageIcon{
    width: 14px;
    margin-left: 105px;
  }
</style>
