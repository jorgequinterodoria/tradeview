<template>
    <div class="Comunnitraders">
        <div class="call-to-action">
            <p class="action-text">Try CommuniTraders Now!</p>
        </div>
    </div>
    <CallToAction />
</template>

<script>
import CallToAction from "./CallToAction.vue"; // Asume que el componente CallToAction está en el mismo directorio

export default {
    name: "Comunnitraders",
    components: {
        CallToAction,
    },
};
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
}

.Comunnitraders {
    /* Layout Properties */
    position: absolute;
    top: 2511px;
    left: 0px;
    width: 1920px;
    height: 422px;

    /* UI Properties */
    background: linear-gradient(360deg, #181F29 0%, #181F29 100%) 0% 0% no-repeat;
    opacity: 1;
}

.call-to-action {
    /* Layout Properties */
    position: absolute;
    top: 20px;
    left: 756px;
    width: 408px;
    height: 41px;

    /* UI Properties */
    font: normal 900 30px/45px Noto Sans;
    letter-spacing: 0px;
    text-align: center;
    color: #FFFFFF;
    opacity: 1;
}
</style>
