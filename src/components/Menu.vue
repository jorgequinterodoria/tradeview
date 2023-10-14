<template>
    <div class="menu">
        <div class="menu-item">Markets</div>
        <div class="menu-item">Company <i class="arrow-down"></i></div>
        <div class="menu-item">Accounts</div>
        <div class="menu-item">Platforms <i class="arrow-down"></i></div>
        <div class="menu-item">Pricing</div>
        <div class="menu-item">Introducing Brokers</div>
        <div class="menu-item">Education</div>
        <div class="menu-item">Support <i class="arrow-down"></i></div>
    </div>
</template>
  
<script>
export default {
    name: "Menu",
};
</script>
  
<style scoped>
.menu {
    position: absolute;
    top: 98px;
    left: 0.39990234375px;
    width: 1920px;
    height: 162px;
    background: transparent linear-gradient(180deg, #181F29 0%, #181F29 18%, #181F2960 59%, #181F2900 100%) 0% 0% no-repeat padding-box;
    opacity: 1;
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: white;
}

.menu-item {
    cursor: pointer;
}

.arrow-down {
    margin-left: 5px;
    display: inline-block;
    border: solid white;
    border-width: 0 2px 2px 0;
    padding: 3px;
    transform: rotate(45deg);
}
</style>
  