<template>
    <div class="card">
        <div >
            <img :src="icon" alt="Mi Imagen" class="icon" />
        </div>
        <div class="title">{{ titulo }}</div>
        <div class="content">{{ contenido }}</div>
    </div>
</template>

<script>
export default {
    name: "Card",
    props: {
        icon: String,
        titulo: String,
        contenido: String,
    },
};
</script>

<style scoped>
.card {
    /* Layout Properties */
    position: relative;
    width: 516px;
    height: 260px;
    opacity: 1;
    padding: 20px;
    margin: 20px;
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 0px 30px #00000014;
}

.icon {
    /* Layout Properties */
    top: 0px;
    left: 0px;
    width: 50px;
    height: 50px;

    /* UI Properties */
    background-size: cover;
    opacity: 1;
}

.title {
    /* Layout Properties */
    top: 54px;
    left: 0px;
    width: 457px;
    height: 28px;

    /* UI Properties */
    font: normal bold 18px/24px Noto Sans;
    color: #FF0000;
    text-align: left;
    letter-spacing: 0px;
    opacity: 1;
}

.content {
    /* Layout Properties */
    top: 82px;
    left: 0px;
    width: 457px;
    height: 88px;

    /* UI Properties */
    font: normal 300 18px/24px Noto Sans;
    color: #363636;
    text-align: left;
    letter-spacing: 0px;
    opacity: 1;
}
</style>
