<template>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Project ptwo</title>
        <script src="https://cdn.tailwindcss.com"></script>
        <!--<link rel="stylesheet" href="/css/styles.css">-->
    </head>
    <body class="bg-purple-200 ">
        <Header />
        <Page />
    </body>
</html>
</template>

<script>
import Header from "./_includes/Header.vue"
import Page from "./_includes/Page.vue"

export default {
    components: {
        Header,
        Page
    }
}
</script>
