<template>
    <div class="hello">
        <img :src="link" alt="">
    </div>
</template>

<script>
export default {
    name: "HelloWorld",
    props: {
        link: String
    }
}
</script>

