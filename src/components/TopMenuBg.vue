
<template>
    <div class="top-menu-bg">
        <img class="group-30" src="@/assets/Group30.png" alt="Group 30" />
        <div class="horizontal-line"></div>
        <p class="text">
            Tradeview’s CommuniTraders software lets our partners provide value-added copy trading to their clients.
        </p>
        <p class="download-text">Free Download for Tradeview Users</p>
        <div class="vertical-line"></div>
        <button class="contact-button">Contact your broker</button>
        <p class="signup-text">Don’t have a Tradeview Account yet?</p>
        <button class="demo-button">Get a free demo</button>
    </div>
</template>

<script>

export default {
    name: "TopMenuBG",
};
</script>

<style scoped>
.top-menu-bg {
    position: absolute;
    top: 0;
    left: 840px;
    width: 1080px;
    height: 1080px;
    background: #181F29;
    opacity: 1;
    color: #FFFFFF;
}

.group-30 {
    position: absolute;
    top: 346px;
    left: 340px;
    width: 420px;
    height: 118px;
    background: transparent url('@/assets/Group30.png') 0% 0% no-repeat padding-box;
    opacity: 1;
}

.horizontal-line {
    position: absolute;
    top: 546px;
    left: 220px;
    width: 654px;
    height: 0px;
    border: 1px solid #FFFFFF;
    opacity: 1;
}

.text {
    position: absolute;
    top: 563px;
    left: 212px;
    width: 665px;
    height: 129px;
    text-align: center;
    letter-spacing: 0px;
    color: #FFFFFF;
    opacity: 1;
}

.download-text {
    position: absolute;
    top: 783px;
    left: 150px;
    width: 292px;
    height: 24px;

    font: var(--unnamed-font-style-normal) normal var(--unnamed-font-weight-300) 18px/24px var(--unnamed-font-family-noto-sans);
    letter-spacing: var(--unnamed-character-spacing-0);
    text-align: center;
    font: normal normal 300 18px/24px Noto Sans;
    letter-spacing: 0px;
    color: #FFFFFF;
    opacity: 1;
}

.vertical-line {
    position: absolute;
    top: 754px;
    left: 550px;
    width: 0px;
    height: 164px;
    border: 1px solid #6E7079;
    opacity: 1;
}

.contact-button {
    position: absolute;
    top: 833px;
    left: 177px;
    width: 240px;
    height: 55px;
    width: 240px;
    height: 55px;
    border: 1px solid #FFFFFF;
    opacity: 1;
    cursor: pointer;
}

.signup-text {
    position: absolute;
    top: 783px;
    left: 650px;
    width: 294px;
    height: 24px;
    font: normal 300 18px/24px Noto Sans;
    letter-spacing: 0px;
    text-align: center;
    color: #FFFFFF;
    opacity: 1;
}

.demo-button {
    position: absolute;
    top: 833px;
    left: 680px;
    width: 240px;
    height: 55px;
    background: #FF0000;
    opacity: 1;
    color: #FFFFFF;
    text-align: center;
    line-height: 55px;
    cursor: pointer;
}
</style>
  