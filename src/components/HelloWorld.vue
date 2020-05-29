<template>
    <div>
        we
        <div id="main" style="width: 600px;height:400px;"></div>
    </div>
</template>
<script>
    export default {
        data() {
            return {}
        },
        methods: {
            initChart() {
                console.log('22')
                // var myChart = echarts.init(document.getElementById('main'));
            }
        },
        mounted() {
            this.initChart()
        }
    }
</script>
