<template>
    <div class="column items-center justify-between fill">
        <q-btn class="bg-orange-5 text-white">{{ myName }}</q-btn>
        <q-btn class="bg-orange-5 text-white">Shahan Kazi</q-btn>
        <q-btn class="bg-orange-5 text-white">Fahad Kazi</q-btn>
        <redSquare/>
    </div>
</template>

<script>
import script from './script'

export default script;
</script>

<style scoped>
.fill  {
    width: 100%;
    height: 100vh;
}
</style>