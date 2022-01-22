<template>
    <div class="w-full h-28  bg-amber-200 shadow-2xl
        text-center font-serif font-bold
        text-purple-300
        text-9xl py-auto">
        {{ day }}
    </div>
</template>

<script>
const weekday = ["Sun","Mon","Tue","Wed","Thu","Fri","Sat"]
const d = new Date()

export default {
    data() {
        return { day: weekday[d.getDay()] }
    },
}
</script>