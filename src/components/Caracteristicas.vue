<template>
    <div class="caracteristicas">
        <Card :icon="img1" titulo="Ideal for Beginner Clients"
            contenido="Increase trading volumes as new traders gain comfort by following successful traders in forex markets and beyond into stocks, options, commodities, and more…" />
        <Card :icon="img2" titulo="Low Barriers to Entry"
            contenido="CommuniTraders software is free and clients can start with just a $100 minimum investment." />
        <Card :icon="img3" titulo="Simple Interface"
            contenido="A simple GUI provides needed features and tools but isn't bogged down by non-core features. This allows clients to get setup quickly and start trading." />
        <Card :icon="img4" titulo="No Long-Term Commitments"
            contenido="Clients can easily signup to start, change signal providers, or stop the service. There is no long-term lockup." />
        <Card :icon="img5" titulo="Funds Safety"
            contenido="CommuniTraders benefits from the same strong regulation and banking partners standalone Tradeview clients enjoy along with transparency and negative balance protection." />
        <Card :icon="img6" titulo="Tradeview Runs CommuniTrader"
            contenido="You will experience the Tradeview service you know and love, no gimmicks or hidden fees, excellent live customer support, and your dedicated account manager." />

    </div>
</template>

<script>
import Card from './Card.vue';
import img1 from '@/assets/icons/Group2806.png'
import img2 from '@/assets/icons/Group2816.png'
import img3 from '@/assets/icons/Group2817.png'
import img4 from '@/assets/icons/Group2819.png'
import img5 from '@/assets/icons/Group2821.png'
import img6 from '@/assets/icons/Group2823.png'
export default {
    name: "Caracteristicas",
    components: {
        Card
    },
    data() {
        return {
            img1,
            img2,
            img3,
            img4,
            img5,
            img6,
        }
    }
};
</script>

<style scoped>
.caracteristicas {
    /* Layout Properties */
    position: absolute;
    top: 1080px;
    left: 0px;
    width: 1920px;
    height: 776px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    background: #FFFFFF;
    opacity: 1;
}
</style>
  