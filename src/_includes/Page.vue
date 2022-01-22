<template>
    <div class="gap-8 columns-1 sm:columns-3
        p-10 text-justify">
        <p>{{ article }}</p>
    </div>
</template>

<script>
import { LoremIpsum } from "lorem-ipsum"

const lorem = new LoremIpsum()

export default {
    data() {
        return { article: lorem.generateParagraphs(4) }
    },
}
</script>