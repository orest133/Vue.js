<template>
    <div id="exercise2">
        <h1>Exercise 2</h1>
        <!-- 1) Show an alert when the Button gets clicked -->
        <div>
            <button v-on:click="showAlert()">Show Alert</button>
        </div>
        <!-- 2) Listen to the "keydown" event and store the value in a data property (hint: event.target.value gives you the value) -->
        <div>
            <input v-on:keydown="updateValue" type="text">
            <p>{{ value }}</p>
        </div>
        <!-- 3) Adjust the example from 2) to only fire if the "key down" is the ENTER key -->
        <div>
            <input v-on:keydown.enter="updateValue" type="text">
            <p>{{ value }}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Exercise2",
        data: function () {
            return {
                value: ''
            }
        },
        methods: {
            showAlert() {
                alert("Button is clicked!!");
            },
            updateValue(event) {
                this.value = event.target.value;
            }
        }
    }
</script>

<style scoped>

</style>