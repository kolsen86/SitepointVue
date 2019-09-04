<script>
import { Bar } from "vue-chartjs"

export default {
    extends: Bar,
    data() {
        return {
            datacollection: {
                labels: ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December'],
                datasets: [
                    {
                        label: "Data One",
                        backgroundColor: "#f25432",
                        pointBackgroundColor: "white",
                        borderWidth: 1,
                        pointBorderColor: 
                    }
                ]
            }
        }
    }
}
</script>
