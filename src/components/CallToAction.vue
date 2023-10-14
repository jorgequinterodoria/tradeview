
<template>
    <div class="call-to-action">
        <p class="download-text">Free Download for Tradeview Users</p>
        <div class="vertical-line"></div>
        <button class="contact-button">Contact your broker</button>
        <p class="signup-text">Don’t have a Tradeview Account yet?</p>
        <button class="demo-button">Get a free demo</button>
    </div>
</template>

<script>
export default {
    name: "CallToAction",
};
</script>

<style scoped>

.call-to-action{
    position: absolute;
    top: 50px;
    left: 370px;
}
.download-text {
    position: absolute;
    top: 2650px;
    left: -150px;
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
    top: 2625px;
    left: 213px;
    width: 0px;
    height: 164px;
    border: 1px solid #6E7079;
    opacity: 1;
}

.contact-button {
    position: absolute;
    top: 2690px;
    left: -128px;
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
    top: 2650px;
    left: 265px;
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
    top: 2690px;
    left: 286px;
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
