
<template>
    <div class="header">
        <div class="logo">
            <img class="logo-img" src="@/assets/Logo.svg" alt="Logo" />
        </div>
        <div class="nav-items">
            <div class="nav-item">Forex</div>
            <div class="nav-item">Stocks</div>
            <div class="nav-item">Futures</div>
            <div class="nav-item">TradegateHub</div>
        </div>
        <div class="right-items">
            <div class="nav-item">Login</div>
            <div class="nav-item">Contact</div>
            <div class="language-selector">English  <img src="@/assets/icons/Path100.png"/><i class="arrow-down"></i></div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: "Header",
};
</script>

<style scoped>
.header {
    position: absolute;
    top: 0px;
    left: 0.39990234375px;
    width: 1900px;
    height: 119px;
    background: #181F29;
    opacity: 1;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    padding: 0 20px;
}

.logo{
    margin-right: 100px;
}
.logo-img {
    position: absolute;
    top: 32px;
    left: 50px;
    width: 365px;
    height: 56px;
    background: transparent url('@/assets/Logo.svg') 0% 0% no-repeat padding-box;
    opacity: 1;
}

.nav-items,
.right-items {
    display: flex;
}

.nav-item {
    margin: 0 10px;
    cursor: pointer;
}

.language-selector {
    font-size: 14px;
    display: flex;
    align-items: center;
    justify-content: space-between;
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
  