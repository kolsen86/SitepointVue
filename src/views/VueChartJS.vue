<template>
<section class="container">
    <h1>Demo examples of vue-chartjs</h1>
    <div class="columns">
        <div class="column">
            <h3>Line Chart</h3>
            <Line-chart></Line-chart>
        </div>
        <div class="column">
            <h3>Bar Chart</h3>

        </div>
    </div>
    <div class="columns">
        <div class="column">
            <h3>Bubble Chart</h3>

        </div>
        <div class="column">
            <h3>Reactivity - Live update upon change in datasets</h3>

        </div>
    </div>
</section>
</template>

<script>
import LineChart from "@/components/LineChart.vue"
import BarChart from "@/components/BarChart.vue"
import BubbleChart from "@/components/BubbleChart.vue"
import Reactive from "@/components/Reactive.vue"
export default {
    name: "VueChartJS",
    components: {
        LineChart,
        BarChart,
        BubbleChart,
        Reactive
    }
}
</script>
