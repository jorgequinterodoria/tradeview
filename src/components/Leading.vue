<template>
    <div class="custom-component">
        <div>
            <p class="text1">Leading Edge Technology</p>
            <p class="text2">Easy to use management tools, our fastest possible execution and spreads as low as 0.0.</p>
            <p class="text3">
                <span>Quick Guide: CommuniTraders Web User Manual  </span>
                <img class="icon" src="@/assets/icons/Icon awesome-external-link-alt.png" alt="External Link Icon" />
            </p>
        </div>
        <img class="image" src="@/assets/Mask Group 2.png" alt="Mask Group 2 Image" />
    </div>
</template>

<script>
export default {
    name: "Leading",
};
</script>

<style scoped>
.custom-component {
    /* Layout Properties */
    position: absolute;
    top: 1857px;
    left: 0px;
    width: 1920px;
    height: 655px;
    display: flex;
    align-items: center;
    justify-content: space-around;

    /* UI Properties */
    background: #F2F2F2;
    opacity: 1;
}

.text1 {
    /* Layout Properties */
    top: 2106px;
    left: 343px;
    width: 516px;
    height: 49px;

    /* UI Properties */
    font: normal 900 30px/45px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    text-align: left;
    opacity: 1;
}

.text2 {
    /* Layout Properties */
    top: 2177px;
    left: 343px;
    width: 556px;
    height: 85px;

    /* UI Properties */
    font: normal 25px/36px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    text-align: left;
    opacity: 1;
}

.text3 {
    /* Layout Properties */
    top: 2284px;
    left: 343px;
    width: 420px;
    height: 24px;

    /* UI Properties */
    font: normal medium 18px/36px Noto Sans;
    letter-spacing: 0px;
    color: #363636;
    text-align: left;
    text-decoration: underline;
    opacity: 1;
}

.icon {
    /* Layout Properties */
    top: 2289px;
    left: 771px;
    width: 16px;
    height: 14px;

    /* UI Properties */
    opacity: 1;
}

.image {
    /* Layout Properties */
    top: 1942px;
    left: 1006px;
    width: 612px;
    height: 484px;

    /* UI Properties */
    opacity: 1;
}
</style>
  